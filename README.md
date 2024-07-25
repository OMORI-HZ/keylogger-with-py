# keylogger-with-py
simple keylogger using python for you lilbro🫡


Step-by-Step Guide
***Install pynput: If you haven't already installed the pynput library, you can do so using ```pip install pynput```***


Explanation:
Imports:

pynput.keyboard: Used for capturing keyboard events.
on_press Function:

This function is called whenever a key is pressed.
It tries to log the character representation of the key.
If the key doesn't have a character representation (like special keys), it logs the key name instead.
on_release Function:

This function is called whenever a key is released.
If the Esc key is released, it stops the listener by returning False.
Listener Block:

The keyboard.Listener is used to listen for keyboard events.
It calls the on_press and on_release functions for respective events.
The listener runs in a blocking call with listener.join() until stopped.

**!!!Notes:
Stopping the script: You can stop the script by pressing the Esc key.
File Location: The keystrokes will be logged to a file named keylog.txt in the same directory as the script.
Ethical Considerations: Always obtain explicit permission before running a keylogger on any system. Unauthorized use of keyloggers is illegal and unethical.
Disclaimer:
This example is provided for educational purposes only. Unauthorized use of keyloggers is illegal and unethical. Use this knowledge responsibly and always respect privacy and legal boundaries.**
