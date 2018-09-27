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

### Topics:
* Coeducation
* Integration 
* Bill Clinton 
* Fraternity Renaissance
* Sit in (Vietnam) 
* Jesse Jackson
* MLK 
* Y2K
* “The move” of Leyburn Library
* WW1
* Ambulance Corps 
* WW2
* ATO steals a train
* Hurricane Camille 
* Virginia Horse Center
* Prohibition 
* Lee Chapel 1920s controversy or 1960s renovation
* Mock Con (Alvin Barclay) 
* Buildings! Burning of Tucker, Lenfest/Wilson, Elrod Commons, 
* Cold War
* Best Fancy Dress theme 
* Best Advertisement
* Best Greek story:
* Best sports story: 

## Activity 3
To search the RTP from your computer, open it in your text editor. 

In Sublime/Atom:
* File > Open > select TesseractOCR. If you select the file, then press open, rather than double clicking and entering the folder, you should see all the folders in the left pane. 
* Use ```Cmd + F``` to search or the Find menu item. If you select a folder name or specific file on the left, you can search on just that folder/file.

# Data Assessment 
Record the answers to all questions in a text file saved to DCI102-studentname Box Folder. 

## Part 1 - File structure + command line
Using your new found command line skills, let's learn more about the RTP data. 

* Use `pwd` `cd` and `ls` to navigate through the `TesseractOCR` folder. 
	* What is the basic file structure of the data set as you have received it? What about the file names? What are the patterns? Where (or when) do the patterns change? 
	* What is the granularity of the text files? Does each file contain one page? Issue? Reel? Volume? Year? 
* Use `cat` to read a file. Find the manual for `cat`. What else can you do with this command?
* What happens when you type `ls *.2.txt`?
* Can you figure out how to list all the file names in `TesseractOCR` and send them to a text file?
* Last step: type `history` and paste your command history into the text file. 

## Part 2 - RegEx 
Using your new found regex skills, let's start cleaning up some RTP data.

* In Sublime or Atom, open the TesseractOCR folder so the left pane contains the file structure. 
* Look around for repetitive problems in the OCR. List 5 problems you find more than once. 
* Start testing regular expressions on those problems. List your successful tests. You can use regex101.com if it helps. 
* Answer the following: 
	* How would you find large spaces between words?
	* Are there frequent misspellings of common words? \(Ring-tum, Rockbridge, Washington for instance\).

## Part 3 - Lexos
With your data subset, start exploring Lexos. Use the documentation often!
* What looks the most helpful on the `Prepare > Scrub` menu?
* What are lemmas?
* What is a document term matrix?
* Which visualization is most useful?
* What is interesting in the `Analyze` menu? Why?


## Part 4 - Next steps
* What are the biggest problems with the data set?
* Which problems can you solve?
* Based on your proposed research question, what are your priorities for OCR cleanup? 
* What's going in your subset of data? 


## Bonus round - script reading
Box also contains the folder `/tesseractscript` with the original scripts used to create the OCRed text files. The `tesseract_process.sh` script was written by Professor Sara Sprenkle in 2014 in order to create a data set for another DH course.

Even if you don't understand everything that's happening in the script, there is one important detail that affects your data. Can you find it?