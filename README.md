# Focus-Blur
This example, as the text input gains and loses focus, feedback is shown to the user in the div element under the text input. The feedback is given using two functions. tipUsername() is triggered when the text input gains focus. It changes the class attribute of the element containing the message, and updates the contents of the element. checkUsername() is triggered when the text input loses focus. It adds a message and changes the class if the username is less than 5 characters; otherwise, it clears the message.

## Focus & Blur events

* The HTML elements you can interact with, such as links and form elements, can gain focus. These events fire when they gain or lose focus.
* If you can interact with HTML element, then it can gain and lose focus. You can also tab between the elements that can gain focus a technique often used by those with visual impairments.
* In older scripts, the focus and blur events were often used to change the appearance of an element as it gained focus, but now the CSS: focus psedo-class is a better solution unless you need to affect an element other than the one that gained focus.

## How to run the app?
* In your terminal type
```
git clone https://github.com/bostonhuman/focus-blur
```
* Open `focus-blur.html` to run the app.
