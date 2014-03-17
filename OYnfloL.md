---
author: JustinGuarachado
views: 0
published: false
type: lesson
id: "JustinGuarachado-OYnfloL"

---

## Summary:
During this lesson, students will get an introduction to styling a website with CSS and learn about the properties and values for styling text.
By the end of the lesson students will be able to:

- explain why a website needs CSS
- define a CSS selector
- recognize all of the parts of a CSS rule


## Materials:
- Computers with internet access

## Preperation:
- Create a poster with the example CSS rule
- Create a poster with a list of CSS properties and the possible values for the properties
- Print the CSS checklist worksheet

## Lesson:
#### Review:
What is HTML?
HTML is the language that web developers use to create websites. Each HTML tag translates to an element on the page.

## Show
HTML on its own creates elements but has no style. An example of a website with just HTML can be found here. Ask students if this is a web page that they would like to make? Why not?


## Explain
To style the website Cascading Style Sheets or CSS needs to be added to the website. CSS is written as a series of rules that define what the HTML tags look like.

#### Example
```
CSS
*Needs actual picture*

```
Using the example website type the following into the CSS box:
The title of the page in the preview area will jump to the middle of the page.
## How it works:
Each rule consists of two parts: the selector and a series of declarations that are separated by semi-colons. The selector determines which tag(s) the rule is for, and the declaration defines the rule.

Selector                                    Declaration

```                                            ```
*Needs picture                                { text-align : center; }
                                                 Property     Value
                                                 *Needs picture
```                                               ```

In this example, the selector h1 will select any <h1> header tag in the HTML. The declaration ‘text-align : center’ sets the text to align to the middle of the heading.

There are different types of selectors but today students will be introduced to only the element selector. The element selector will set the rule for all of the HTML elements with the tag. For example the selector ‘h1’ will set the rules for all of the <h1> elements. The ‘img’ selector will set the rules for any <img> elements on the page.

Yellow Highlight:
CHECK FOR UNDERSTANDING:
Which elements will be affected by the above CSS rule?
Any element with the h1 tag will be affected.

## As A Group:
Using the properties poster in the classroom, figure out the correct CSS rule to change the font size of all of the paragraphs to 25px.

Selector                                  Declaration
```                                          ```
P                                        {Font-size : 25pc;}
                                           Prperty    Value
```                                         ```

## Review:
Which tags contain text?
The <h1> and <p> tags contain text.

Which CSS selector will set the rules for the paragraphs?
The selector ‘p’ will set rules for all of the paragraphs.

## Practice:
Students will now get on the computer and go to the http://codepen.io/9dots/pen/xAhfi and set CSS rules for the various selectors according to the handout. The selectors and properties should be already typed for the students, they only need to change the values to the specified answers.

## Explore:
After practicing, student will now use the font properties to practice changing the text of the webpage. Students need to try all of the properties to see the effect that they have on the text. The most exciting web site will be projected for the class to see.

# Go Beyond:
If students complete the work early, they can try editing one of the featured pens on the codepen home site. When they are editing the website they should try to find the CSS relating to text and change it to see what happens to the website.
