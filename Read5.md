# Read Class 5 
# Images
There are several things to consider when selecting and preparing images for your site, but taking time to get them right will make it look more attractive and professional.
In this chapter you will learn how to:
- Include an image in your web pages using HTML
- Pick which image format to use
- Show an image at the right size
- Optimize an image for use on the web to make pages load faste

**Choosing Images for Your Site**
A picture can say a thousand words, and great
images help make the difference between an
average-looking site and a really engaging one.

 **Storing Images on Your Site**
Its prefer to store Images in same project in file

*Img Tag*
<img>To add an image into the page you need to use an <img>
element. This is an empty element (which means there is
no closing tag). It must carry the following two attributes:
- src
This tells the browser where it can find the image file. This
will usually be a relative URL pointing to an image on your
own site. (Here you can see that the images are in a child folder
called images — relative URLs were covered on pages 83-84).
- alt
This provides a text description of the image which describes the
image if you cannot see it.
- title
You can also use the title attribute with the <img> element
to provide additional information about the image. Most browsers
will display the content of this attribute in a tootip when the
user hovers over the image.

**Height & Width of Images** 
- height
This specifies the height of the image in pixels.
- width
This specifies the width of the image in pixels.
Images often take longer to load than the HTML code that
makes up the rest of the page. It is, therefore, a good idea to
specify the size of the image so that the browser can render
the rest of the text on the page while leaving the right amount of space for 
Where an image is placed in the code will affect how it
is displayed. Here are three examples of image placement
that produce different results:
- before a paragraph
The paragraph starts on a new
line after the image.
- inside the start of a
paragraph
The first row of text aligns with
the bottom of the image.
- in the middle of a
paragraph
The image is placed between the
words of the paragraph that it
appears in
Block elements always appear
on a new line. Examples of block
elements include the head & elements.
align chapter-05/aligning-images-horizontally.html HTML
The align attribute was commonly used to indicate how
the other parts of a page should flow around an image. It has
been removed from HTML5 and new websites should use
CSS to control the alignment of images.

#### Rules of images
- Save images in the right format
- Save images at the right size
- Use the correct resolution

*Tools to Edit & Save Images*
-Adobe
-Photoshop.

*Image Dimensions*
The images you use on your website should be
saved at the same width and height that you
want them to appear on the page

*Cropping Images*
When cropping images it is important not to
lose valuable information. It is best to source
images that are the correct shape if possible.

*Image Resolution*
Images created for the web should be saved at
a resolution of 72 ppi. The higher the resolution
of the image, the larger the size of the file

*Vector Images*
Vector images differ from bitmap images and
are resolution-independent. Vector images are
commonly created in programs such as Adobe Illustrator

*Animated GIFs*
Animated GIFs show several frames of an
image in sequence and therefore can be used to
create simple animations.

# color
- RGB values
- HEX codes
- color names

*CSS3: HSL Colors*
CSS3 introduces an entirely new and intuitive
way to specify colors using hue, saturation,
and lightness values.
*CSS3: HSL & HSLA*
hsl, hsla
The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for:
- hue
This is expressed as an angle
(between 0 and 360 degrees).
- saturation
This is expressed as a
percentage.
- lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100% being black.
- alpha
This is expressed as a
number between 0 and 1.0.
For example, 0.5 represents
50% transparency, and 0.75
represents 75% transparency

### Text
*weight*
- Light
- Medium
- Bold
- Black

*Style*
- Normal
- Italic
- Oblique

*Stretch*
- Condensed
- Regular
- Extended

*Techniques That Offer*
a Wider Choice of
Typefaces
There are several ways to use fonts other than those listed on the
previous page. However, typefaces are subject to copyright, so the
techniques you can choose from are limited by their respective licenses.

- font-family
The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.
- font-size
The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font. 

- @font-face allows you to use
a font, even if it is not installed
on the computer of the person
browsing, by allowing you to
specify a path to a copy of the
font, which will be downloaded if
it is not on the user's machine.

*Font Format:*
Different browsers support different formats for fonts
(in the same way that they support different audio and
video formats), so you will need to supply the font in several
variations to reach all browsers

font-weight:
- normal This causes text to appear at a
normal weight.
- Bold : This causes text to appear bold.

* text-transform
- uppercase
This causes the text to appear
uppercase.
- lowercase
This causes the text to appear
lowercase.
- capitalize
This causes the first letter of
each word to appear capitalized

- text-decoration:
none
This removes any decoration
already applied to the text.
underline
This adds a line underneath the
text.
overline
This adds a line over the top of
the text.
line-through
This adds a line through words.
blink
This animates the text to make it
flash on and off (however this is
generally frowned upon, as it is
considered rather annoying).

*text-align*
- left
This indicates that the text
should be left-aligned.
- right
This indicates that the text
should be right-aligned.
- center
This allows you to center text.
- justify
This indicates that every line in
a paragraph, except the last line,
should be set to take up the full
width of the containing box.

*JPEG vs PNG vs GIF — which image format to use and when?*

*Animation:*
- only GIF supports animation.
*Colours:*
- GIF images are limited to 256 colours.
- PNG images mainly have two modes.
- JPEG images can support around 16 million colours

*Transparency*
- JPEG images don’t support transparency and are hence not usable for such cases.
- PNG images support transparency in two ways 
- GIF images support transparency by declaring a single colour in the colour palette as transparent 