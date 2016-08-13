
Project: Chess Playing Robot
Sponsored by: Robotics Club IIT Kanpur
Link to project video: https://youtu.be/qM6v5F6DXPY?list=PLJnixDjbax5djwgONCMpo3PXhzUpyR_XX

CPRv1.3 version is the first code with simplest artificial intelligence.
Got completed on 11:59 pm 14th June 2014.

CPRv1.4 version has implemented search algorithms, i.e., minimax but 
still alpha beta pruning has not been implemented yet.
The fault in pawn moves [4x6xW and 3x1xB move checked] improved.
Now, as per my knowledge everything is correct. Feeling happy after getting defeated!! Really
Special thanks to SAUMYA, AMIT, SHILPI

**CPRv1.5**  20th June 2014, 10:15pm
This version is new becuase of using alpha beta algorithms which makes the searching
faster. It is really very smart.
Still there is space for improvements:-
1. Flagging the event of loss of game
2. Using historical moves initially instead of searching
3. Improving GUI



The Chess Board is defined as follows : 

(0,0) (0,1) (0,2) (0,3) (0,4) (0,5) (0,6) (0,7)
(1,0) (1,1) (1,2) (1,3) (1,4) (1,5) (1,6) (1,7)
(2,0) (2,1) (2,2) (2,3) (2,4) (2,5) (2,6) (2,7)
(3,0) (3,1) (3,2) (3,3) (3,4) (3,5) (3,6) (3,7)
(4,0) (4,1) (4,2) (4,3) (4,4) (4,5) (4,6) (4,7)
(5,0) (5,1) (5,2) (5,3) (5,4) (5,5) (5,6) (5,7)
(6,0) (6,1) (6,2) (6,3) (6,4) (6,5) (6,6) (6,7)
(7,0) (7,1) (7,2) (7,3) (7,4) (7,5) (7,6) (7,7)

To move a piece from (1,4) to (3,4) input :
		1 <space> 4 <space> 3 <space> 4 <return>
		
Hit return for the computer to process his move
