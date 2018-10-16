# Unit 1 / Text / Methodology

There are a wide variety of methods for analyzing textual data. Obviously, we will not be able to cover them all in-depth. The goal of this unit is to introduce you to text analysis methods and the steps required to assemble a textual data set. Because this is a data-focused course, we are not spending time on digital methods for close reading. But they do exist!

## Defining methods

### Word frequency or counting words

Word frequency is a good place to start. How many times does a specific word occur in a document? In a corpus?

You've probably seen this executed in the form of a word cloud. The more frequently a word appears, the larger the size.

For more introduction, check out ["Basic Text Mining: Word Clouds, their Limitations, and Moving Beyond."](http://www.themacroscope.org/?page_id=633)

### Collocation and context

So we have some frequently-used words. What about their neighbors? Are there patterns to the words that appear around our frequently-used words? Where is the document do those words appear? Near the beginning or the end?

### N-grams

For our purposes, n-grams are phrases of a certain length or "n". Technically, linguists consider n-grams to be "a contiguous sequence of n items from a given sequence of text or speech" \([Wikipedia](https://en.wikipedia.org/wiki/N-gram)\).

### Topic modeling

A complex, statistical method for determining the topic or a list of topics of a document/corpus.

See [Topic Modeling Made Just Simple Enough](https://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/) by Ted Underwood.

[Topic Modeling tool](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)

### Sentiment analysis

Sentiment analysis is a form of "natural language processing" that attempts to determine whether a chunk of text is positive, negative, or some other subjective measurement.

As you might imagine, this type of analysis is useful for determining public opinion - be it a brand, political message, or something else that is hashtag-able.

[Visualizing Twitter Sentiment](https://www.csc.ncsu.edu/faculty/healey/tweet_viz/) is a great way to see what sentiment analysis looks like in action. Try \#wlu20 to see how the first-years are feeling.

### Classification and named entity recognition

Classification and NER are other methods of "natural language processing" that you might encounter. We won't spend much time with them in this course, but you should be aware of the terms. Both are machine-learning methods to figure out if a document or individual words/phrases match a particular model. Classification could be used to determine if an email is spam. NER could be used to extract the names of people or places mentioned in a document.

[Scattertext](https://github.com/JasonKessler/scattertext) visualization tool

## Tools

### Lexos
This [tool](http://lexos.wheatoncollege.edu/upload) from Wheaton College performs some powerful pre-processing of your corpus for text analysis. 

### Wordle

Word clouds are a simple way to get started. Copy and paste text from the RTP into [Wordle](http://www.wordle.net/).

### Voyant

[Voyant](http://www.voyant-tools.org/) is a popular text analysis tool. It accepts single documents or entire corpora. The number of features can be a little overwhelming, so be sure to check out the [documentation](http://www.voyant-tools.org/docs/#!/guide/about).

I recommend [running Voyant locally](http://docs.voyant-tools.org/resources/run-your-own/voyant-server/) so it doesn't stress their servers.

### AntConc

[AntConc](http://www.laurenceanthony.net/software/antconc/) is another tool for performing linguistic analysis of a corpus. It is definitely powerful, but the results can be harder to interpret.

The Programming Historian has a lesson on "[Corpus Analysis with AntConc](http://programminghistorian.org/lessons/corpus-analysis-with-antconc)."

### Google n-gram and Bookworm

[Google Books Ngram Viewer](https://books.google.com/ngrams) is a popular tool for visualizing n-grams over time in the Google Books data set.

Prof. Brandon Walsh delves into the nuances of the Ngram Viewer over on his [text analysis workbook](https://bmw9t.gitbooks.io/introduction-to-text-analysis/content/issues/google-ngram.html).

You can apply the same technology to your own corpus with a took called [Bookworm](http://bookworm.culturomics.org/).

### MALLET and Serendip

[MALLET](http://mallet.cs.umass.edu/http://mallet.cs.umass.edu/) stands for MAchine Learning for LanguagE Toolkit. It's a powerful command line tool with many features, including topic modeling. You're welcome to learn more about how MALLET works, but don't worry too much about understanding the statistics behind it.

Check out [Getting Started with Topic Modeling and MALLET](http://programminghistorian.org/lessons/topic-modeling-and-mallet).

Scott Enderle's Topic Modeling Tool [Quickstart Guide](https://senderle.github.io/topic-modeling-tool/documentation/2017/01/06/quickstart.html)

[Serendip](http://vep.cs.wisc.edu/serendip/) is a visual interface for interacting with the topic models of a corpus. Using their sample data, you can compare topics across all of Shakespeare's plays. It's also possible to load in your own corpus.

### Natural Language Toolkit \(NLTK\)

[NLTK](http://www.nltk.org/) is a Python library containing a number of text analysis tools. If you feel comfortable with the command line or have programming experience, you might want to explore this option.

Check out the [Steinheil Affair project on GitHub](https://github.com/wludh/frenchnewspapers) for an example of what can be with NLTK.

## Evaluation questions

* What do you think of the results? What's surprising? What's not? 
* How about the tool itself? What options do you have? 
* What can you do with the results? 
* What is useful about this tool and type of analysis? 
* Are the visualizations meaningful? Easy to decipher? Why or why not?
* Compare and contrast tools.
* Does this tool expose problems with your data?

## Resources

* [Introduction to Text Analysis workbook](https://bmw9t.gitbooks.io/introduction-to-text-analysis/content/) by Prof. Brandon Walsh
* [Journal of Cultural Analytics](http://culturalanalytics.org/) - new journal devoted to "the computational study of culture."
* [Intro to Text Analysis guide](http://guides.library.duke.edu/text_analysis) from Duke University Libraries
* [_The Historian's Macroscope_](http://www.themacroscope.org/?page_id=633), starting with the chapter "Basic Text Mining"



