# Forms:

-example **(the search box)**.

-There are several types of form controls that you can use to collect information from users:

1- ADDING TEXT:

![text](https://th.bing.com/th/id/R475aea2853c0965d749f871a1dd34a49?rik=avmzul5tz321Jg&pid=ImgRaw)

2-Making Choices:

![m c](https://th.bing.com/th/id/Re4cfc291a8755c3ce63b646d9b1282dc?rik=%2fRZHLx4Fooeu%2bQ&pid=ImgRaw)

3-Submitting Forms:

![submit](https://th.bing.com/th/id/R0c4d75e25df4931701d3e78be9b63723?rik=sXPir2Sy6uQ9gA&pid=ImgRaw)

**Form Structure `<form>`**

-action :Every `<form>` element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.

-method:Forms can be sent using one of two methods: get or post.

a. With the **get method**, the values from the form are added to the end of the URL specified in the action attribute. The get method is ideal for:

* short forms (such as search boxes).

* when you are just retrieving data from the web server (not sending information that should be added to or deleted from a database).

b. With the **post method** the values are sent in what are known as HTTP headers. As a rule of thumb you should use the post method if your form:

* allows users to upload a file
* is very long
* contains sensitive data (e.g. passwords)
* adds information to, or deletes information from, a database.

**Text input:**

-The `<input>` element is used to create several different form controls. The value of the type
attribute determines what kind of input they will be creating.

1-`type="text"`When the type attribute , it creates a singleline text input(when it has a value of text).

**name** (For example, in a login form)

**size**:The size attribute should not be used on new forms. It was used in older forms.

**maxlength**You can use the maxlength
attribute to limit the number of characters a user may enter into the text field. 

2-Password Input `type="password"`: to enter password.

3-`type="radio"`Radio buttons allow users to pick just one of a number of options.

4-`type="checkbox"`Checkboxes allow users to select (and unselect) one or more options in answer to a question.

5-`type="submit"`:The submit button is used to send a form to the server

6-`type="hidden"`:They allow web page authors to add values to forms that users cannot see.

##Lists, Tables and Forms:

`list-style-type`

a- **Unordered Lists**

For an unordered list you can use the following values:
 * none
 * disc
 * circle
 * square

b- **Ordered Lists**

-you can use the following values:
* decimal(1 2 3)
* decimal-leading-zero(01 02 03)
* lower-alpha(a b c)
* upper-alpha(A B C)
* lower-roman(i. ii. iii.)
* upper-roman (I II II)

![list](https://th.bing.com/th/id/OIP.2pA0-LhTQLQ1zYykEAJi_wHaCr?pid=ImgDet&rs=1)

-`list-style-image`:

-The value starts with the letters url and is followed by a pair of parentheses. Inside the parentheses, the path to the image is given inside double quotes.

![image](https://forum.blocsapp.com/uploads/db8018/original/1X/cd4490dc503feaf572d1cd1570e25ecd86bdb87f.png)

-`list-style-position`: 

* outside:The marker sits to the left of the block of text.

* inside:The marker sits inside the box of text.

**Aligning Form Controls**

-We can use a property **float** to move the titles to the left of the page


-`cursor`The cursor property allows you to control the type of mouse cursor that should be displayed 
to users.

-Here are the most commonly used values for this property:

![cursor](https://th.bing.com/th/id/Rfccc31cd65bcc56f9f760082f511a192?rik=Glrmachu9LQwRQ&riu=http%3a%2f%2fschubiserv.de%2fimages%2fcursor-windows.png&ehk=567Lt%2breBym80TIsgeP2w7hynuSQy9G4ued1UPC2i3w%3d&risl=&pid=ImgRaw)

## DIFFERENT EVENT TYPES:

-while you are browsing the web, there is a selection of the events that occur in the browser:

1- UI EVENTS:when a user interacts with the browser's user interface (UI)

2- KEYBOARD EVENTS:when a user interacts with the keyboard 

3- MOUSE EVENTS :when a user interacts with a mouse. trackpad, or touchscreen 

 ![](https://th.bing.com/th/id/Rd19efad6a24d2d49afaa9dcf960a3694?rik=a5SVjukp0ijG6A&pid=ImgRaw)

**HOW EVENTS TRIGGER JAVASCRIPT CODE**:

![](https://i.stack.imgur.com/YszX3.png)

1. Select t he element node(s) you want the script to respond to.

2. Indicate which event on the selected node(s) will trigger the response.

3. State the code you want to run when the event occurs. 

**Event flow**

a. event bubbling
b. event capturing

![event](https://th.bing.com/th/id/OIP.6KjsLCZJHesH2dAHCbk0PAHaB3?pid=ImgDet&rs=1)

_EVENT LISTENER WITH NO PARAMETERS_

![](https://www.codegrepper.com/codeimages/javascript-pass-parameter-to-event-listener.png)

_EVENT LISTENER WITH PARAMETERS_

![](https://th.bing.com/th/id/R5760f253aa6e354db12c6b0f057787ca?rik=%2f3JRvfLsxROx8w&riu=http%3a%2f%2f1.bp.blogspot.com%2f_x8Kft4g8fUQ%2fTQsQG7Jb8aI%2fAAAAAAAAAJg%2fzzFXj0gdD04%2fs400%2f003hear.jpg&ehk=dCPdZcESNNplHc181dQdlQd%2b2vn7ILFqwO%2fFjUBbUj0%3d&risl=&pid=ImgRaw)

## DIFFERENT TYPES OF EVENTS :
* W3C DOM EVENTS
* HTM LS EVENTS
* BOM EVENTS 

![](https://image.slidesharecdn.com/jsdom-130412075940-phpapp01/95/javascript-dom-manipulations-36-638.jpg?cb=1365753679)



