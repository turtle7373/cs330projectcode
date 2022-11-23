# cs330projectcode

Bryan Nguyen

part 1 
The program takes in your id which is 5 digits long.
If it isn't 5 digits long you must re-enter it.
Once it has the id it will generate the unlocking code and locking code.
It will then as for one long string of input and the program will read the whole string character by character till and determine if the final state of the machine is locked or unlocked. 

part 2
The program is the same but this time the input is a random string of numbers and will run until the machine is unlocked. 
Once the machine is unlocked it will stop and count how many numbers it read and state so. 

To test I inputed every test case I came up with on eclispe IDE. 
test case inlcude 
numbers infront of unlock or lock code
numbers after unlock or lock code 
unlock or lock code in between numbers 
only unlock code 
only lock code 
numbers without unlock or lock code 
numbers smaller than lenght of unlock and lock code 
and ran it with the random number generator 

My programs contains only if and else statements with while and for loops to read and compare each character till the correct code is found and if it isn't it will just continue to loop again. It also contains random number generator for part 2. 

