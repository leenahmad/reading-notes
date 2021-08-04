# Images 

HTML img tag is used to display image on the web page. HTML img tag is an empty tag that contains attributes only, closing tags are not used in HTML image element.

## Attributes of HTML img tag
The src and alt are important attributes of HTML img tag.

1. src
It is a necessary attribute that describes the source or path of the image. It instructs the browser where to look for the image on the server.

The location of image may be on the same directory or another server.

2. alt
The alt attribute defines an alternate text for the image, if it can't be displayed. The value of the alt attribute describe the image in words. The alt attribute is considered good for SEO prospective.

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFGlBkZAOtq_H1_Vt9HyvSqXLeM8eVzC4u0A&usqp=CAU)

3. title
You can also use the title
attribute with the `<img>` element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.
![img](https://codetheweb.blog/assets/img/posts/html-syntax/tag-structure-2.png)

4. width
It is an optional attribute which is used to specify the width to display the image. It is not recommended now. You should apply CSS in place of width attribute.

5. height
It h3 the height of the image. The HTML height attribute also supports iframe, image and object elements. It is not recommended now. You should apply CSS in place of height attribute.

![img](https://www.wikihow.com/images/thumb/0/00/Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg/v4-460px-Set-Image-Width-and-Height-Using-HTML-Step-2-Version-3.jpg.webp)


## Where to Place Images in Your Code

Where an image is placed
in the code will affect how it
is displayed. Here are three
examples of image placement
that produce different results:
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

## Summary IMAGES
- The <img> element is used to add images to a
web page.
* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
- You should save images at the size you will be using
them on the web page and in the appropriate format.
* Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.


# CSS Color
The color CSS property sets the foreground color value of an element's text and text decorations, and sets the `<currentcolor>` value. currentcolor may be used as an indirect value on other properties and is the default for other color properties, such as border-color.



## Syntax

/* Keyword values */

color: currentcolor;

/* `<named-color>` values */

color: red;

color: orange;

color: tan;

color: rebeccapurple;

/* `<hex-color>` values */

color: #090;

color: #009900;

color: #090a;

color: #009900aa;

/* `<rgb()>` values */

color: rgb(34, 12, 64, 0.6);

color: rgba(34, 12, 64, 0.6);

color: rgb(34 12 64 / 0.6);

color: rgba(34 12 64 / 0.3);

color: rgb(34.0 12 64 / 60%);

color: rgba(34.6 12 64 / 30%);

/* `<hsl()>` values */

color: hsl(30, 100%, 50%, 0.6);

color: hsla(30, 100%, 50%, 0.6);

color: hsl(30 100% 50% / 0.6);

color: hsla(30 100% 50% / 0.6);

color: hsl(30.0 100% 50% / 60%);

color: hsla(30.2 100% 50% / 60%);

/* Global values */

color: inherit;

color: initial;

color: revert;

color: unset;

## Background Color

The CSS background-color property defines the background color of an element.

## Syntax

background-color: value;


- #RRGGBB : Hexadecimal representation of the background color
div { background-color: #FF0000; }
* rgb()	RGB representation of the background color
div { background-color: rgb(255,0,0); }
* color name : Name of the background color (ie: red, blue, black, white)
div { background-color: red; }
- transparent : Indicates that the element shows the background-color of the element behind it.
The default value for CSS background-color is transparent.
div { background-color: transparent; }

- inherit : Element will inherit the background-color from its parent element
div { background-color: inherit; }

## Summary COLOR
* Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
- There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
* Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
--------------------------------------------------
# Text

![img](https://www.shillingtoneducation.com/content-blog/uploads/2019/09/Typography_Anatomy.jpg)

[You can read more about Text here](https://www.w3.org/TR/REC-html40-971218/present/graphics.html)
## Summary TEXT
- There are properties to control the choice of font, size,
weight, style, and spacing.
* There is a limited choice of fonts that you can assume
most people will have installed.
- If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
* You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
- You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.
]

# JPEG vs PNG vs GIF

## *JPEG*

JPEG stands for Joint Photographic Experts Group, which is the name of the organisation that developed the image format. When you save an image as a JPEG, some data from the image will be lost and deleted forever to reduce the size of the file.

JPEG is designed to compress photographs that use natural colours and light. It does not work well with line drawings of shapes, or text. Saving these kinds of graphics in JPEG often results in pixellation around the edges – when an image becomes blurry and you can see individual pixels. It’s also not a great idea to edit and save files as JPEGs several times over, because the quality of the image will be reduced each time you save.

Use JPEG if you want to make your photos small enough to share easily over the internet, but still retain fairly high image quality.

## *PNG*

Portable Network Graphics (PNG) are different from JPEGs because they use “lossless compression”. This means a PNG can be compressed to a smaller file size without losing any of the detail in the image. This makes PNG a good option for saving graphics – such as logos, shapes, screenshots, illustrations, and text – that you want to share over the internet, or use in presentations.

These types of graphics won’t be as pixellated in PNG form as they would be as a JPEG. You can also share, edit, and save PNG files many times without losing any of the image quality. Unlike JPEGs, PNG files also support transparency, making this the format if you want part of your image, such as the background, to be transparent.

## *GIF*
The Graphics Interchange Format (GIF) is the predecessor (something that came before another thing) to the PNG, and they both use a similar type of lossless compression.

The GIF was designed more than 30 years ago, when internet speeds were slow, and images needed to be a lot smaller to be shared easily over the web. As a result, images saved as GIFs are limited to just 256 colours, compared to around16 million possible colours in a JPEG image. This gives GIFs a grainy look full of unrealistic colours.

You probably know GIFs for their ability to animate, but originally GIFs were only static images. The animation function was added several years later.

---------------------------------------------------------- 

[You can read more about JPEG vs PNG vs GIF](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d) 
