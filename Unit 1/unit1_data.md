# Unit 1 / Text / Data 

## Background
For our first challenge, we will tackle a familiar source: the [Ring-tum Phi Archive](https://repository.wlu.edu/handle/11021/26338). 

The Ring-tum Phi (RTP) is Washington and Lee's student newspaper, published on a weekly basis since 1897. The RTP is a great source for institutional and local history. It can also serve as a window into the college student perspective on current events. For instance, someone interested in the [history of downtown Lexington](http://historiclexington.omeka.wlu.edu/) can learn more about area businesses by the advertisements. Someone interested in the [co-education decision](http://beyondbowties.academic.wlu.edu/) in 1985 could read op-eds from current students. 

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
Running a document through a scanner does result in a perfect copy and paste-able version of that document. If you've ever tried to scan a form or print journal article, you might have found yourself battling with an Adobe product. When you scan a document, even if it turns into a PDF, it is an *image* of that document. 

The process by which computer turns that image into *characters* that can be manipulated is called **optical character recognition**. There are a variety of OCR tools available, however their quality can vary widely. 

### Activity 2
The type of OCR tool you need depends on your project. If you have modern documents, you might be okay with a less sophisticated tool. 

Compare and contrast the output of several OCR tools: 
* Use the TIFF files in the ```Unit1_Text``` in Box.
* Submit the same TIFF file to each of these tools. There's a document with instructions in Box.
  * Adobe Pro
  * Google Drive 
  * Tesseract
* Which tool does a better job? Which is easier to install? To use? Which tool is more efficient for the task at hand? What if you had to OCR 100 years of the RTP?

## Data set 
A zip file of the RTP data set is available in our course Box folder. It consists of text files from each issue of the RTP. Or does it?

### Activity 3
Using your new found command line skills, let's learn more about the RTP data. 
* Use ```pwd``` ```cd``` and ```ls``` to navigate through the ```TesseractOCR``` folder. 
* Use ```cat``` to read a file. Find the manual for ```cat```. What else can you do with this command? 
* What happens when you type ```ls *.2.txt```?
* Work through the tutorials in the Command Line page using the RTP data. 
* Can you figure out how to list all the file names in ```TesseractOCR``` and send them to a text file? 

### Activity 4
Using your new found Regex skills, let's start cleaning up some RTP data. 
* Using Sublime Text, 


The zip file also contains the folder ```/tesseractscript``` with the original scripts used to create the OCRed text files. This script was written by Professor Sara Sprenkle in 2014 in order to create a data set for another DH course. 

### Activity 5 TBD

