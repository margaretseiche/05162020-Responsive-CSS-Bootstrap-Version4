# Homework2

# Unit 02 CSS and Bootstrap Homework: Responsive Portfolio

* I started by creating `index.html`, `portfolio.html` and `contact.html`.  

* Next I added all of the links for style sheets: reset, Bootstrap, Bootstrap jQuery, Google Fonts and style (my CSS file).

* Then I used the last homework as a framework for the header, with h1 on the left and Bootstrap navigation on the right.  This is the same for all 3 pages, just changing which one is the active link.  I set some parameters in a media query when the screen moved below 840px (when the nav bar would collapse to the second line).  1) I pushed the margin-top down for main so that the header would not block main content. 2) Then I centered the h1 and navigation. 

* I set 'main' as the group and used a 'container-fluid' from Bootstrap for each page.  I used rows and called some 'articleHeading' and others 'features' to set CSS.

* For index, I wanted 3 portions that I called articles.  I had one row at the top for the heading and applied CSS to differentiate it from the rest of the article.  Then for the next rows (which I called 'feature' so that I could apply CSS consistently), I split into columns.  I added a few photos using float-left.  For the text on the other side of the pictures, I enclosed them in their own <div> elements so that they would stick together (as before the second <p> would pop to the next line).  

* In several cases, I called a group of items "id"; the HTML validation service warned that these were duplicates (and presumably that they should be classes).  I left them as is because we were warned by the TAs about keeping them separate from the multiple classes assigned by Bootstrap.

* For the portfolio page, I started the same way, with 'rowHeading' to apply CSS to the top row.  For the next part, I put 1 row with 4 columns.  In each column, I used Bootstrap cards to show a few different examples of prior work.  
 - I used one with an image and 2 button links (one to a pdf file and then a website), 
 - one column card with a video,
 - another with an image Bootstrap carousel and a button linked to a pdf,
 - and the last one with an image and 3 button links to websites.  
 When I collapsing, because I had 4 columns, I decided to move to 2x2 when the screen was too small for all four.  To do this, I used min-width.

* On the contact page, I had social media icons set in columns so that they would collapse.  For the most part, this worked.  It became a problem at the smaller screen size 576px.  I experimented but did not solve the problem.  On the lower portion, I used another article to create a portion for people to send an email (though not a real functioning section) which I set to resize. 

* I added some media queries with changing CSS conditions based on trial-and-error to fit as the screen size changed.

* I wanted to add hanging indents so that on collapsing, second lines would align (not go in front for instance in a list item), but I couldn't figure it out.

* I did not use a sticky footer.  (I would find it a little strange and worry that people wouldn't notice that they needed to scroll down, thinking that the stuck footer was the end of the content.)  Instead, I created a fixed top, so that my name and navigation menu would stay on the browser top regardless of how far down someone scrolled.