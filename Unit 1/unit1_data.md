# Unit 1 / Text / Data

## Background

For our first challenge, we will tackle a familiar source: the [Ring-tum Phi Archive](https://repository.wlu.edu/handle/11021/26338).

The Ring-tum Phi \(RTP\) is Washington and Lee's student newspaper, published on a weekly basis since 1897. The RTP is a great source for institutional and local history. It can also serve as a window into the college student perspective on current events. For instance, someone interested in the [history of downtown Lexington](http://historiclexington.omeka.wlu.edu/) can learn more about area businesses by the advertisements. Someone interested in the [co-education decision](http://beyondbowties.academic.wlu.edu/) in 1985 could read op-eds from current students.

But how do you find what you're looking for in the RTP? How do you browse if you don't know what you're looking for? Can anyone access it at any time?

Currently, the RTP is available in several forms. Can you tell what they are from the [catalog record](http://annie.wlu.edu:80/record=b1345778~S0)?

1. The entire run of the print newspaper, bound together by volume, sits in the vault in Special Collections. [See what that looks like.](https://i.makeagif.com/media/8-11-2016/aNVqo7.gif)
2. Most of the entire run is available on microfilm. 
3. The current year of the print newspaper is available to public for browsing. 
4. The entire run of the newspaper has been digitized and is available via the [Digital Archive](https://repository.wlu.edu/handle/11021/26338).
5. Question: how is the RTP being captured now?

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

## Digitization & OCR

Running a document through a scanner does result in a perfect copy and paste-able version of that document. If you've ever tried to scan a form or print journal article, you might have found yourself battling with an Adobe product. When you scan a document, even if it turns into a PDF, it is an _image_ of that document.

The process by which computer turns that image into _characters_ that can be manipulated is called **optical character recognition**. There are a [variety of OCR tools available](https://github.com/kba/awesome-ocr), however their quality can vary widely. 

### Activity 2

The type of OCR tool you need depends on your project. If you have modern documents, you might be okay with a less sophisticated tool.

Compare and contrast the output of several OCR tools:

* Use the TIFF files in the `Unit1_Text` in Box.
* Submit the same TIFF file to each of these tools. There's a document with instructions in Box.
  * Adobe Pro
  * Google Drive 
  * Tesseract
* Which tool does a better job? Which is easier to install? To use? Which tool is more efficient for the task at hand? What if you had to OCR 100 years of the RTP?

## Data set

A zip file of the RTP data set is available in our course Box folder. It consists of text files from each issue of the RTP. Or does it?

### Activity 3

Using your new found command line skills, let's learn more about the RTP data.

* Use `pwd` `cd` and `ls` to navigate through the `TesseractOCR` folder. 
* Use `cat` to read a file. Find the manual for `cat`. What else can you do with this command? 
* What happens when you type `ls *.2.txt`?
* Can you figure out how to list all the file names in `TesseractOCR` and send them to a text file? 
* Continue learning by working through the tutorials in the Command Line page using the RTP data. 

### Activity 4

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

**Word of advice: keep a running list of all the changes you make!**

## Data Assessment Activity

Using the skills you have picked up during the last few class sessions, assess the data you have and make a plan for its cleanup. The results of this activity should be turned in with your data set on 10/11. While we will work on aspects of this activity together in class, ultimately this is part of your assignment and you will need to take individual responsibility for its completion. The answers to the following questions should be saved in a text file with your data set, as per instructions on the Assignments page.

* What is the existing file structure of the data set as you you have received it? What can you discern from the directory names? Describe in detail.  Note the inconsistencies.
* Can improvements be made to the file structure and file names?
* What is the granularity of the text files? Page? Issue? Reel? Volume? Year? Are there patterns? How does it change over time?
* Is there duplicate data? How will you handle it?
* How clean is the OCR? How could you estimate this? Does the quality change over time? 
* Based on your proposed research question, what are your priorities for OCR cleanup? Give examples. What are the biggest problems and how will you solve them? 



