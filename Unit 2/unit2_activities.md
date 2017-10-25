# Unit 2 / Activities

## Activity 1: Design a network!
In order to practice using the terminology and methods of network analysis, let's design a network from scratch. Consult [Network Analysis Fundamentals](http://www.themacroscope.org/?page_id=892) for some help with terminology.
1. At your table, select a topic for your network. It should be approachable for all members of your group. Game of Thrones? W&L students? Sports? A novel or TV show? 
2. List all the nodes in your network. Do they have types? Do they have attributes? Is this a biomodal or multimodal network?
3. Start making connections or edges in your network. What type of edges do you need? Do the edges have a weight? 
4. Think about centrality. Do you have an ego network? How might you start calculating centrality? 

## Activity 2: Open Graph protocol
In this activity, you will semantically enrich your website using Facebook's [Open Graph Protocol](http://ogp.me/). As the site says, Open Graph Protocol "enables any web page to become a rich object in a social graph." When you paste a link into Facebook or Twitter and an image and title show up nicely formatted, this is why.
1. Create a new HTML page or find one of your HTML pages from the first week in class. 
2. Create a new directory called "Unit2" in your domain. (Hint, go to File Manager).
3. Upload your HTML file to this new directory. Copy the URL of this HTML page. Ex. www.mackenziekbrooks.info/unit2/index.html.
4. Visit the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/sharing/) and paste in the URL. What do you see?
5. So let's add some metadata! Visit [http://ogp.me/](http://ogp.me/) and add the basic metadata fields as listed to your HTML file. 
6. Upload this file to your website, then paste the URL into the Debugger again. What do you see now?

## Activity 3: Data Assessment
Using Open Refine, explore your data set. In a text file to be turned in with Unit 2 Data, answer the following:
1. What do the "Text Facet" or "Numeric Facet" features reveal about your data? Are there outliers that need investigation?
2. Are there columns that should be split or joined? How would you do this in Open Refine (or Excel?) 
3. What columns would be best served by the "cluster and edit" feature? Why?
4. Which columns need to be modified for consistency? (hint: any date field)
5. Is there research you need to conduct to learn about the people in your data? How will you go about it? 

## Activity 4: Data Generation
* Fill this out [data generation survey](https://docs.google.com/forms/d/e/1FAIpQLSeSBKxh-rv1W8z8vPLdeurrtrN6QAt3QkhXY8plkB4lzAMHOw/viewform?c=0&w=1) to create a simple data set for testing network analysis tools. 
* Follow Miriam Posner's [tutorial](http://miriamposner.com/blog/a-fun-way-to-introduce-dh-students-to-dataviz/) to convert data to two columns. 
* Data is available as .csv on Box. 
* Load data into your chosen app for testing.


## Activity 5: Set Your Intentions
* What is my research question or topic?
* What are the biggest problems I have found with the data? What are realistic solutions?
* What methods/tools am I interested in using?
* What resources do I need?
* What are my next steps? Break them down!

## Activity 6: Documentation 
What makes good documentation? As *Data + Design* [reminds](https://infoactive.co/data-design/ch08.html) us: 
> "Regardless of how you choose to do it, good documentation of your cleaning procedures ensures that you can always justify why certain data points were removed and others weren’t and that others are able to verify that the data were cleaned competently and correctly."

### Part 1
* At your table, brainstorm a list of the qualities of good documentation.
* For each quality, find an example from the projects and tutorials we've used so far in the course. 
* Share your results with the group. 

### Qualities
* Don't assume previous knowledge of the subject. 
* Clarity
* Thorough - detailed, easy to understand, don't skip steps
* Simple, easy to follow, step by step
  * Bullet points rather than paragraphs
* Cover all methods for your project 
* Document as you go along, rather than at the end
* Keep track of what doesn't work - helpful to you and others
* Visual aesthetic (not WebAdvisor)
* Troubleshooting section - problems encountered
* ```Show your code``` 
* Plain text when possible 
* Screenshots! 
* Linking to other tutorials when applicable
* Third person, declarative sentences. 

### Part 2
* Using your new list of principles, document one of your methods from this unit. It can be something you learned to do in Excel or Open Refine or one of the visualization tools.
* Post this documentation to your website by Thursday's class. 

## Activity 7: Excel tips
* To open CSV file > Get External Data > From Text > Choose your delimiter
* To combine cells > =(A2&" "&B2)
* To fill in whole column, drag down the bottom right corner of the first cell.
* Copy columns with formulas and paste special as "value" to preserve actual data.
* Keyboard shortcuts! Alt + __ to save time on commands.
* Filter and sort.
  * Check "expand selection" to sort all the rows in your spreadsheet.
  * Use the filter option to show or hide certain data in your columns.
* To format dates according to ISO standard, change column type to "Custom," then add in yyyy-mm-dd to the "type field."

## Activity 8: Peer Review
### Documentation
* You will receive the link to another classmate's documentation page. Follow their documentation to produce the same result.
* Take notes on what worked and what didn't work. 
* Share 1 positive aspect + 1 needs improvement aspect with your partner. 
* Reference the comments from your peer reviewer in the Documentation assignment for Unit 2.

### Visualization
* Spend some time on [HelpMeViz](http://helpmeviz.com) and [Part 4 of Data + Design](https://infoactive.co/data-design/part04.html). Take note of the problems and solutions that both sites present. 
* Review your classmate's visualization. 
* Share 1 positive + 1 needs improvement.
* Reference the comments from your peer reviewer in the Documentation assignment for Unit 2.

