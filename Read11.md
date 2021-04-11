# Read class 11

#Images
> Controlling the size and alignment of
your images using CSS keeps rules that
affect the presentation of your page in
the CSS and out of the HTML markup.

> control the size of an image 
You can control the size of an image using the width and
height properties in CSS, just like you can for any other box.
Specifying image sizes helps pages to load more smoothly
because the HTML and CSS code will often load before the
images, and telling the browser how much space to leave for an
image allows it to render the rest of the page without waiting for the image to download.

>Aligning img
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}

>Centering img
img.align-center {
display: block;
margin: 0px auto;}
img.medium {
width: 250px;
height: 250px;}

>background-image
background-image: url("images/pattern.gif");}

> Repeating img
- repeat
The background image is repeated both horizontally and
vertically (the default way it is shown if the backgroundrepeat property isn't used).
- repeat-x
The image is repeated horizontally only (as shown in
the first example on the left).
- repeat-y
The image is repeated vertically only.
- no-repeat
The image is only shown once. The background-attachment
property specifies whether a background image should stay in
one position or move as the user scrolls up and down the page. 
can have one of two values:
- fixed
The background image stays in the same position on the page.
- scroll
The background image moves up and down as the user scrolls
up and down the page.

background-position:
 - left top
 - left center
 - left bottom
 - center top
 - center center
 - center bottom
 - right top
 - right center
 - right bottom

> CSS3 is going to introduce the ability to specify a gradient for the background of a box. The gradient is created using the
background-image propertyand, at the time of writing,
different browsers required a different syntax.


# Practical Information

>seo
Search engine optimization (orSEO) is the practice of trying
to help your site appear nearer the top of search engine results when people look for the topics that your website covers. At the heart of SEO is the idea of
working out which terms people are likely to enter into a search engine to find your site and then
using these terms in the right places on your site to increase
the chances that search engines will show a link to your site in their results. In order to determine who comes
first in the search results, search
engines do not only look at what appears on your site. They also consider how many sites link to you (and how relevant those links are). For this reason, SEO
is often split into two areas:
- on-page techniques and off-page techniques

1: Page Title
The page title appears at the top of the browser window or on the tab of a browser. It is specified in the <title> element which lives inside the <head> element.
2: URL / Web Address
The name of the file is part of the URL. Where possible, use
keywords in the file name.
3: Headings
If the keywords are in a heading <hn> element then a search
engine will know that this page is all about that subject and give it greater weight than other text.
4: Text
Where possible, it helps to repeat the keywords in the main
body of the text at least 2-3 times. Do not, however, over-use
these terms, because the text must be easy for a human to read.
5: Link Text
Use keywords in the text that create links between pages
(rather than using generic expressions such as "click here").
6: Image Alt Text
Search engines rely on you providing accurate descriptions
of images in the alt text. This will also help your images show
up in the results of image-based searches.
7: Page Descriptions
The description also lives inside the <head> element and is
specified using a <meta> tag. It should be a sentence that
describes the content of the page. (These are not shown in
the browser window but they may be displayed in the results
pages of search engines.)

> Analytics: Learning about your Visitors
As soon as people start coming to your site, you can start analyzing how they found it, what they were looking at and at what point they are leaving. One of the best tools for doing this is a free service offered by Google called Google Analytics

> DOMAIN NAMES WEB HOSTING
Your domain name is your web address (e.g. google.com or bbc.
co.uk). There are many websites that allow you to register domain names. Usually you will have to
pay an annual fee to keep that domain name.
These sites usually have a form that allows you to check whether your preferred domain name is
available, and because millions of domain names have already
been registered, it might take you a while to find the one that is right for your site.
A lot of sites that offer domain name registration also offer web hosting.