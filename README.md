# Chatbot build using python
## The workflow of the project
Import the Tkinter library and create a new root window using the Tk() function.

Set the title of the root window to "Chatbot" using the title() function.

Define a function named "send" which will be called when the user clicks on the "Send" button.

In the "send" function, get the text entered by the user in the Entry widget using the get() method and concatenate it with the string "You -> ".

Insert this concatenated string into the Text widget using the insert() method and the END constant to specify the insertion point.

Convert the user input to lowercase and compare it with different predefined phrases such as "hello", "hi", "how are you", etc.

Depending on the user input, insert an appropriate response from the chatbot into the Text widget.

Clear the Entry widget using the delete() method and the range from 0 to the END constant.

Create a new Text widget and place it in the root window using the grid() method, specifying the row, column, and columnspan.

Create a new Entry widget and place it in the root window below the Text widget using the grid() method, specifying the row and column.

Create a new Button widget labeled "Send" and place it in the root window next to the Entry widget using the grid() method, specifying the row and column and the command parameter to call the "send" function.

Start the main event loop using the mainloop() method, which waits for events such as button clicks or keypresses and handles them accordingly.

** Finaly, When the user enters a message and clicks the "Send" button, the chatbot checks for specific phrases and responds accordingly. The conversation is displayed in the Text widget in a simple format of "You -> message" and "Bot -> message".**
