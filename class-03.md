# Lists in HTML:
1. **Unordered lists** `<ul>`:(begin with a bullet point)

 ![ul](https://image3.slideserve.com/6012517/unordered-lists-in-html-l.jpg)
 
2. **Ordered lists**`<ol>`:(each item has number)
 
![ol](https://th.bing.com/th/id/OIP.2z4UJIwvg9VsCWjKy7fJbgHaFj?pid=ImgDet&w=1024&h=768&rs=1)

3. **Definition lists**`<dl>`:it consists of a series of terms and their definitions. 

we use `<dt>` tag to contain the term being defined _(Defintion Term)_& use `<dd>` to contain the definition. 

 ![dl](https://i.ytimg.com/vi/ZPJ4H1H8okc/maxresdefault.jpg)
 
   `Question` **what is the mean of Nested lists?**
   
   ** Nested Lists: when you put list inside list (the nested list should be inside a `<li>` element of the list in which it is nested).for example:
 
![nested lists](https://th.bing.com/th/id/R3136b9a4be3f2d8f8dd29dc90cfe3c61?rik=sT5BUmXLNDwjzA&pid=ImgRaw)

## Boxes:
### Boxes Dimensions (width, height):

Boxes in HTML will appear as it defalut dimensions, so you ncan set your own dimensions for a box by using the height and width properties( use _pixels_, percentages, or 
ems).

## Border, Margin & Padding:

![border](https://i.ytimg.com/vi/N6GN9M2ZKvM/maxresdefault.jpg)

![border](https://i.ytimg.com/vi/RMNHZsDUZMo/maxresdefault.jpg)

1. ### **Border**:
The border separates the edge of one box from another.we can use border-width properity to control the width of a border.The value of this property can be:
*  pixels
*  thin
* medium
* thick
 **_we can't use percentages with this propert_**
![border](https://user-images.githubusercontent.com/85401880/122681054-2c96aa00-d1fb-11eb-930f-98fa9f7fa786.png)

-we can control the _individual size _of borders by using these separate propirities:

* border-top-width
* border-right-width
* border-bottom-width
* border-left-width

-we can control the style of a border using the **border-style** property. this property have these values:
* **solid** :a single solid line.
* **dotted** :a series of square dot.
* **dashed** :a series of short lines.
* **double** :two solid lines.
* **groove**: appears to be carved into the page.
* **ridge** :appears to stick out from the page.
* **inset** :appears embedded into the page.
* **outset**: looks like it is coming out of the screen.
* **hidden / none**: no border is shown.

-we can specify the color of a border using : **RGB values,hex codes or CSS color names**.


2. ### **Padding **:

