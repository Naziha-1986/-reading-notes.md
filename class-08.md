## *Layout:

-we use layout  to control where each element sits on the page and how to create attractive page layouts.
-CSS deals with each HTML element as if it is in its _own box_.this box will be **Block box**(start  on a new line ) or **inline box**(continue in the same line).

![block and inline](https://th.bing.com/th/id/R01bd85b015ee0b310cb017569c7eed8d?rik=jdGjArzotu858w&riu=http%3a%2f%2f4.bp.blogspot.com%2f-TiwOixlooJk%2fU4UyEnv_XpI%2fAAAAAAAACFs%2fNuuLz2IvoZ4%2fs1600%2fcss-display-block-vs-inline-block.png&ehk=EiE1Ba548uTmNLw7RJ6WJKdEWOcrrD5TcPZXQylJllU%3d&risl=&pid=ImgRaw)


`Question` **What is  containing or parent element?**

`Answer`
when one block-level element sits inside another block-level element.
![parent](https://i.stack.imgur.com/BpIFY.jpg)

### Controlling the Position of Elements:
-you can use **positioning schemes** in CSS that allow you to control 
the layout of a page by using:
*  normal flow(defult):`position:static`, each block-level element sits on top of the next one. 

 * relative positioning :`position:relative`moves an 
element in relation to where it  6would have been in normal flow.
 * absolute positioning: `position:absolute`.

### Floating elements `float`:
![float](https://th.bing.com/th/id/R84798aced356387af7c933d8810f7aef?rik=taC3JYG5D%2bnoTQ&pid=ImgRaw)

-you can flow an element and place it as far to the left or right of the containing element as possible.

-`clear`: it allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box.
-`float:left`
The left-hand side of the box
should not touch any other elements appearing in the same containing element.
-`float right`
The right-hand side of the box will not touch elements appearing in the same containing element
![left & rirht](https://th.bing.com/th/id/Ra057022c32b9c277048b1f39d6a7b1d7?rik=QIeU%2baBEh9l8JQ&pid=ImgRaw)

`float both`
Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.
`float none`
Elements can touch either side.

-If a containing element only
contains floated elements, some browsers will treat it as if it is zero pixels tall.

**Fixed Width Layouts**
Fixed width layout designs do not
change size as the user increases or decreases the size of their browser window.

**Advantages:**

*  Pixel values are accurate 
at controlling size and positioning of elements.
* The designer has far greater control over the appearance and position of items on the page than with liquid layouts.
* You can control the lengths of lines of text regardless of the size of the user's window.
* The size of an image will always remain the same relative to the rest of the page.

**Disadvantages**

* You can end up with big gaps 
around the edge of a page.
* If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read.
* If a user increases font sizes,
text might not fit into the allotted spaces.
* The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
* The page will often take up more vertical space than a liquid layout with the same content.

**CSS Frameworks**:
it aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on.

**Advantages:**

* They save you from repeatedly writing code for the same tasks.
* They will have been tested across different browser versions (which helps avoid browser bugs).

**Disadvantages**

* They often require that you use class names in your HTML code that only control the presentation of the page (rather than describe its content.
* In order to satisfy a wide variety of needs, they often contain more code than you need for your particular web page (commonly referred to as code “bloat”).

**Multiple style sheets:**
`@import`
-Some web page authors split up their CSS style rules into separate style sheets. For example, they might use one style sheet to control the layout and another to control fonts, colors and so on.
-There are two ways to add multiple style sheets to a page:
1: Your HTML page can link to one style sheet and that stylesheet can use the `@import`rule to import other style sheets.
2: In the HTML you can use a
separate  element for each style sheet.
