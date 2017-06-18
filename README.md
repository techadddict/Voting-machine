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
             
      def unDoVote_Conservative(self):
          if(self.conservative > 0):
             self.conservative = self.conservative -1
                
      def getTotalConservativesVotes(self):
          return   self.conservative

      def getTotalLabourVotes(self):
          return  self.labour 
