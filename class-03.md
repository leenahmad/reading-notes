# Lists

HTML offers web authors three ways for specifying lists of information. All lists must contain one or more list elements. Lists may contain −

1. ul> − An unordered list. This will list items using plain bullets.

 2. ol>  − An ordered list. This will use different schemes of numbers to list your items.

3. dl> − A definition list. This arranges your items in the same way as they are arranged in a dictionary.

## HTML Ordered List or Numbered List

In the ordered HTML lists, all the list items are marked with numbers by default. It is known as numbered list also. The ordered list starts with ol> tag and the list items start with li> tag.

![html](https://codebridgeplus.com/wp-content/uploads/ordered-lists-2-638.jpg)

### Example 

`<ol>`

 `<li>`Aries`</li>`  
 `<li>`Bingo`</li>`  
 `<li>`Leo`</li>` 
 `<li>`Oracle`</li> ` 

`</ol>`

Output:

1. Aries
2. Bingo
3. Leo
4. Oracle


## HTML Unordered List or Bulleted List
In HTML Unordered list, all the list items are marked with bullets. It is also known as bulleted list also. The Unordered list starts with <(ul> tag and list items start with the <(li> tag.



### Example of ordered and unorderd list 
![html](https://wpastra.com/wp-content/uploads/2017/11/bullet-lists-code.png)

## HTML Description List or Definition List
HTML Description list is also a list style which is supported by HTML and XHTML. It is also known as definition list where entries are listed like a dictionary or encyclopedia.

The definition list is very appropriate when you want to present glossary, list of terms or other name-value list.

The HTML definition list contains following three tags:

1. <(dl)> tag defines the start of the list.
2. <(dt>) tag defines a term.
3. <(dd)> tag defines the term definition (description).

### Example of HTML Description List or Definition List

![html](https://slideplayer.com/slide/8664259/26/images/8/Definition+List+%28cont.%29.jpg)


## HTML Nested List
A list within another list is termed as nested list. If you want a bullet list inside a numbered list then such type of list will called as nested list.

![html](https://i.stack.imgur.com/rqAiC.jpg)

## Lists Summary
- There are three types of HTML lists: ordered,
unordered, and definition.
-  Ordered lists use numbers.
- Unordered lists use bullets.
- Definition lists are used to define terminology.
- Lists can be nested inside one another.

# Boxes

In CSS, the term "box model" is used when talking about design and layout.

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. 

![css](https://codinglead.github.io/images/box-model.png)

xplanation of the different parts:

- Content - The content of the box, where text and images appear
- Padding - Clears an area around the content. The padding is transparent
- Border - A border that goes around the padding and content
- Margin - Clears an area outside the border. The margin is transparent.


## Width and Height of an Element

In order to set the width and height of an element correctly in all browsers, you need to know how the box model works.

## *CSS Setting height and width*
The height and width properties
 are used to set the height and width of an element.

The height and width properties
 do not include padding, borders, or margins. It sets the height/width of the area inside the padding, border, and margin of the element.

## *CSS height and width Values*
The height and width properties may have the following values:

auto - This is default. The browser calculates the height and width

length - Defines the height/width in px, cm etc.

% - Defines the height/width in percent of the containing block
initial - Sets the height/width to its default value.

inherit - The height/width will be inherited from its parent value.

## Min Width to Max Width
You can also use the (max-width: ..) and (min-width: ..) values to set a minimum width and a maximum width

![css](https://i.stack.imgur.com/k9vLo.png)

## Overflowing Content overflow
The overflow property specifies what should happen if content overflows an element's box.

This property specifies whether to clip content or to add scrollbars when an element's content is too big to fit in a specified area.

Value	| Description
-------- | -----------
visible |The overflow is not clipped. It renders outside the element's box. This is default
hidden |The overflow is clipped, and the rest of the content will be invisible.
scroll |The overflow is clipped, but a scroll-bar is added to see the rest of the content
auto |If overflow is clipped, a scroll-bar should be added to see the rest of the content	
initial |Sets this property to its default value. Read about initial	
inherit |Inherits this property from its parent element. Read about inherit

## border-width

The border-width property sets the width of an element's four borders. This property can have from one to four values.

Examples:

- border-width: thin medium thick - - 10px;
- - top border is thin
- - right border is medium
- - bottom border is thick
+ - left border is 10px

- border-width: thin medium thick;
- - top border is thin
- - right and left borders are medium
- - bottom border is thick

- border-width: thin medium;
- - top and bottom borders are thin
- - right and left borders are medium

- border-width: thin;
- - all four borders are thin

![css](https://media.geeksforgeeks.org/wp-content/uploads/border-width-with-one-value.png)

## CSS Border Style
The border-style property specifies what kind of border to display.

The following values are allowed:

- dotted - Defines a dotted border
- dashed - Defines a dashed border
- solid - Defines a solid border
- double - Defines a double border
- groove - Defines a 3D grooved - border. The effect depends on - the border-color value
- ridge - Defines a 3D ridged border. The effect depends on the border-color value
- inset - Defines a 3D inset border. The effect depends on the border-color value
- outset - Defines a 3D outset border. The effect depends on the border-color value
- none - Defines no border
- hidden - Defines a hidden border

The border-style property can
 have from one to four values (for the top border, right border, bottom border, and the left border).

 ![css](https://i.stack.imgur.com/SlpZv.png)

 ## CSS Border Color
The border-color property is used to add color to border of an element. This property does not work if it is used alone, so first, the “border-style” property is used to set the borders. This can take one to four values for the top border, right border, bottom border, and the left border respectively. If this property is not set then it inherits the color of the element.

Syntax:

border-color: color-value;

The color can be set by:

- name - specify a color name, like "red"
- HEX - specify a HEX value, like "#ff0000"
- RGB - specify a RGB value, like "rgb(255,0,0)"
- HSL - specify a HSL value, like "hsl(0, 100%, 50%)"
transparent

Example :
  h1 {
            color: #009900;
        }
          
        p.one {
            border-style: solid;
            border-color: blue;
        }
          
        p.two {
            border-style: solid;
            border-color: bluered 
            yellow green;
        }
          
        p.three {
            border-style: solid;
            color: green;
        }


![css](https://media.geeksforgeeks.org/wp-content/uploads/output1-13.png)


## Boxes Summary 
- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding
for each box with CSS.
- It is possible to hide elements using the display and
visibility properties.
- Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
- Legibility can be improved by controlling the width of
boxes containing text and the leading.
- CSS3 has introduced the ability to create image
borders and rounded borders.

# Decisions and Loops

conditional statements are used to perform different actions based on various conditions. The conditional statement evaluates a condition before the execution of instructions.

When you write the code, you require to perform different actions for different decisions. You can easily perform it by using conditional statements.

Types of Conditional Statements
The conditional statements in JavaScript are listed below:

- if statement
- if….else statement
- if….else if….statement
- nested if statement
- switch statement

1. The if statement
It is one of the simplest decision-making statement which is used to decide whether a block of JavaScript code will execute if a certain condition is true.

## Syntax

if (condition) {  
  // block of code will execute if the condition is true  
} 

If the condition evaluates to true, the code within if statement will execute, but if the condition evaluates to false, then the code after the end of if statement (after the closing of curly braces) will execute.

2. The if….else statement
An if….else statement includes two blocks that are if block and else block. It is the next form of the control statement, which allows the execution of JavaScript in a more controlled way. It is used when you require to check two different conditions and execute a different set of codes. The else statement is used for specifying the execution of a block of code if the condition is false.

## Syntax

if (condition)  
 {  
  // block of code will execute if the condition is true  
}  
 else  
 {  
  // block of code will execute if the condition is false  
}  

If the condition is true, then the statements inside if block will be executed, but if the condition is false, then the statements of the else block will be executed.

3. The if….else if…..else statement
It is used to test multiple conditions. The if statement can have multiple or zero else if statements and they must be used before using the else statement. You should always be kept in mind that the else statement must come after the else if statements.

## Syntax

if (condition1)   
{  
  //  block of code will execute if condition1 is true  
}  
 else if (condition2)   
{  
  //  block of code will execute if the condition1 is false and condition2 is true  
}   
else   
{  
  //  block of code will execute if the condition1 is false and condition2 is false  
}  

4. The nested if statement
It is an if statement inside an if statement.

## Syntax

if (condition1)   
{   
Statement 1; //It will execute when condition1 is true  
if (condition2)  
 {   
Statement 2; //It will execute when condition2 is true  
}  
else  
{  
 Statement 3; //It will execute when condition2 is false  
}  
} 

5. The switch statement
It is a multi-way branch statement that is also used for decision-making purposes. In some cases, the switch statement is more convenient than if-else statements. It is mainly used when all branches depend upon the value of a single variable. It executes a block of code depending upon the different cases.

The switch statement uses the break or default keywords, but both of them are optional. Let us define these two keywords:

break: It is used within the switch statement for terminating the sequence of a statement. It is optional to use. If it gets omitted, then the execution will continue on each statement. When it is used, then it will stop the execution within the block.

default: It specifies some code to run when there is no case match. There can be only a single default keyword in a switch. It is also optional, but it is recommended to use it as it takes care of unexpected cases.

If the condition passed to switch doesn't match with any value in cases, then the statement under the default will get executed.

## Syntax

switch(expression){      
case value1:      
 //code to be executed;      
 break;  //optional    
case value2:      
 //code to be executed;      
 break;  //optional    
......      
      
default:       
 code to be executed if all cases are not matched;      
}   

![js](https://static.javatpoint.com/tutorial/es6/images/es6-decision-making4.png)

## Summary Decisions and Loops

- Conditional statements allow your code to make
decisions about what to do next.
- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
- Logical operators allow you to combine more than one
set of comparison operators.
- if ... else statements allow you to run one set of code
- if a condition is true, and another if it is false.
- switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).
- Data types can be coerced from one type to another.
- All values evaluate to either truthy or falsy.
- There are three types of loop: for, while, and
do ... while. Each repeats a set of statements.
