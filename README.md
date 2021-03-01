# Code Refactor

For this homework assignment, I am tasked with refactoring a html file and a CSS file for an existing website. 

<h2>The following list is the acceptance criteria:</h2>

    * GIVEN a webpage meets accessibility standards
    * WHEN I view the source code
    * THEN I find semantic HTML elements
    * WHEN I view the structure of the HTML elements
    * THEN I find that the elements follow a logical structure independent of styling and positioning
    * WHEN I view the image elements
    * THEN I find accessible alt attributes
    * WHEN I view the heading attributes
    * THEN they fall in sequential order
    * WHEN I view the title element
    * THEN I find a concise, descriptive title
<br>
    
<h2>The following is a mock up page of how the website site should look like.</h2>     
    
<img src="https://github.com/vickphat/homework1/blob/main/mockup.png">

<br>    
<br>

<h2>Changes</h2>

<br>
The following will be a list of the changes I did to the html file:

    * Inside the html file, the code was not in semantic order. The element "div" was used for every section. 
    I changed those div and gave the html file a "header", "main", "aside" and "footer". 
    
    * In the "head" section, I changed the title from "website" to "Horiseon". 
    
    * In the body, I removed the class "header".
    
    * Indicated that the class "hero", is the background image for the website. 
    
    * Under main, I added id="search-engine-optimization" to fix broken link.
    
    * I added img alt attributes for all img tags.

    * Deleted classes of "search-engine-optimization", "online-reputation-management", and "social-media-marketing" and replaced it with "content-style".

    * Deleted classes of "benefit-brand", "benefit-cost", and "benefit-lead" and replaced it with "benefit-style". 
    
<br>
The following will be a list of the changes I did to the CSS file:

    * Added comments to the CSS file to detail what each class does.
    
    * Put the file into semantic order.

    * Changed header from a class to a element selector.
    
    * Added new class called "content-style"

    * Removed classes "search-engine-optimization", "online-reputation-management", and "social-media-marketing" and replaced it with "content-style".
    
    * Added new class called "benefit-style"
    
    * Removed classes "benefit-brand", "benefit-cost", and "benefit-lead" and replaced it with "benefit-style". 
    
    * Consolidated codes to remove unnecessary code and lower the amount of space being used.  
    
<br>

This is the URL of the deployed application  - https://vickphat.github.io/homework1/
