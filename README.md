# Voting-machine
#Simulates voting and how voters are counted for each party 

class VotingMachine:

      def  __init__(self):
           self.demo=0
           self.rep=0
       
      def voteDemocrat(self):
          self.demo = self.demo + 1

      def voteRepublican(self):
          self.rep = self.rep + 1

      def clearVotes(self):
          self.rep = 0
          self.demo =0

      def getTotaldemovotes(self):
          return self.demo

      def getTotalrepvotes(self):
          return self.rep 
#create objects and use methods
myVotingMachine=VotingMachine()
myVotingMachine.voteDemocrat()
myVotingMachine.voteDemocrat()
myVotingMachine.voteDemocrat()
myVotingMachine.voteRepublican()
print(myVotingMachine.getTotaldemovotes() )
print(myVotingMachine.getTotalrepvotes() )
