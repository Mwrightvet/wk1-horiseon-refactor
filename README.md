# wk1-horiseon-refactor
Refactoring of the Horiseon website to meet accessibility standards for good SEO standards

#User Story 
02-Challenge (Week 1) - As a margeting agency, website follows accessibility standars for Search Engine Optimization (SEO). 

#Acceptance Criteria 
1. Ensure the source code contains semantic elements.
2. Ensure the semtantic elements follow a logical structure something along the lines of the example below. 
```
<title>
<header>
<nav>
<section>
<h> header tags should be logical
<p> paragraph markings
<footer>
``` 

3. Ensure Incons and Image elemnets contain proper alt tags for accessibility purposes using the example below. 
   ```<img src="cost-management.png" alt="Cog wheel with dollar symbols"```

4. Ensure the heading attributes follow a sequential order.
  ``` h1, h2, h3, h4, etc.```
5. Ensure the title element has a concise and descriptive title. 

6. List of Edits made:
   - followed the site "https://www.w3schools.com/html/html5_semantic_elements.asp" for semantic guidelines
   - changed the title to match website content
   - change the div class that contained a header class to it's own header semantic
   - changed the div class that contained the navigation items to the semantic html for navigation since it's used for navigating the site
   - changing the navigation caused some weird behavior (added bullets) even though I specifically said not to for the unstructured list, so I had to be creative in adjusting the background
   - changed the background color to have a seamless transition between the h1 class and the navigation since it was trying to separate them. **This by far was the most time consuming section
   - added single quotes around some of the font-families that were getting irnored
   - added the id to the search engine optimization section to fix the navigation since it was broken
   - moved the image from the css and into the html so that I coul use the image alt tags
   - added the classes to the hero section where I moved the image
   - added alt tags to all of the images 
   - changed the separate sections that were only separated by divs using the section semantic
   - moved the div that was on the right side of the page into the HTML aside semantic
   - removed some weird spacing issues in the paragraphs 
   - changed the div that used a footer class to using it's own footer semantic
  
   - If I had more time what would I have done:
   -    figured out how to fix the navigation better so that I didn't have to change the background so much
   -    cleaned up the redundant section image sizes
   -    cleaned up the redudndant section styling for all of the h2s
   -    cleaned up the redundant section styling for all of the h3
   -    overall clean up the style page to reduce some redundancies 
