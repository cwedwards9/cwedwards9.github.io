# Homework 2: Responsive portfolio
Use Bootstrap to create a mobile responsive portfolio

## A Few Notes:
* I used the HTML boilerplate from the getbootstrap website which gave me boilerplate HTML as well as the Boostrap CSS link and the Bootstrap JS 
* Other than the Boostrap CDNs I have, I also included:
    * A CSS Reset file to take away any browser-specific css styling
    * My own css file, style.css specifically for looks, not layout
    * Google Fonts to give me more options for font styles
    * Font Awesome to give me icons to include in my footer for social media


### Navbar
* I created a navbar that is consistent on all three HTML pages
* I used a pretty basic code example from the Bootstrap site for the navbar
* The changes I made to the navbar included:
    * The navbar background color and the text color
    * I deleted one list item since I only need three
    * I added links to all of the HTML pages
    * I changed the text content to be the names of the pages
    * I added some margin classes to make the navbar items and the navbar itself spaced out better

### Footer
* I created a footer that is consistent on all three HTML pages
* I did not use a reference for this part
* I used the grid system for the three parts in the footer
* Each part was its own column and one part was icons with clickable links to my social media
* It is responsive, any size smaller than medium size pushed the three parts into columns
    * Otherwise they are spaced out with space between them
* I had to manually set the right margin to 0 because for some reason, the margin was pushing the width to be much bigger than needed

### index.html
* This file/page is my main page that is all about me
* All content is using Bootstrap grid system
* All of the content after the navbar except footer is inside of the main tag with a container class
* I included a title and an `<hr>` in the first row/column
* The rest of the content in the main tags are divided in section tags
* Each section tag is a row with two columns nested inside
* The two columns are a paragraph and an image all about me
    * The columns are 5 units each leaving 2 units left for space around the columns
* I have made this page responsive by collapsing the rows into columns when the screen size is less than large size
* I have also changed the order of what elements appear when they stack into columns using the order Bootstrap class

### contact.html
* This file/page mainly contains a mockup for a form that could be used to contact me  
* All content is using Bootstrap grid system
* All content besides the navbar and footer are inside of a main tag with container class
* I included a title and an `<hr>` in the first row/column
* The rest is the form that I created
* The first section is a row with 2 columns that are 4 units each leaving 4 units of space left
    * The two columns are two text/email inputs with labels
    * They are centered in the row
* The next two sections are rows that are both 8 units leaving 4 units of space left
    * These columns are a text input and textarea tag
    * They are also centered within their respective row
* The last section/row nests a button inside of it that is centered

### portfolio.html
* This file/page will be used to show off web development related work I have done in this bootcamp
* Since we have not done a big project yet, I have just included filler images that are responsive
* All content is using Bootstrap grid system
* All sections are in the main tag
* The first section includes the title and an `<hr>`
* The other three sections are rows with two columns
* Screen size large and above displays the three rows and two columns side by side centered in the row
    * The columns take up 4 units each so 8 units altogether with 4 units left of space
* Screen size smaller than large has each column on its own row



