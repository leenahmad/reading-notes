# Forms
HTML Forms are required, when you want to collect some data from the site visitor. For example, during user registration you would like to collect information such as name, email address, credit card, etc.

A form will take input from the site visitor and then will post it to a back-end application such as CGI, ASP Script or PHP script etc. The back-end application will perform required processing on the passed data based on defined business logic inside the application.

There are various form elements available like text fields, textarea fields, drop-down menus, radio buttons, checkboxes, etc.

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRMVXEV3m_Mc6p1InOBkCtqFyeRG2-_bPSJSg&usqp=CAU)

## Why use HTML Form
HTML forms are required if you want to collect some data from of the site visitor.

For example: If a user want to purchase some items on internet, he/she must fill the form such as shipping address and credit/debit card details so that item can be sent to the given address.

The HTML `<form>` tag is used to create an HTML form.

## syntax 

`<form action = "Script URL" method = "GET|POST">`
   form elements like input, textarea 
   etc.

`</form>`


## HTML Form Controls
There are different types of form controls that you can use to collect data using HTML form −

- Text Input Controls
- Checkboxes Controls
- Radio Box Controls
- Select Box Controls
- File Select boxes
- Hidden Controls
- Clickable Buttons
- Submit and Reset Button
## Text Input Controls

There are three types of text input used on forms −

1. Single-line text input controls − This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML `<input>` tag.

2. input controls − This is also a single-line text input but it masks the character as soon as a user enters it. They are also created using HTMl `<input>` tag.

3. Multi-line text input controls − This is used when the user is required to give details that may be longer than a single sentence. Multi-line input controls are created using HTML `<textarea>` tag.

Single-line text input controls
This control is used for items that require only one line of user input, such as search boxes or names. They are created using HTML `<input>` tag.



### *Attributes*
Following is the list of attributes for `<input>` tag for creating text field.
	
1. type : Indicates the type of input control and for text input control it will be set to text.

2. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

3.	value : This can be used to provide an initial value inside the control.

4. size : Allows to specify the width of the text-input control in terms of characters.

5. maxlength : Allows to specify the maximum number of characters a user can enter into the text box.

## Password input controls
This is also a single-line text input but it masks the character as soon as a user enters it. They are also created using HTML `<input>`tag but type attribute is set to password.


## Attributes
Following is the list of attributes for `<input> ` tag for creating password field.

1. type : Indicates the type of input control and for password input control it will be set to password.

2. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

3. value : This can be used to provide an initial value inside the control.

4. size : Allows to specify the width of the text-input control in terms of characters.

5. maxlength : Allows to specify the maximum number of characters a user can enter into the text box.

## Multiple-Line Text Input Controls
This is used when the user is required to give details that may be longer than a single sentence. Multi-line input controls are created using HTML `<textarea>` tag.



## Attributes
Following is the list of attributes for `<textarea>` tag.

1. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

2. rows : Indicates the number of rows of text area box.

3. cols : Indicates the number of columns of text area box

## Checkbox Control
Checkboxes are used when more than one option is required to be selected. They are also created using HTML `<input>` tag but type attribute is set to checkbox..

## Attributes
Following is the list of attributes for `<checkbox>` tag.

1. type : Indicates the type of input control and for checkbox input control it will be set to checkbox..

2. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

3. value : The value that will be used if the checkbox is selected.

4. checked : Set to checked if you want to select it by default.

## Radio Button Control
Radio buttons are used when out of many options, just one option is required to be selected. They are also created using HTML `<input>` tag but type attribute is set to radio.

## Attributes
Following is the list of attributes for radio button.

Sr.No	Attribute & Description
1. type : Indicates the type of input control and for checkbox input control it will be set to radio.

2. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

3. value : The value that will be used if the radio box is selected.

4. checked : Set to checked if you want to select it by default.

## Select Box Control
A select box, also called drop down box which provides option to list down various options in the form of drop down list, from where a user can select one or more options.


## Attributes
Following is the list of important attributes of `<select>` tag −

1. name : Used to give a name to the control which is sent to the server to be recognized and get the value.

2. size : This can be used to present a scrolling list box.

3. multiple : If set to "multiple" then allows a user to select multiple items from the menu.

### Following is the list of important attributes of <option> tag −

## Attribute

1. value : The value that will be used if an option in the select box box is selected.

2. selected : Specifies that this option should be the initially selected value when the page loads.

3. label : An alternative way of labeling options

## File Upload Box
If you want to allow a user to upload a file to your web site, you will need to use a file upload box, also known as a file select box. This is also created using the `<input>` element but type attribute is set to file.

Example
Here is example HTML code for a form with one file upload box −


## Attributes
Following is the list of important attributes of file upload box −
1. name : Used to give a name to the control which is sent to the server to be recognized and get the value.
 
2. accept : Specifies the types of files that the server accepts.

## Button Controls
There are various ways in HTML to create clickable buttons. You can also create a clickable button using `<input>`tag by setting its type attribute to button. 

The type attribute can take the following values −
1.	submit : This creates a button that automatically submits a form.

2. reset : This creates a button that automatically resets form controls to their initial values.

3. button : This creates a button that is used to trigger a client-side script when the user clicks that button.

4. image : This creates a clickable button but we can use an image as background of the button.


## Hidden Form Controls
Hidden form controls are used to hide data inside the page which later on can be pushed to the server. This control hides inside the code and does not appear on the actual page. For example, following hidden form is being used to keep current page number. When a user will click next page then the value of hidden control will be sent to the web server and there it will decide which page will be displayed next based on the passed current page.

![img](https://media.geeksforgeeks.org/wp-content/uploads/20190529105752/type.png)


## Summary FORMS

- Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
`<form>` element.
+ Information from a form is sent in name/value pairs.
- Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.
+ HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# Summary LISTS , TAB LES AND FORMS
+In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
- List markers can be given different appearances
using the list-style-type and list-style image
properties.
+ Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
+ Forms are easier to use if the form controls are
vertically aligned using CSS.
- Forms benefit from styles that make them feel more
interactive.


# Events
## What is an Event ?
JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

When the page loads, it is called an event. When the user clicks a button, that click too is an event. Other examples include events like pressing any key, closing a window, resizing a window, etc.

Developers can use these events to execute JavaScript coded responses, which cause buttons to close windows, messages to be displayed to users, data to be validated, and virtually any other type of response imaginable.

Events are a part of the Document Object Model (DOM) Level 3 and every HTML element contains a set of events which can trigger JavaScript Code.

Please go through this small tutorial for a better understanding HTML Event Reference. 

![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/Ways-of-Using-JavaScript-Events-1200x720.png)

## onclick Event Type
This is the most frequently used event type which occurs when a user clicks the left button of his mouse. You can put your validation, warning etc., against this event type.
 
## onsubmit Event Type
onsubmit is an event that occurs when you try to submit a form. You can put your form validation against this event type.

## onmouseover and onmouseout
These two event types will help you create nice effects with images or even with text as well. The onmouseover event triggers when you bring your mouse over any element and the onmouseout triggers when you move your mouse out from that element.

![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Event-Types.jpg)

## Summary Events 
- Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
+ Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
+ When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
+ You can use event delegation to monitor for events
that happen on all of the children of an element.
+ The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events.

