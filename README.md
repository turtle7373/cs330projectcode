# cs330projectcode

Bryan Nguyen

build instrctions 

Both my files are already made with java and made executable to a jar file. so you can go right to testing afterr you clone it.

If you want to use gradle you can run gradle clean to gradle shadowJar and it will clean removes the build file and shadowJar will remakes the file.

You can also build an execuatble jar file with /gradlew jar on the java files is another option in linux/ubuntu.

You can also use gradlew clean on the file as well to run it withoug executable.

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
