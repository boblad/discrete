#Assignment 5#
#Bryant Oblad A01770171#

##Question 1##


1. The Cannibals and Missionaries Problem. Three cannibals and three missionaries are standing together on the West side of a river bank. A boat is available that will hold up to two people. If the missionaries are ever outnumbered, on a bank or in the boat, the cannibals will eat them. Please generate a procedure to get the six people to the East side of the river bank (uneaten).

_Claim_: There is a solution to getting all 6 people to the other side of the bank while following the rules of the game.

_Proof_: See the image "Figure 1" attached to the back of this packet.
This image will demonstrate the process needed to complete the cannibals and missionaries problem with C being a cannibal and M being a missionary.


##Question 2##

2. Suppose C = {c1, c2, . . . , cn} is a collection of chemicals which must be stored very carefully at very specic temperatures. For each ci ∈ C, you know the lowest temperature at which it can be stored, call it i, and highest temperature at which it can be stored, call it h$_i$. The containers that will be used to store the chemicals are extremely expensive (they may be train cars) and so it is important to minimize the number of containers used for storing the chemicals. Solve the problem in the general case; that is, develop an algorithm or scheme for determining the smallest number of temperature-controlled storage units into which the chemicals can be stored.

_Claim_: The lowest number of temperature-controlled storage units can be determined by using the highest low's chemical to depict a container

_Proof_: See the image attached to the back of this packet. With the example I show on Figure 2, We see that if we take the first, lowest highest temperature of a chemical in this case C$_1$ that the chemical will group with the highest count of chemicals possible. This proves that for any sitution and any amount of chemicals, taking the lowest temperature chemical and following it to its high and grouping all joined chemicals, will ensure the least amount of chemical containers.
