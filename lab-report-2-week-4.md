# Lab Report 2, Week 4
**Hello Class!** Welcome to UCSD CSE 15L. This is the second lab report for the course. In this lab, I'm going to show you three different bugs and the relationship between the bug, the symptom, and the failure-inducing input.

## Bug #1:
Below is a screenshot of code change diff from Github for the first bugs:
![Image_code_change_1](add_later)

The link to the test file for a failure-inducing input is here: [Link](https://github.com/jeffyuan2022/markdown-parser/blob/main/test-file.md)

The symptom of that failure-inducing input is ***Infinite Loop***
Below is a screeshot of the symptom in command line:
![Image_symptom_1](add_later)

**The relationship between the bug, the symptom, and the failure-inducing input:**
Due to the failure-inducing input, that there is one additional empty line (line 5) of code after the last link in the test file, the testing program (MarkdownParse.java) caused a bug that it cannot find the next open bracket after the last link in the test file and it can't end the while loop. So as the symptom, it goes into an infinite loop when running the test.

## Bug #2:
Below is a screenshot of code change diff from Github for the second bugs:
![Image_code_change_2](add_later)

The link to the test file for a failure-inducing input is here: Link

The symptom of that failure-inducing input is ***Infinite Loop***
Below is a screeshot of the symptom in command line:
![Image_symptom_2](add_later)

**The relationship between the bug, the symptom, and the failure-inducing input:**
This bug is caused by the two empty lines of code that are after the last link (lines 4 and 5). The symptom of this test is that it produces an infinite loop due to the fact that the failure-inducing input causes the program to not check the indexOf output after it finds the very last link in the file.

## Bug #3:
Below is a screenshot of code change diff from Github for the third bugs:
![Image_code_change_3](add_later)

The link to the test file for a failure-inducing input is here: Link

The symptom of that failure-inducing input is ***Infinite Loop***
Below is a screeshot of the symptom in command line:
![Image_symptom_3](add_later)

**The relationship between the bug, the symptom, and the failure-inducing input:**
This bug is caused by the two empty lines of code that are after the last link (lines 4 and 5). The symptom of this test is that it produces an infinite loop due to the fact that the failure-inducing input causes the program to not check the indexOf output after it finds the very last link in the file.
