# Day 2
__12/01/2020__

## What is a Pseudo-Class and what are some of the most common ones you think you will use
A pseudo-class is set of classes that define an event on an element. For example, :hover is one of the most useful and common ones that exist. It allows for something to happen or change when the mouse is over the affected element. This could be changing colors, turning the icon to a different one, etc. I could see myself using :hover on almost every site that I would build as it allows for special functionality that seems to be on most websites these days.
    
## What is Specificity and how might you use it to your benefit?

Specificity is the value that is given to a css rule base on whether the rule is targeting a tag, class, or an id. Tags have a specificty of one, classes have a specificty of 10, and ids have a specificity of 100. Specificity allows you to set most things to a certain rule, such as a div that will have a background of blue. This lets you set all of the divs in your document to the one rule, which you can easily change. It would also be easy to overide on any divs with the class name of "blue" for example, as a class has a higher specificty than a tag. Using specificity allows us to modify our styles with many objects being affected, or only a few being drastically effected.

## What problems do you think you could run into if you over-utilized the !important feature?
The !important feature should only be used in rare cases and over-utulizing it will lead to having extremely high specificities in your css. This means that you won't really be able to override the !important tag, which could be annoying if you simply wanted to change the color of a document. It also could lead to instances where you equal a different !important tag, meaning that only one of your styles might appear, depending on which loads first. 