### Activity 1
Let's explore what's in the Ring-tum Phi! 
* Through the Digital Archive or the text files on your machine, start browsing the Ring-tum Phi.
* Not sure where to start? 
  * Look up the year you were born.
  * Find coverage of a major historical event.
  * Find Mock Con coverage. 
  * Mention of sorority/fraternity? 
  * Did your parent/older friend attend W&L?
  * Sports, music, or other W&L events?
  * Other ideas: diversity, alcohol/drug policies, gender issues, town and gown relations...
* Pay attention to your browsing experience. Is it easy to find what you're looking for? Are you tumbling down research rabbit holes?

### Activity 2
The type of OCR tool you need depends on your project. If you have modern documents, you might be okay with a less sophisticated tool. 

Compare and contrast the output of several OCR tools: 
* Use the TIFF files in the ```Unit1_Text``` in Box.
* Submit the same TIFF file to each of these tools. There's a document with instructions in Box.
  * Adobe Pro
  * Google Drive 
  * Tesseract
* Which tool does a better job? Which is easier to install? To use? Which tool is more efficient for the task at hand? What if you had to OCR 100 years of the RTP?

### Activity 3
Using your new found command line skills, let's learn more about the RTP data. 
* Use ```pwd``` ```cd``` and ```ls``` to navigate through the ```TesseractOCR``` folder. 
* Use ```cat``` to read a file. Find the manual for ```cat```. What else can you do with this command? 
* What happens when you type ```ls *.2.txt```?
* Can you figure out how to list all the file names in ```TesseractOCR``` and send them to a text file? 
* Continue learning by working through the tutorials in the Command Line page using the RTP data. 

### Activity 4
Box also contains the folder ```/tesseractscript``` with the original scripts used to create the OCRed text files. The ```tesseract_process.sh``` script was written by Professor Sara Sprenkle in 2014 in order to create a data set for another DH course. 

Even if you don't understand everything that's happening in the script, there is one important detail that affects your data. Can you find it?


### Activity 5
Using your new found regex skills, let's start cleaning up some RTP data. 
* In Sublime Text, ```File > Open``` the TesseractOCR on your Desktop. The menu option ```View > Sidebar``` should show you a tree of all the files in this folder. 
* Clicking on a file once will preview it, double clicking will actually open it. 
* Right click on a directory and choose ```Find in folder```. Now you can use the find and replace function in all the text files. Remember to select the button ```.``` to turn on regex capabilities. If you type in a search, then press the enter key, you should get a new window with all the search results gathered together. This is useful for scanning results in multiple files.
* Using any of the materials from Dr. Mickel's visit or our readings, start looking for patterns and apply regex searches to the text.
* Don't forget that you can consult the newspaper images in the Digital Archive. Before you undertake a large scale correction, double check that you won't be altering content you still need.
* Potential questions:
  * How would you find large spaces between words? 
  * Are there frequent misspellings of common words? (Ring-tum, Rockbridge, Washington for instance).
  * Can you do anything about the gibberish?