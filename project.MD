Project



Do something when the user clicks the buy now button. If the user has not entered anything, a message will appear telling them to enter a name.

If a word has been entered, let the user know if the count is available.

Create a new javascript file called buy_now.js (you will be working inside this file).
Create an arrow function called **buyNow**
In the function, check if the input field is empty; if it is, print a message asking the user to input letters.
In the function, check if the input field value is equal to the default text (eg: **input === ‘YOUR NAME’**) , if it is; print a message asking the user to enter their custom letters.
Print a success message if the user enters a unique letter.
If letter length is greater than 15, tell the user that they exceeded the number of available letters.
Finally, set a **click** event for the buy now button by also calling the buyNow function.