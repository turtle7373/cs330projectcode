# cs330projectcode

Bryan Nguyen

build instrctions 

first copy part1.java file and part2.java file and make your own java files for each of them. 

make sure they are java files(clone them)

use command line javac part1.java and javac part2.java to make the class files of each 

make a text file and name it manifest.txt

in that file have Main-Class: (which ever part is being made into jar) (with 2 enters after)

so example it will look like this Main-Class: part1 (2 enter lines part)

so after u have the manifest.txt with stuff in it use the 

next use the command jar cfm part1.jar manifest.txt part1.class  (this will make the first jar file) (make sure int he manifest.txt it is Main-Class: part1 (With the 2 enter lines)

next use the command jar cfm part2.jar manifest.txt part2.class  (this will make the first jar file) (make sure int he manifest.txt it is Main-Class: part2 (With the 2 enter lines)

To test you download the part1 and part2 jar files.

Open command prompt and locate file that your downloads are located. 

ex (C:\Users\nguye\Downloads>)

and use java -jar jarfilename.jar

so for running part 1 type (java -jar part1.jar)

and test.

and for part 2 type (java -jar part2.jar)

and test.


part 1 
The program takes in your id which is 5 digits long.
If it isn't 5 digits long you must re-enter it.
Once it has the id it will generate the unlocking code and locking code.
It will then as for one long string of input and the program will read the whole string character by character till and determine if the final state of the machine is locked or unlocked. 

part 2
The program is the same but this time the input is a random string of numbers and will run until the machine is unlocked. 
Once the machine is unlocked it will stop and count how many numbers it read and state so. 

To test I inputed every test case I came up with on eclispe IDE. 

the id will always be 33441

test case inlcude 

numbers infront of unlock or lock code
input:4654334411
input:4554334414

numbers after unlock or lock code 
input:3344114554
input:3344144554

unlock or lock code in between numbers 
input:45453344114545
input:45453344144545

only unlock code 
input:334411

only lock code 
input:334414

numbers without unlock or lock code 
input:4546849486

numbers smaller than lenght of unlock and lock code 
input:54

and ran it with the random number generator 
input will be random

Memo

My programs contains only if and else statements with while and for loops to read and compare each character till the correct code is found and if it isn't it will just continue to loop again. It also contains random number generator for part 2. 

![image](https://user-images.githubusercontent.com/118865861/203473448-7fd08883-810c-4fc6-8dc1-ed732cd55778.png)

Email me at bnguyen11@hawk.iit.edu for any questions.
