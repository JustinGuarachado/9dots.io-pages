---
author: JustinGuarachado
views: 0
published: false
type: lesson
id: "JustinGuarachado-OYnmIHi"

---

## Summary:
During this lesson, students will continue to explore CSS and learn how to resize elements and create margins create space between elements.
By the end of the lesson students will be able to:
   - use the height and width properties to resize elements
   - explain how the margin property is used to create space between           		elements
   - inspect websites and look at the HTML and CSS rules for an 		element

## Materials:
- Computers with internet access and Chrome browser

## Preperation:

- Create a poster with the box model to help explain margins
- Create a poster with a list of CSS properties and the possible values for:
	○ width
	○ height
	○ margin

## Lesson:
#### Review:
What is CSS?
Cascading Style Sheets or CSS is a language that adds styles and formatting to a website. The HTML creates the elements and the CSS defines what they look like with a series of rules.

Selector                                      Declaration
```												```
h1												{ text-align: center;}
												 Property  Value
                                                 *Need actual picture
```													```
What is the structure of a CSS rule?
A CSS rule is broken into two parts: the selector and the declaration. The declaration has a property and the value for that property.
## Discuss:
Using the http://codepen.io/9dots/pen/xAhfi example site again, ask students what needs to be fixed now that they can already create properly styled text. Guide them to the answer that many of the elements are the wrong size and are too close to each other. To change that we are need to learn about some new CSS properties.

## Introduce:
CSS uses the box model to organize elements. Using the Box Model poster, show students that every element has a width and a height property for the content. For an image that would set the width and the height of the image itself. The elements also have a margin. The margin is a box that surrounds the element to add spacing between the element and other elements on the page.

```
*Add picture here

```

## Show:
SHOW:
Using the http://codepen.io/9dots/pen/xAhfi example site input the following into the CSS box:

```
img{
	Width:300px;
    Height:400px;
    Margin:15px;
 Afterward, show students the ability to inspect the element. In Google Chrome, right click one of the images and the select ‘Inspect Element’. This will open a window in your browser that shows all of the HTML and CSS used on the element. The section on the right is where the CSS is shown. Scroll to the bottom of that section and there is an interactive version of the box model. Hovering over each section will show where it is on the element.
 
 ## Guided:
Students will now open their computers to the same http://codepen.io/9dots/pen/xAhfi example site. With the teacher, students will attempt to change the height, width, and margin of the images on their website.

## Discuss:
Do you always want all of the images to be the same size? No, sometimes we want to be able to set the size of an individual image without changing the rest of them. To do this we are going to give an HTML element an id.
```
<img id="logo" src="batman"></img>

```
## Explain:
Once the HTML has an id, instead of selecting all of the <img> tags, we can use a different kind of selector to edit just one. This is called an id selector. To tell the CSS to edit an id we need to put a ‘#’ followed by the id. For the example above that would be:

```
 #Logo{
        Width:600px;
        Height:400px;
        Margin:20px'
        
 ```
## Explore
Using the new information student will have 10 minutes to attempt to edit the website and make it look as nice as possible. The student who is working the hardest will have his/her website displayed on the projector for the entire class.




