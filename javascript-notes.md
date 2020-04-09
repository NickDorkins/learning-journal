
**PROPERTIES**
- Properties describe characteristics of the current
web page (such as the title of the page).
**METHODS**
- Methods perform tasks associated with the document currently loaded in the browser (such as getting information from a specified element or adding new content).
**EVENTS**
- You can respond to events, such as a user clicking or
tapping on an element.

## Code from DO-ALONG
```
var today = new Date();
var hourNow = today.getHours(); 
var greeting;

if (hourNow > 18) {
    greeting= 'Good evening!';
} else if (hourNow > 12) { 
    greeting = ' Good afternoon!';
} else if (hourNow > 0) { 
    greeting = 'Good morni ng!';
} else {
    greeting = 'Welcome! ' ;
}
document.write( '<h3>' + greeting + '</ h3>');

```