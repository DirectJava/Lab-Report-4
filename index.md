1. Logging into ieng6:

In order to log in to my ieng6 account, I typed in `ssh <ieng6 email>` and then the password.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/3601f68c-7f85-4be1-8efb-77a43dc1c7c7)

2. Cloning the Repository:

To clone the repository, I basically typed in `git clone <link to the repository>`

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/d89202ac-4df1-4951-9485-31eb645e7809)

3. Running the Tests:

To run the tests, I had to type in `ls` to search for the particular file that I'm looking for. Here, I chose FileExamples.java. Then, I typed in `bash test.sh` to see if the tests ran successfully. As a bonus, I typed in typed in `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and then `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` to prove that both ways work.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/f1dd54bb-dfdb-4a9c-8d56-a5c606d400cd)
![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/043dc491-351b-4035-a3dd-9ff2a37cfa0e)

On the left is the photo of `bash test.sh` and on the right is the `-cp` hamcrest insertion.

4. Editing the File:
 
 In order for me to edit the file, I accessed it by typing in `vim FileExamples.java` to edit the file in vim mode. In order to get to the part I wanted, I just typed `j` multiple times until I reched the last loop in `merge`. At that point, I just used my `l` key to shift right until reaching the `1` in `index1`. Once I reached that step, I typed `x` to delete the `1` and then `a` in order to facilitate typing in the text. After that I pressed the `<--` multiople times until I reached the desired spot to type in `2`.
 
 ![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/45990300-2105-4eb2-b934-26e72f955544)

5. Re-Run the Tests:

In order to re-run the test, I just typed in `:wq` to save my work and exit out of vim. Once I am outside of vim, I can just type in `-cp` hamcrest files to re-run the test. As a bonus once again, I also tried typing in `bash test.sh` to run the test.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/7ebc0a55-c068-41df-99dd-8c4d584ea44a)

Above the blue line is the `-cp` interpretation, and below the blue line is with `bash test.sh`.

6. Commit and push:

In order to save the files...
