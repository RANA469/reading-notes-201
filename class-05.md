# Images must have:
1.Be relevant
2.Convey information
3.Convey the right mood
4.Be instantly recognisable
5.Fit the color palette


## To add an image into the page
1. you need to use an <img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
2. src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
3. alt
This provides a text description
of the image which describes the
image if you cannot see it.
4. title
You can also use the title
attribute with the <img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.


## Height & Width of Images:
+ height
This specifies the height of the
image in pixels.
+ width
This specifies the width of the
image in pixels.
## Where to Place Images in Your Code
1. before a paragraph
The paragraph starts on a new
line after the image.
2. inside the start of a
paragraph
The first row of text aligns with
the bottom of the image.
3. in the middle of a
paragraph
The image is placed between the
words of the paragraph that it
appears in.

# Old Code: Aligning Images Horizontally
align chapter-05/aligning-images-horizontally.html HTML
The align attribute was
commonly used to indicate how
the other parts of a page should
flow around an image
- left
This aligns the image to the left
(allowing text to flow around its
right-hand side).
- right
This aligns the image to the right
(allowing text to flow around its
left-hand side).
# Old Code: Aligning Images Vertically
- top
This aligns the first line of the
surrounding text with the top of
the image.
- middle
This aligns the first line of the
surrounding text with the middle
of the image.
- bottom
This aligns the first line of the
surrounding text with the bottom
of the image.

# Three Rules for Creating Images
1. Save images in the right format
2. Save images at the right size
3. Use the correct resolution

## Image Dimensions
The images you use on your website should be
saved at the same width and height that you
want them to appear on the page.
## Vector Images
Vector images differ from bitmap images and
are resolution-independent. Vector images are
commonly created in programs such as Adobe
Illustrator.
## Animated GIFs
Animated GIFs show several frames of an
image in sequence and therefore can be used to
create simple animations

# Transparenc
1. Transparent GIF:If the transparent part of the
image has straight edges and
it is 100% transparent
2. png:If the transparent part of the
image has diagonal or rounded
edges or if you want a semi

## Examining Images on the Web
## Checking the Size of Images
 This can be
achieved by right-clicking on the image and making a selection from
the pop-up menu that appears

## Downloading Images
you can do so by
accessing the same pop-up menu

## HTML5: Figure and Figure Caption
- HTML5: Figure and
Figure Caption
- <figcaption>
The <figcaption> element has
been added to HTML5 in order
to allow web page authors to add
a caption to an image.

////////////////


## Foreground Color
1. ### color
2. ### rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
3.  ### hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
4. ### color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan

# background-color
1. ### RGB Values
Values for red, green, and blue
are expressed as numbers
between 0 and 255Hex Codes
2. ### Hex values
 represent values
for red, green, and blue in
hexadecimal code.
3. ### Color Names
Colors are represented by
predefined names. However,
they are very limited in number.
4. ### hue 
5. ### saturation
6. ### brightness

## Contrast
When picking foreground and background
colors, it is important to ensure that there is
enough contrast for the text to be legible.

# CSS3: Opacity
## opacity, rgba
CSS3 introduces the opacity
property which allows you to
specify the opacity of an element
and any of its child elements.
The value is a number between
0.0 and 1.0 (so a value of 0.5
is 50% opacity and 0.15 is 15%
opacity)

## CSS3: HSL & HSLA
1. ### hue
This is expressed as an angle
(between 0 and 360 degrees).
2. ### saturation
This is expressed as a
percentage.
3. ### lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
4. ### alpha
This is expressed as a
number between 0 and 1.0.

////////
## Typeface Terminology
1. serif
2. sans-serif
3. monospace

## Weight 
Light
Medium
Bold
Black
## Style
Normal
Italic
Oblique
## Stretch
Condensed
Regular
Extended

# Techniques That Offer a Wider Choiceof Typefaces
1. font-family
2. font-face 
3. Service-based
Font-Face

# Specifying Typefaces font-family
The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.
# Size of Type
font-size: The font-size property enables
you to specify a size for the
font
