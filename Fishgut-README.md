# Homework 10

You will fill out the following
questionnaire for each program and submit the answers as your final homework. You will
also share your questionnaire with the group that created the program __by the end of discussion__.
---
# FISHGUT FEEDBACK

### The Readme

#### 1. Is the Readme file the first document displayed upon lading the Github?  Does this Readme page include a title, and the name and contact information for all project members?
Yes. It includes a good title and names + contact info.

#### 2. Is the purpose of this program clear from the Introduction?  What -in your own words- is the motivation behind the program.
The program is meant to take an OTU file and a file that holds sequencing data and then combine them in effort to analyze it with R. While this is to the point, you could elaborate more. For example, what kind of analyses will be run in R and how will this help in the long run?

#### 3. Is there a program workflow and is it easy to understand?  What -in your own words- is the program workflow?
There is  program work flow, and while it is clear, I think it would be best if was shown as a flow chart or a numbered step-by-step summary of the program. First the program will take an OTU file and a taxonomy file, and will sort through them to put them in alphabetical order and fill empty slots with "unassigned." You can then take the merged fil output and run it in the DAMFish R program to create a "phyloseq" to visualize and analyze the data.

#### 4. Are the dependencies indicated in the workflow?  If there are Hoffman2 specific requirements are they indicated?
Yes there are dependencies. You need to edit the actial data files to ensure that it only has what you want to analyze, one header, unique feature IDs, and : or tab as a delimiter. You wowuld also have to load R packages in the Hoffman terminal

#### 5. Are there instructions for running the program?  Do the instructions make sense?  What would you do to improve the instructions?
There are instructions to run the program, and while the do detail the steps the user must take it would be helpful to maybe number them or just do a bit of reformatting (like changing headers). I also would edit the README.md to display anything that should be a script as script by using the insert bash script on R.

### 6. Is there a section that indicates the files and directories produced by the program?
No

#### 7. Are the research programs / motivations for the program cited?  Are the dependencies cited?
Yes, the dependencies are cited, but it lacks  research programs / motivations (not sure if there is any)
---

### The Scripts

#### 8. Is there a directory that contains all of the program scripts?
The github contains all the scripts, but they are not sorted into 1 directory

#### 9. Do these programs generate a run log?
N/A
---

### The Vignette

#### 10. Is there a directory called Vignette and does it include a test set, the commands used to run the program and the expected output databases?
There is a vignette directory. I'm pretty sure the files for test set are there, but I would put them in on clear directory. The commands are in the README and there is a folder for expected outputs. 

#### 11. Where you able to run the Vignette using the small test dataset? If not what errors did you get?  If so was it easy to run the dataset?  Where the instructions clear.
Yes it did work for the small dataset! The instructions were clear for the vignette small test set

#### 12. Where you able to reproduce the expected output?  If not what was different.
I was a ble to produce the expected output
---

### General

#### 13. Give __at least two__ suggestions for ways to improve the GitHub page or the operation of the program.
I would look back over the README and just make it consistent in reference to the formatting 
I would also make sure that all the script that you include in any of the READMEs be displayed as a script and not text
Make sure to add expected outputs list onto the README too!