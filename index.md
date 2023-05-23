I. Logging into ieng6:

In order to log in to my ieng6 account, I typed in `ssh <ieng6 email>` and then the password.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/3601f68c-7f85-4be1-8efb-77a43dc1c7c7)

II. Cloning the Repository:

First, I forked the repository by using the fork button on the right hand corner. Going back to the GitHub Desktop, I clicked on clone repository and chose `lab7` for cloning.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/816a31e5-24b8-4e7c-9e2b-e8b201799189)

That's the forking process.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/85d79e04-7224-4945-a5c4-73917fbd5e06)

That's the cloning process

III. Running the Tests:

To run the tests, I had to type in `ls` to search for the particular file that I'm looking for. Here, I chose FileExamples.java. Then, I typed in `bash test.sh` to see if the tests ran successfully. As a bonus, I typed in typed in `javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java` and then `java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests` to prove that both ways work.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/f1dd54bb-dfdb-4a9c-8d56-a5c606d400cd)
![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/043dc491-351b-4035-a3dd-9ff2a37cfa0e)

On the left is the photo of `bash test.sh` and on the right is the `-cp` hamcrest insertion.

IV. Editing the File:
 
 In order for me to edit the file, I accessed it by typing in `vim FileExamples.java` to edit the file in vim mode. In order to get to the part I wanted, I just typed `j` multiple times to scroll down until I reched the last loop in `merge`. At that point, I just used my `l` key to shift right until reaching the `1` in `index1`. Once I reached that step, I typed `x` to delete the `1` and then `a` in order to facilitate typing in the text. After that I pressed the `<--` multiople times until I reached the desired spot to type in `2`.
 
 ![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/45990300-2105-4eb2-b934-26e72f955544)

V. Re-Run the Tests:

In order to re-run the test, I just typed in `:wq` to save my work and exit out of vim. Once I am outside of vim, I can just type in `-cp` hamcrest files to re-run the test. As a bonus once again, I also tried typing in `bash test.sh` to run the test.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/7ebc0a55-c068-41df-99dd-8c4d584ea44a)

Above the blue line is the `-cp` interpretation, and below the blue line is with `bash test.sh`.

VI. Commit and push:

In order to commit to all changes, I used `git status` to see if I had saved it or not. Knowing that the `modified ListExamples.java` is in red text, I typed in `git add ListExamples.java` to let java know that I made these changes and want to keep them up to date. I then typed in `git status` to check `modified ListExamples.java`, only to find out that text is no longer in red font, but rather in green font. Once that's ready, I typed `git commit m "replaced index1 with index2" in order to submit the file with the message in regards to changes been made.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/8b20b3f2-ee61-4486-bfc4-cc432040fd86)

After that, I typed `git push` to send the updated text in my repository.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/d21ed840-4769-4e19-858f-90bbf6879530)

VII Final Product:

Here is my repository showing all changes made.

![image](https://github.com/DirectJava/Lab-Report-4/assets/122843554/20a40b71-a721-43cd-9ed4-521f67da89d9)

