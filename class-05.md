# Class 5 Reading Notes

## Images

It is good practice to store the images on your site in a folder rather than linking to an image URL

Images are added as shown:
````
<img src="imagefile.jpg" alt="a text description of the image when you cannot see it" 
title="content that may display if the user hovers the cursor over the image" />
````
**Image tags are self closing**

- Note: the align attribute in html is outdated, one should use CSS to place images

- Images should be saved at the correct size, rather than scaling the images in your styling
- Designers can use tools such as photoshop and other software to resize images

### Image Formats:

- jpeg: used for bright, images with vibrant color ranges
- png: use when saving images that have few colors or large areas of the same color, such as logos or graphics. Do **not** use png for images of sky and snow, as these have dynamic range and are not considered areas of the same color
- Source images that are the correct shape rather than cropping them
- Animated gifs: these shows several frames as an image creating short animations. 
-Transparancies can only be created in png or gif format. 

## Color

Colors is CSS can be specified in 4 ways:

1. RGB Values: These express colors in terms of how much green, red and blue are used to make it. They are written like rgb(100,100,90), for example. 

2. Hex Codes: These are siz digit codes that represent the amount of red, green and blue in a color, for example, #ee3e80

3. Color Names: These are a list of predefined colors that browsers recognize.

4. HSLA: Short for Hue, Saturation, Lightness and Alpha. 

## Contrast

When desinging pages, it is extremely important to consider contrast.

Low Contrast: text is hard to read in this condition, and it also affects that abilities of people with visual impairments or colorblindness to read the pages.

High contrast: These conditions make text easier to read and attracts attention, but may cause strain when reading long spans of small text.

Medium contrast: These conditions improve readability for long spans of text. This is created using dark grey text on a white background, or off-white text on a dark background. 

## Text

Typeface Terminology:
- Serif: have extra details off the main strokes on the letters
- Sans-serif: have straight ends to letters and much cleaner design
- Monospace: every letter is a fixed width and occupies the same amount of space

Be careful wehn choosing types faces, if will only display a specific font if it is installed on a user's computer however, ther are some workarounds to this

- Font-family: This allows you to specify a specific typeface, while also specifying alternates if the user does not have your first choice installed. Be aware that this still requires the specified fonts to be installed on the user's computer.
- Font-Face: specifies where a font can be downloaded if it is not installed on the user's computer

Specifying font sizes:
- font sizes can be specified in pixels, percentages, and ems

### Font styling:

text-transform:
- uppercase: Makes all of the letters in an element uppercase
- lowercase: makes all the letters in an element lowercase
- capitolize: capitolizes the first letter of every word

Spacing:
- the term typographers use for the spacing between letters is kerning
- kerning can be controled with the letter-spacing property

Alignment:
- left: text will be aligned to the left
- Right: text will be aligned to the right:
- center
- justify: every line in a paragraph will take up the full width on its container

Styling links:
- :link allows you to style links you have not yet visited
- :visited allows you to set styles for links you have visted

Responding to users:
- :hover is applied when a user hovers the cursor over an element
- :active is applied when an element is being activated by a user, such as pressing a button or clicking a link
- :focus is applied when an element has focus

**[Back to Main Page](README.md)**




