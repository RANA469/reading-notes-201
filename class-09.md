< form > element is used to create an HTML form for user input.

## Types of form :

1.Adding Text

2.Making Choices

Submiting Forms

Uploading Files

Every < form > element requires an action attribute action attribute specifies where to send the form-data when a form is submitted.

Forms can be sent using one of two methods: get or post. attribute specifies how to send form-data

 element is used to create several different form controls.

## Type attribute it is a type of input like:

1-Text (it by default)

2-Password

3-Radio

4-Checkbox

5-Drop Down List Box < select>

6-Uploading file “ file “

7-Submit Button “ submit “

8-Image Button “ image “

9-Button & hidden Controls “ hidden “

10-Date

11-Email

12-URL

13-search



## name attribute is used to reference elements in a JavaScript, or to reference form data after a form is submitted.

### size attribute specifies the visible width in characters

### maxlength attribute specifies the maximum number of characters allowed

form validation it is a check if user input correct info or not.

list-style-type

Unordered Lists Types:

(none,disc,circle,square)

## Ordered Lists Types:

1.decimal:1 2 3
2.decimal-leading-zero:01 02 03
3.lower-alpha:a b c
4.upper-alpha:A B C
5.lower-roman:i. ii. iii.
6.upper-roman:I II III

## list-style-position
 ### property specifies the position of the list-item (bullet points).

## list-style-position:
 ### outside; means that the bullet points will be outside the list item.

## list-style-position: 
### inside; means that the bullet points will be inside the list item.

## list-style property 
### is a shorthand for this properties:

1-list-style-type

2-list-style-position

3-list-style-image

## Table

empty-cells property to display empty cells

border-spacing property sets the distance between the borders of adjacent cells.

border-collapse property to connect border line with each other

Styling Text Inputs its like any text

## Styling Submit Buttons :

(color,text-shadow,background-color)

:hover
cursor :

(auto,,crosshair,default,pointer,move,text,wait,help,url(link of cursor)

## UI EVENTS
 *Occur when a user interacts with the browser’s user interface (UI) rather than the web page like(load,unload,error,etc..)

## KEYBOARD EVENTS 
*when user use the keyboard like (keydown,key up , keypress,etc..)

## MOUSE EVENTS
 *when user use the mouse like (click,dblclick,mouseup,etc..)

if the event ocurred it named fired or raised.

trigger method triggers the specified event and the default behavior of an even for the selected elements.

### some example for the Event (input,change,submit,DOMSubtreeModified,DOMNodelnserted,blur / focusout ,etc..)

## Event handling :

1.Select t he element node(s) you want the script to respond to.(SELECT ELEMENT)

2.Indicate which event on the selected node(s) will trigger the response. (SPEC! FY EVENT)

3.State the code you want to run when the event occurs. (CALL CODE)

HTML EVENT HANDLER ATTRIBUTES its an older code and not usefull for now
![](https://res.cloudinary.com/hzxejch6p/image/upload/c_scale,w_300/v1502872464/capture-bubble_nbgmry.png)
element.onevent=functionName

EVENT LISTENERS can add many function at a time, its not compatible with old browser element .addEventlistener(‘event’, functionName [, Boolean]) ;

internet explorer did not support addEventListner().

Event flow it use to select element parents.

Event Object When an event occurs in HTML, the event belongs to a certain event object.

preventDefault() method cancels the event, meaning that the default action that belongs to the event will not occur.

The stopPropagation() method prevents propagation of the same event from being called.

THE this KEYWORD refers to the owner of a function.

W3C DOM EVENTS The DOM events specification is managed by the W3C (who also look after other specifications including HTML, CSS, and XML).

HTML5 EVENTS The HTMLS specification (that is still being developed) details events that browsers are expected to support that are specifically used with HTML.(input,submit,etc..)

BOM EVENTS Browser manufacturers also implement some events as part of their Browser Object Model (or BOM). Typically these are events not (yet) covered by W3C specifications (although some will be added to W3C specifications in the future).(touchstart,touchend,touchmove,etc..)

blur When an element loses focus, the b 1 ur event fires for that DOM node.

focus When an element gains focus, the focus event fires for that DOM node.

MOUSE EVENTS occured when the mouse move or click.event like(click,dblclick,etc..)
![](data:image/jpeg;base64,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)
## we can determine a mouse position.

KEYBOARD EVENTS event occured if using a keyboard.event like (input,keydown,keypress,etc..)

MUTATION EVENTS & OBSERVERS *event occured if there any change in structure like remove or add element.event like (DOMNodelnserted ,DOMNodeRemoved,etc..)

HTML5 Event its more popular and quickly. event like (DOMContentLoaded,hashchange and beforeun load)
