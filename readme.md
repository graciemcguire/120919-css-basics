CSS Minis - Part 1: Intro & Box Model
SWBAT
Discuss what CSS does and why it's important
Differentiate between inline, internal, and external stylesheets
Understand how to use class, id, and element selectors, and selector order of importance
Demonstrate the use of the box model

CSS Basics


What is it?
What Does it Do?
Examples
CSS Zen Garden
[Geocitiesizer] (https://www.wonder-tonic.com/geocitiesizer/)
[Ling's] (https://www.lingscars.com/)
Stylesheets and Selectors
How do we add CSS to our HTML page?

Inline
style="color:blue;text-align:center;">

Internal
<style><style/>

External import external page
< link rel="stylesheet" href="styles.css" >


Types of CSS selectors & their hierarchy

HTML tags/elements
Classes
IDs
Element Selector:
ul li {
  color: black;
}

Class Selector:
.list-item {
  color: red;
}

ID Selector:
#list-item {
  color: green;
}

The Box Model
What is the box model?
4 Elements of the box model:

Content - The content of the box, where text and images appear
Padding - Clears an area around the content. The padding is transparent
Border - A border that goes around the padding and content
Margin - Clears an area outside the border. The margin is transparent

Resources
Awwwards
codrops
CSS Tricks
CSS Grid Guide
CSS MDN
CSS Zen Garden
Flexbox Froggy
CSS Grid Garden
DaFont
Lost Type
