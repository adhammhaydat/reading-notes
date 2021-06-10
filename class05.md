# Images, Color, Text

1. Chapter 5: “Images” 
2. Chapter 11: “Color” 
3. Chapter 12: “Text” 

------------------------------## Chapter 5: “Images” (pp.94-125)

`There are many reasons why you might 
want to add an image to a web page: you 
might want to include a logo, photograph, 
illustration, diagram, or chart.`

**Choosing Images for Your Site**

`A picture can say a thousand words, and great 
images help make the difference between an 
average-looking site and a really engaging one.`

**Images should...Be relevant**

1. Convey information
2. Convey the right mood 
3. Be instantly recognisable 
4. Fit the color palette

**Stock photos**

1. www.istockphoto.com
2. www.gettyimages.com
3. www.veer.com
4. www.sxc.hu
5. www.fotolia.com

**Online extra**

* by capying image address 

**Storing Images on Your Site**

`f you are building a site from scratch, it is good 
practice to create a folder for all of the images 
the site uses.`

**Adding Images**

To add an image into the page 
you need to use an `<img>`
element. This is an empty 
element (which means there is 
no closing tag). and insaide this tage it should have src="path of image", and title.

we can add css tyle to image by using defirant attrebute like width, height and postion.

**HTML5: Figure and Figure Caption**

mages often come with 
captions. HTML5 has introduced 
a new `<figure>` element to 
contain images and their caption 
so that the two are associated. 
You can have more than one 
image inside the `<figure>`
element as long as they all share 
the same caption

The `<figcaption></figcaption>` element has been added to HTML5 in order to allow web page authors to add a caption to an image.

-------------------------------

## Chapter 11: “Color”

Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.

**CSS Color Names**

In CSS, a color can be specified by using a predefined color name:

![colors](https://i.pinimg.com/originals/ad/07/fa/ad07fab27cc455481593fe3704cdd800.png)

**CSS RGB Colors**

In CSS, a color can be specified as an RGB value, using this formula:
`rgb(red, green, blue)`

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

example: `rgb(255, 99, 71)`

**CSS HEX Colors**

A hexadecimal color is specified with: `#RRGGBB`, where the `RR (red), GG (green) and BB (blue)` hexadecimal integers specify the components of the color.

example: `#ff6347`

**CSS HSL Colors**

In CSS, a color can be specified using hue, saturation, and lightness (HSL) in the form:
`hsl(hue, saturation, lightness)`.

example: `hsl(0, 100%, 50%)`.

------------------------------

## Chapter 12: “Text”

CSS has a lot of properties for formatting text.

**Text Color**

The color property is used to set the color of the text.

**Text Alignment**
The text-align property is used to set the horizontal alignment of a text.

A text can be left or right aligned, centered, or justified.

**Text Decoration**

![text-decotation](https://media.geeksforgeeks.org/wp-content/uploads/color-4.png)

this image showing 3 proparites give to text.

**Text Transformation**

The text-transform property is used to specify uppercase and lowercase letters in a text.

`p.uppercase {
  text-transform: uppercase;
}`

`p.lowercase {
  text-transform: lowercase;
}`

`p.capitalize {
  text-transform: capitalize;
}`


**Text Indentation**
The text-indent property is used to specify the indentation of the first line of a text:

![text-indentation](https://image.slidesharecdn.com/csstools-111111094434-phpapp01/95/css-power-tools-63-728.jpg?cb=1321004825)


**Letter Spacing**
The letter-spacing property is used to specify the space between the characters in a text.

**Text Shadow**
The text-shadow property adds shadow to text.

![text-shadow](https://codesdope-media.nyc3.cdn.digitaloceanspaces.com/prod/media/blog_images/15/2019/3/9/25shadow.png)

------------------------------

**JPEG images** don’t support transparency and are hence not usable for such cases.

**PNG images** support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background. PNG8 images (discussed in the “Colours” section below) can support only index transparency whereas PNG24 images can support alpha channel transparency.

**GIF images** support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.

this informatin from
[Blog | ImageKit.io](https://blog.imagekit.io/jpeg-vs-png-vs-gif-which-image-format-to-use-and-when-c8913ae3e01d)
