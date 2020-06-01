# Responsive Web Design 

## Responsive vs Adaptive:

- responsive sites adapt quickly and positively to change
- these terms could be used relatively interchangeably in the field

## Mobile design:

- Some places will have completely separate sites built for mobile users vs desktop users
- Depends on a different code base and browser sniffing
- Respinsive design in the preferred method in the filed 


Three main components of responsive design:
1. Flexible layouts
2. Media queries
3. Flexible media

## Flexible layouts:

- Build layout grids using relative units such as percentages and ems, instead of absolute measures like pixels for margins, width and padding

New CSS properties:
- **vh**: viewport height, based on the users device
- **vw**: viewport width, based on user's device
- **vmin**: minimum of the viewport's height and width
- **vmax**: maximum of the viewport's height and width

Responsive design formula:
target width of element / width of parent element = relative width of target

## Media Queries:
Initializing: 
**HTML**: 
````
<link href = "style.css" rel = "stylesheet" media = " all and (max-width 1024px)>
````
**CSS:**
````
@media and all (max-width 1024px) {
...
}
````
**Import rule:**
````
@import url(style.css) all and (max-width 1024px){
...
}
````
Media types: all, screen, prints, tv, braille, etc (defaults to screen if not specified)

### Mobile first technique:
- Uses styles targeted at smaller viewports as the default for the websites
- Uses media queries to add styles as the viewport gets alrger, as opposed to the other way around

## Flexible Media:

- images and videos need to be scalable
- embedded videos and some media types need a workaround for this:
- can be achieved by adding a container and setting to 100% max width of the container
-embedded media needs to be positioned absolutely within a parent element to be responsive, and parent element needs to be 100% width and height with a vh of 0

# All About Floats:

- floated elements remain a part of the web-page

## How to use clear properly:
- elements given "clear" property after a float will not move up adjacent to the floated element
- example: clear floats on a footer to prevent it from not taking up the whole bottom of a page

## problems with floats:
- pushdown: elements within a floated element can become wider than the float itself
- double margins


