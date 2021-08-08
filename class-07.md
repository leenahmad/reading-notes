# Tables

HTML table tag is used to display data in tabular form (row * column). There can be many columns in a row.

We can create a table to display data in tabular form, using `<table>` element, with the help of `<tr>` , `<td>`, and `<th>` elements.

In Each table, table row is defined by `<tr>` tag, table header is defined by `<th>`, and table data is defined by `<td>` tags.

HTML tables are used to manage the layout of the page e.g. header section, navigation bar, body content, footer section etc. But it is recommended to use div tag over table to manage the layout of the page .

![img](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/07/Html-Tables.jpg)

The `<table>` tag defines the contents of the table. Each row is defined by `<tr>` tags, and is made up of a number of data (or header) cells. The number of columns is defined by the number of cells in a row. Data cells are indicated by the `<td>` tag. A table cell may contain any data that can be displayed in an HTML document (formatted text, images, multimedia elements, and even other tables).


## Spanning Column
The colspan attribute in HTML specifies the number of columns a cell should span. It allows the single table cell to span the width of more than one cell or column. It provides the same functionality as “merge cell” in a spreadsheet program like Excel.
Usage: It can be used with `<td>` and `<th>` element while creating an HTML Table.
 

Attribute Values: It contains a value i.e number Which specify the number of columns that a cell should span. 

`<td>`: The colspan attribute when used with `<td>` tag determines the number of standard cells it should span. 

## Syntax: 
`<td colspan = "value">table content...</td>`

![img](https://i.ytimg.com/vi/67tkBXxLH9M/maxresdefault.jpg)


`<th>`: The colspan attribute when used with `<th>` tag determines the number of header cells it should span. 

## Syntax: 

`<th colspan = "value">table content...</th>`

The value specifies the number of columns that the cell fills. The value must be a integer. 

## Spanning Rows
The rowspan attribute in HTML specifies the number of rows a cell should span. That is if a row spans two rows, it means it will take up the space of two rows in that table. It allows the single table cell to span the height of more than one cell or row. It provides the same functionality as “merge cell” in the spreadsheet program like Excel.
Usage: It can be used with `<td>` and `<th>` element in an HTML Table.
 

Attribute Values: It contains a value i.e number Which specify the number of rows that a table cell should span. 

`<td>`: The rowspan attribute when used with `<td>` tag determines the number of standard cells it should span.

## Syntax: 
`<td rowspan = "value">table content...</td>`

![img](https://media.geeksforgeeks.org/wp-content/uploads/20190626005621/throwspan.png)

`<th>`: The rowspan attribute when used with `<th>` tag determines the number of header cells it should span.

## Syntax: 

`<th rowspan = "value">table content...</th>`

## Summary Tables
- The `<table>` element is used to add tables to a web
page.
- A table is drawn out row by row. Each row is created
with the `<tr>` element.
- Inside each row there are a number of cells
represented by the `<td>` element (or `<th>` if it is a
header).
- You can make cells of a table span more than one row
or column using the rowspan and colspan attributes.
- For long tables you can split the table into a `<thead>`,
`<tbody>`, and `<tfoot>`.


# Object
A javaScript object is an entity having state and behavior (properties and method). For example: car, pen, bike, chair, glass, keyboard, monitor etc.

JavaScript is an object-based language. Everything is an object in JavaScript.

JavaScript is template based not class based. Here, we don't create class to get the object. But, we direct create objects.

## 
Creating Objects in JavaScript

1. By object literal.
2. By creating instance of Object directly (using new keyword).
3. By using an object constructor (using new keyword).


## 1) JavaScript Object by object literal
The syntax of creating object using object literal is given below:

`object= {property1:value1,\property2:value2.....propertyN:valueN}`

As you can see, property and value is separated by : (colon).

## 2) By creating instance of Object
The syntax of creating object directly is given below:

`var objectname=new Object();  
Here, new keyword is used to create object.`

## 3) By using an Object constructor
Here, you need to create function with arguments. Each argument value can be assigned in the current object by using this keyword.


The (*this keyword*) refers to the current object.

## Summary object 
- An object is a series of variables and functions that
represent something from the world around you.
- In an object, variables are known as properties of the
object; functions are known as methods of the object.
- Web browsers implement objects that represent both
the browser window and the document loaded into the
browser window.
- JavaScript also has several built-in objects such as
String, Number, Math, and Date. Their properties and
methods offer functionality that help you write scripts.
- Arrays and objects can be used to create complex data
sets (and both can contain the other).