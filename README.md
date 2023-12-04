# Refactor challenge web code for websites accessibility on search engines 


As a marketing agency website, in order that own site is optimized for search engines, I want a codebase with accessibility standards! 
I had an initial HTML and CSS codebase of which, I'm just showing you a few lines here, and it looked like this:
*HTML code: 
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine 

*CSS code: 
.benefit-brand img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}
.benefit-cost img {
     display: block;
                


## Code accessibility development requirements


To develop the code to make it accessible for the search engines I needed to follow certain criteria:
* source code use semantic HTML elements throughout;
* styling and positioning not to influence the logical structure of the code;
* `alt` attributes to be add for images and icons;
* concise and descriptive title to be used for title elements.



### Technical functionality improved by me


* Application's links are functional;
* Application's CSS selectors semantic structure is consolidated;
* Application's HTML and CSS file changes are commented.
 Now I will display some actual line of codes that illustrates some functionality:
 *HTML code:
 <!--Main content of the marketing web page (I changed the div to a semantic element main)-->
    <main class="content ">
        <!--First section(I added an id element to Search Engine Optimization article so it become an in-page functional link, then I changed div to a semantic element)-->
        <section id="search-engine-optimization " class="search-engine-optimization ">
            <img src="./assets/images/search-engine-optimization.jpg " class="float-left " alt="Search engine optimization image." />
            <h2>Search Engine Optimization</h2>
*CSS code:
/*The aside img element has the same  display,
    margin and
    max-width style, so I merged the styling*/

.benefit-lead img,
.benefit-brand img,
.benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}




Licensed under the MIT license.
