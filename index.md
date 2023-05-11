# Khoi Nguyen - Lab 3
### Research Commands
In this lab, I will be discussing the 'grep' command and four command-line options or alternates to the 'grep' command. <br>
To start, we must define what the 'grep' command is and its functionality. 'grep' is a command for performing filter and search operation in a file or a folder or in the output of another command. <br>

The syntax of 'grep' is given by the following: <br>
```
grep [options] pattern [files]
```
<br>
To better visualize, the following image is a screenshot of the syntax of 'grep' command syntax. <br>
![Image](lab3_1.jpg) <br>
In this screenshot, we see that 'grep' is filtering out all files that contains "biomed" in it. Then it is saving all the outputs into the "grep-results.txt". Afterwards, we use the 'wc' command to print out the line count, word count, and character count of our saved outputs in "grep-results.txt". <br>
<br>
**Four Alternatives to 'grep'** <br>
1) *'-r' command* <br>
-r (or --recursive): This option tells grep to search for the specified string in all files within the specified directory and its subdirectories. This is useful when you need to search for a string in a large number of files within a directory tree. <br>
The following is the syntax for '-r' command: <br>
```
grep -r [specified string] [file]
```
The following image is a sample of it's application using it on files and directories from ./technical. <br>
![Image](lab3_2.jpg) <br>
Here we searched for the specificed string of "industry" in ```technical/plos``` where the ```pmed.0020281.txt``` is located. The string is searched in that file then it's output is saved to ```results1.txt```. Afterwards, its contents are printed using ```cat```.

