## Alexander's Portfolio Site for Coursera's HTML and CSS In Depth Course
If you're looking at this to peer review, or are just a curious sort, these are few things I wanted to list here to mention a few points of how I decided to do all this:

- I did not feel CSS animations were necessary and would be distracting in most amounts. That said, I did use pseudo classes to change text color on hover of the nav links for a small effect I felt was not distracting.

- I included @media breakpoints for a little extra challenge, an attempt at making the design viewable on both mobile like views and desktop as well. Due to mobile view, you won't see the pseudo class text color change I did in this view.

- I wrapped the main logo, the one in the header, in an anchor tag, as usually company sites use their main logo as a home link as well. None of the links go anywhere as its a fictional client, but nice to have.




## The below is just my copy paste of Coursera's instructions for the project + grading for refernce for myself, though whoever is reading this could use it too

## Requirements for this webpage:

The web page should have the company logo at the top of the page ​with a navigation menu underneath. ​The main content of the page should be below the navigation menu. 

At the bottom of the page is the footer. ​The navigation menu requires four links to be laid out horizontally. ​One link must be to the homepage you are developing ​depending on the client persona you've chosen. ​The other links can be to product pages, contact forms or ​company information pages. ​The main content should feature a large banner that links to the client's current ​promotional offer below the promotional banner. ​There are three columns. ​Each column should contain an image followed by a heading and some text. 

Again, depending on the client you choose. ​These can contain offerings or information about the client. ​The footer is split into two columns. ​The left column will contain a small version of the client logo and ​the right column will contain copyright text. ​Now that you know what the visual requirements are. ​Let's examine how you can structure the html and CSS for this layout. ​Remember that it's important to semantically structure your html document. 

So search engines and ​accessibility software can understand the semantics of the web page. ​So it's best to start by planning out the semantic structure. ​You should use the header element for the logo, the nav element for ​the navigation, the main element for the main content and ​the footer element for the footer of the page. ​Once you've set up your semantic html structure, ​the next step is to plan your grid layout for the main content and footer for ​these parts of the web page, you can use either a CSS grid or a flex box layout. ​It's important to plan your CSS rules for ​the different sized columns that are required. ​Remember, you'll need a full with column and 3 3rd width columns for the main content to simplify the main content. 

Consider splitting the content into two rows then to half with columns for ​the footer. ​One last note, it's important to plan your units of measurement ​when defining your CSS rules and properties. ​It will be easier to maintain and ​debug your CSS if your units are consistent throughout the code as you ​learned earlier in the course, choosing a unit such as M or rem for your C. ​S. S. At the beginning of the project and ​sticking to it will help you as you progress further. ​And that's the end of this video about planning a web page. 


## When you submit your assignment, other learners in the course will review and grade your work. They will be looking for the following:

Visual layout

When viewing the home page in the browser:

- Is it clear that this is a home page for one of the four fictional clients?

- Is the correct company logo at the top of the page?

- Is there a horizontal navigation menu with four links below the logo?

- Does one of the links in the navigation menu link to the home page itself?

- Does the main content contain a large promotional banner at the top and three columns below it, each containing an image and some text?

- Does the page have a footer that is split into two columns?

- Does the left column of the footer contain a small version of the client logo and the right column copyright text?

Semantic structure

When opening the HTML file in VS Code, does it contain:

- A header element for the logo?

- A nav element for the navigation menu?

- A main element for the content?

- A footer element for the footer?

- Appropriate usage of other semantic tags such as article and section in the content of the main element?

  

CSS layout, styling and effects

When viewing the home page in the browser:

- Is the use of CSS styling effective?

- Is CSS used to create appropriate interactivity?

When opening the CSS file in VS code, ask yourself the following:

- Is it a grid or flexbox layout?

- Does it have the appropriate selectors to style elements?

- Does it specify any pseudo-classes to create interactivity on the home page?

- Are any animations or transition effects used? Do they improve the user experience or distract from it?

Overall effect of the home page

- Does the home page create adequate interaction and a pleasing visual experience that is fitting for the client and its customers? 

- Are CSS styling and effects used effectively to create intentional engagement? 

- What works well? 

- What advice can you give to improve the user experience, layout and visuals of the home page?

- You'll also need to give feedback on and grade the assignments of two other learners using the same criteria.