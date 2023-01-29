# CSS - Cascading Style Sheets

Used to stylize an HTML page

HTML-> Where an HTML element is present while CSS describes how it looks.

## CSS3

1. Mobile First Mentality
2. Module Based Code
3. Web Font Support
4. Enables fast development and Load Times(Smart File Size)
5. 2d and 3D Animations
6. New Colors and Image Affects
7. Box Size Fixed

## Targets

1. class: For small individual styles within a page. Starts with '.' in the CSS Files and class="" in HTML file.
2. id: Starts with # in CSS Files and id="" in HTML file, usualy is used to define a page's area(Top, Bottom, Side etc). Any name can be used.
3. html element: Apply style to all the HTML elements used in the HTML page.
4. All Selector: Used as * in the CSS File. Used to overwrite the default CSS values in an HTML page.

## CSS3

1. The Box Model: Consider each HTML Tag as a Box on the screen with padding, margin, border and content.

2. Poistion: Can be absolute or relative or fixed. Absolute = the div will position itself with no regard to the neighbouring divs while Relative will keep these in mind while the Fixed will create a sticky div.

3. Float: By default the HTML elements are added one after another in a line from top to bottom, to change this we can use the float attribute in css to make the next element to be added to the provided position of the previous element.

4. Clear: Once we apply the float property on a div we might want to ensure that this ends for the next element. So we can use the clear attribute here to ensure that the left/right side of the html element is clear of any other HTML element.

5. Display: This attribute can be set to either block/inline. This will ensure that the element we have set this to is displayed as a seperate "block" ie in the next line unless we set the float attribute. Or is displayed in a single line as text.