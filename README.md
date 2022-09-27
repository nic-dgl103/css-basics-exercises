# CSS Basics Exercise
This exercise was designed to help you understand this week's content. It is not graded.

1. Clone this repository onto your local computer.

2. In VS Code, add the following styles:
* Link both HTML pages to the external stylesheet
* Write an external style that uses the declaration below to change all the text on both HTML pages to a sans-serif font: <br/>
`{ font-family: sans-serif; }`
* Write an external style that turns all the h2 elements on both HTML pages green.
* Write an external style with a class selector that uses the declaration below to give the call-to-action sections on both HTML pages a crimson border: <br/>
`{ border: 1px solid crimson; }`<br/>
*Ask yourself: Why are we using a class selector? What would be a good name for this class? Why shouldn’t we call it “thin-red-border” for example?*

Go deeper:
* Write an external style with a combination descendant selector that turns the color of the h2 in the call-to-action section on both HTML pages crimson.<br/>
*Ask yourself: Why are we using a descendant selector?*
* On the About HTML page, write an inline style that uses the style below to give only the content about Jim Penman a grey background colour: <br/>
`background-color: gainsboro;`<br/>
*Ask yourself: Did we have to use an inline style? How else could we achieve the same result?*
* Write an external style that uses the declaration below to give all HTML section elements on both HTML pages some padding space: <br/>
`{ padding: 10px 20px; }`
* On the index page, write an embedded style that uses the class name “testimonial” to give the two sections that include quotes from clients the following styles: <br/>
`{ text-align: center; font-style: italic; background-color: gainsboro; margin: 10px 0; }`<br/>
*Ask yourself: Why are we using a class selector? What would be a good name for this class? Why shouldn’t we call it “homepage-italic-quote” for example?*
3. Make sure that you have the Prettier VS Code extension installed. On the index page, right-click > Format document to apply proper formatting. Repeat for the about page and the stylesheet.
