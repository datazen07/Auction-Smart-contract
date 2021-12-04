# Auction-Smart-contract

Implementation:

You will write two versions of the implementation templates: version 1: without modifier (80%) and
version 2 with modifier (20%). We have provided the templates for both versions.
1. Please understand the problems before you proceed.
2. Copy the template into your Remix IDE. Complete the code. You will need to fill in the code at
*ONLY* at the locations indicated. Test it to see if it is operational.
3. Implement version of as Auction.sol and submit for grading. Then update this base version for
Auction.sol for Part 2 requirements, and submit for grading.
Version 1: (80%) Auction.sol: There are 6 tasks where you will fill in the code. You need to review the
code given and understand it fully before you start adding code. This partial code is available in the
course resources section as Auction.sol.

Testing on Remix:

Test the completed code by compiling and running it on Remix JavaScript VM. (i) Account 0 provided by
JavaScript VM is the Auction beneficiary and will not bid. (ii) Navigate to each of the other accounts, and
“register.” You will register four bidders using register function. (iii) The next step is for the bidders to
each bid; for test purposes, you can execute the “bid” function with {{0,1}{1,1}{2,1} } for each of the four
accounts. (iv) Next, execute the “revealWinner” function to determine the winner for each item
randomly, and (v) the getter of the “winners” data can be executed with {0, 1 and 2} as a parameter in
sequence to reveal the winners of the draw respectively. You can do a lot of more testing and
exploration with the buttons provided by the Remix web interface.
