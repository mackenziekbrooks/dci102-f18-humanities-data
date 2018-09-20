# Unit 1 / Activities

## Activity 1: get the data!

* In Box ```/ DCI102-F18-data / Uni1_Text``` there is a zip file ```TesseractOCR```. 
* Do not search then click on this folder! It will unzip, expand, and take up a lot of space. 
* Instead, download this file to your Desktop, then unzip/decompress to view the contents. 

## Activity 2: RTP Scavenger Hunt

1. Form teams of three. Each team is responsible for 3-4 topics + "best of" topics. 
2. In your team's Box note, list your team name, participants, and your topics as headings. 
3. For each topic, find the relevant RTP issue in BOTH the Digital Archive and the data set on your computer. 
4. Paste in a URL from the Digital Archive AND the filename for the text file in your data set. 
5. As you go along, note your observations/frustrations about the data set at the bottom of the Box note. What was hard to find? Why? Where are the inconsistencies? How's the OCR? 


## Activity 3

Using your new found command line skills, let's learn more about the RTP data.

* Use `pwd` `cd` and `ls` to navigate through the `TesseractOCR` folder. 
* Use `cat` to read a file. Find the manual for `cat`. What else can you do with this command? 
* What happens when you type `ls *.2.txt`?
* Can you figure out how to list all the file names in `TesseractOCR` and send them to a text file? 
* Continue learning by working through the tutorials in the Command Line page using the RTP data. 

## Activity 4

Box also contains the folder `/tesseractscript` with the original scripts used to create the OCRed text files. The `tesseract_process.sh` script was written by Professor Sara Sprenkle in 2014 in order to create a data set for another DH course.

Even if you don't understand everything that's happening in the script, there is one important detail that affects your data. Can you find it?

### Activity 5

Using your new found regex skills, let's start cleaning up some RTP data.

* In Sublime Text, `File > Open` the TesseractOCR on your Desktop. The menu option `View > Sidebar` should show you a tree of all the files in this folder. 
* Clicking on a file once will preview it, double clicking will actually open it. 
* Right click on a directory and choose `Find in folder`. Now you can use the find and replace function in all the text files. Remember to select the button `.` to turn on regex capabilities. If you type in a search, then press the enter key, you should get a new window with all the search results gathered together. This is useful for scanning results in multiple files.
* Using any of the materials from Dr. Mickel's visit or our readings, start looking for patterns and apply regex searches to the text.
* Don't forget that you can consult the newspaper images in the Digital Archive. Before you undertake a large scale correction, double check that you won't be altering content you still need.
* Potential questions:
  * How would you find large spaces between words? 
  * Are there frequent misspellings of common words? \(Ring-tum, Rockbridge, Washington for instance\).
  * Can you do anything about the gibberish?

### Activity 6: Data Assessment

Using the skills you have picked up during the last few class sessions, assess the data you have and make a plan for its cleanup. The results of this activity should be turned in with your data set on 10/10. While we will work on aspects of this activity together in class, ultimately this is part of your assignment and you will need to take individual responsibility for its completion. The answers to the following questions should be saved in a text file with your data set, as per instructions on the Assignments page.

* What is the existing file structure of the data set as you you have received it? What can you discern from the directory names? Describe in detail.  Note the inconsistencies.
* Can improvements be made to the file structure and file names?
* What is the granularity of the text files? Page? Issue? Reel? Volume? Year? Are there patterns? How does it change over time?
* Is there duplicate data? How will you handle it?
* How clean is the OCR? How could you estimate this? Does the quality change over time? 
* Based on your proposed research question, what are your priorities for OCR cleanup? Give examples. What are the biggest problems and how will you solve them? 

## Project planning

On paper or on your computer, answer the following questions:  
1. What is my research question or topic?  
2. What are the biggest problems I have found with the data? What are realistic solutions?  
3. What methods/tools am I interested in using?  
4. What resources do I need?  
5. What are my next steps? Break them down!

