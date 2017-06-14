# Voting-machine
#Simulates voting and how voters are counted for each party in an election.

class VotingMachine:

      def  __init__(self):
           self.conservative=0
           self.labour=0
       
      def voteConservative(self):
           self.conservative=    self.conservative +  1

      def voteLabour(self):
         self.labour = self.labour + 1

      def clearVotes(self):
           self.conservative==0
           self.labour==0
           
           
      def unDoVote_Labour(self):
          if( self.labour > 0):
              self.labour= self.labour - 1
             
      def unDoVote(self):
          if(self.conservative > 0):
             self.conservative=self.conservative -1
                
      def getTotaldemovotes(self):
          return self.demo

      def getTotalrepvotes(self):
          return self.rep 
