0. Structure
 Create the most basic, simple and valid HTML file called base_index.html

The page should contain:

a DOCTYPE
a head:
with a title
a body
Tips: don’t forget to read all concept pages…

Test the webpage with the official HTML Validator. You will see that it is not happy!

First things first, fix the code in base_index.html so that it is valid.

You will see that the validator then becomes much happier!
1. Make a cool first webpage
 Copy your file base_index.html to index.html

Add in the body of the page:

at least 4 paragraphs;
headings (titles) of level 1, 2 and 3, which are represented 
2. Make a cool other webpage
 Copy your file base_index.html to tweets.html

Add in the body of the page:

embed at least one tweet (Here’s the official documentation from Twitter about embedding single tweets in a webpage’s HTML code.)
contain a link to your index.html webpage, for users who may go back to your homepage
In index.html, add a link to tweets.html, for users landing on your homepage, who want to see your tweets!
3. Make a cool website
 However, in order to start getting consistency throughout the website, all of the HTML files (index.html and tweets.html) must now have the same structure:

The <body> tag of all of your webpages must contain exactly three direct sub-tags in that order: <header>, <main> and <footer>
The <header> tag must contain an unordered list (the <ul> and <li> tags) of links (the <a> tag) to each of your webpages. As you may have understood, this will serve as a navigation for your website.
The <footer> tag must contain one paragraph with the sentence Made by <YOUR NAME> - <a href="<ANY LINK>" target="_blank">here</a>.
The <main> tag must contain two direct sub-tags in that order: <article> and <aside>:
<article> contains the content of your webpage: texts, links, images, tweets, … This is the part of index.html and tweets.html that you have already written.
<aside> contains a single paragraph, just reading for now “placeholder to add comment thread later”.
4. Add some level of creativity
Update your index.html to add a table with information about some of the learners.

On a new line after the last </aside> tag, introduce an <article> element which will serve as a container for the table of learners.

The <article> tag should contain a table <table> with the following structure:

Use the <thead> tag to define the table header row.
Use the <tbody> tag to contain the table data rows.
Populate the table with the following data:

Name	Age	Country
John	25	USA
Emily	28	Canada
Michael	32	Australia
Sophia	21	UK

