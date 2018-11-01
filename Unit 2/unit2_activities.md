# Unit 2 / Activities

## Activity 1: Design a network!

In order to practice using the terminology and methods of network analysis, let's design a network from scratch. Consult [Network Analysis Fundamentals](http://www.themacroscope.org/?page_id=892) for some help with terminology.  
1. In your group, select a topic for your network. It should be approachable for all members of your group. Game of Thrones? W&L students? Sports? A novel or TV show?  
2. List all the nodes in your network. Do they have types? Do they have attributes? Is this a biomodal or multimodal network?  
3. Start making connections or edges in your network. What type of edges do you need? Do the edges have a weight?  
4. Think about centrality. Do you have an ego network? How might you start calculating centrality?

## Activity 2: Special Collections Scavenger Hunt

1. Form teams of 4-5. 
2. Create a Box note in Unit 2 / Scavenger Hunt for your team. List your names at the top. 
3. In Special Collections, groups will rotate through each collection. You should answer questions by reviewing the material and asking Special Collections staff. 
4. For each collection, you'll want to consider: "where is the network here?" 
5. For your bonus participation point, visit the Stonewall Jackson Cemetery and add a photo to your Box note. 


## Activity 3: Open Graph protocol

In this activity, you will semantically enrich your website using Facebook's [Open Graph Protocol](http://ogp.me/). As the site says, Open Graph Protocol "enables any web page to become a rich object in a social graph." When you paste a link into Facebook or Twitter and an image and title show up nicely formatted, this is why.  
1. Create a new HTML page or find one of your HTML pages from the first week in class.  
2. Create a new directory called "Unit2" in your domain. \(Hint, go to File Manager\).  
3. Upload your HTML file to this new directory. Copy the URL of this HTML page. Ex. www.mackenziekbrooks.info/unit2/index.html.  
4. Visit the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/sharing/) and paste in the URL. What do you see?  
5. So let's add some metadata! Visit [http://ogp.me/](http://ogp.me/) and add the basic metadata fields as listed to your HTML file.  
6. Upload this file to your website, then paste the URL into the Debugger again. What do you see now?

## Activity 4: Data Assessment

Using Open Refine, explore your data set. In a text file to be turned in with Unit 2 Data, answer the following:  
1. What do the "Text Facet" or "Numeric Facet" features reveal about your data? Are there outliers that need investigation?  
2. Are there columns that should be split or joined? How would you do this in Open Refine \(or Excel?\)  
3. What columns would be best served by the "cluster and edit" feature? Why?  
4. Which columns need to be modified for consistency? \(hint: any date field\)  
5. Is there research you need to conduct to learn about the people in your data? How will you go about it?

## Activity 5: Data Generation

* Fill this out [data generation survey](https://goo.gl/forms/UeQlebJxdqGu7baP2) to create a simple data set for testing network analysis tools. 
* Data is available as .csv on Box. 
* Using Open Refine, create an edge list. 
  * Remove the timestamp column.
  * From the first column after the names, select ```Transpose > Transpose cells across columns into rows```.
  * Select the ```one column``` option and title your new column ```Value```. 
  * Check the box for ```Fill down in other columns```.
  * Press ```Transpose```. You should end up with two columns where each person's name is listed multiple times, corresponding with their answer to each survey question.
* Extract your new edge list as .csv to download.
* Load data into your chosen app for testing.

## Activity 6: Network Tools
In small groups by operating system, download or open the following network visualization/analysis tools. Use our new survey edge list to demo these platforms. 

1. Palladio
2. Cytoscape
3. Gephi 
4. UCInet (Windows)

Answer the following: 
1. What do you think of the results? What's surprising? What's not?
2. How about the tool itself? What options do you have?
3. What can you do with the results?
4. What is useful about this tool and type of analysis?
5. Are the visualizations meaningful? Easy to decipher? Why or why not?
6. Compare and contrast tools.
7. Does this tool expose problems with your data? 


## Activity 7: Set Your Intentions

* What is my research question or topic?
* What are the biggest problems I have found with the data? What are realistic solutions?
* What methods/tools am I interested in using?
* What resources do I need?
* What are my next steps? Break them down!

## Activity 8: Peer Review

### Visualization

* Individually, spend some time on [HelpMeViz](http://helpmeviz.com) and [Part 4 of Data + Design](https://infoactive.co/data-design/part04.html). Make a list of the common problems and solutions that both sites present. 
* Share your findings with your group. What did you find in common? Any differences? Do you agree with all the recommendations? 
* Pair up and review your classmate's visualization. 
* Share 1 positive + 1 needs improvement, based on the recommendations from the reading. 


### Documentation

* Switch partners and check out your classmate's documentation page. Follow their documentation to produce the same result.
* Take notes on what worked and what didn't work. 
* Share 1 positive aspect + 1 needs improvement aspect with your partner. 




