
## Understanding The Problem Domain Is The Hardest Part Of Programming:

`Question` What is the hardest thing about writing code?
`Answer`
1. Learning a new technology
2. Naming things
3. Testing your code
4. Debugging
5. Fixing bugs
6. Making software maintainable

- By creating a familiar problem domain, you will find that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.
- Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

-If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

* Make the problem domain easier
* Get better at understanding the problem domain

## WHAT IS AN OBJECT?
![object](https://th.bing.com/th/id/R89d650cdba50b2419420ca847f18af89?rik=AcAuIFkl1edhGA&pid=ImgRaw)

 **object**:is a set of variables and functions to create a model of a something you would recognize from the real world. 

 ![obj](https://miro.medium.com/max/4096/1*GA7toY-Y3a3l0nlewOxIAw.png)

**CREATING· OBJECTS USING LITERAL NOTATION**:
![object literal](https://www.bookofnetwork.com/images/javascript-images/JS_Object-literal---syntax_04Oct16_1420.png)
##  DOM tree:


_DOM tree_:it is  a model of that page reated by the browser and it is stored in the browsers' memory.

![DOM](https://th.bing.com/th/id/R1651909abdd6d7f6eafc8832b685c4a9?rik=7czaMxwBW5uSRg&riu=http%3a%2f%2fcf.ppt-online.org%2ffiles%2fslide%2fl%2flG6hjyFR8carDYH7oVAtPW3exEOg0sSpQ1JKfm%2fslide-4.jpg&ehk=NnwggqOZcebybs4c8tjwoXk5CmiFRxsO0m5swN3JBPc%3d&risl=&pid=ImgRaw)

**WORKING WITH THE DOM TREE:

* STEP 1: ACCESS THE ELEMENTS.
* STEP 2: WORK W ITH THOSE eLEMENTS .

![dom](https://th.bing.com/th/id/OIP.isip1WWKYLI0G69dVSs3ggAAAA?pid=ImgDet&rs=1)

**ACCESSING ELEMENTS**:
-DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 
-there are Methods that return a single element node:
1. getElementByld( 'id '): Selects an individual element given the value of its i d attribute . 

![get](https://i.stack.imgur.com/g04yG.png)

2. querySelector( '
css selector'):Uses CSS selector syntax that would select one or more elements .

-there areMethods that return one or more elements(AS A NODELIST):
1. getEl ementsByClassName('class'): Selects one or more elements given the value of their cl ass attribute. 

2. getEl ementsByTagName( '
tagName '):Selects all elements on the page with the specified tag name.

3. querySelectorAll ( '
css selector'): Uses CSS selector syntax to select one or more elements and returns all of those that match.


**ADDING ELEMENTS USING DOM MANIPULATION**
1. creat the element`createEl ement () `
 2. give it content`createTextNode()` 
 3. add it to the DOM `appendChild() `
 **REMOVING ELEMENTS VIA DOM MANIPULATION**:
 1.store the element to be removed in a variable. 
 2.store the parent of thah element in a variable.
 3.remove the element from its conta ining element.

 ## * document.write() :
it is a simple way to add content that was not in the original source code to the page, but its use is rarely advised.

_ADVANTAGES _:
* It is a quick and easy way to show beginners how 
content can be added to a page. 
DISADVANTAGES 
* It only works when the page initially loads. 
* If you use it after the page has loaded it can: 
1. Overwrite the whole page 
2. Not add the content to the page 
3. Create a new page 
- It can cause problems with XHTML pages that are strictly validated. 
- This method is very rarely used by programmers these days and is generally frowned up.
