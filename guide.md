#Python IDLE Theme Guide for Beginners (Windows)

Here's a <a href="https://raw.githubusercontent.com/Xkr1ptikX/images/master/new%20highlighting.png"  target="_blank">Preview</a> of the end product.

###**Disclaimer**: 
- I am writing this guide based on my own experiences on a Windows 7 machine.
- For the preparation of this guide I used Python 3.4, I haven't tested this method on any other versions. 
- Also I used someone else's configuration settings found <a href="https://github.com/naschorr/neon-night-idle-theme" target="_blank">here</a>. So credit goes to <a href="https://github.com/naschorr" target="_blank">naschorr</a>. 

###What You'll Need
* Python installed
* A text editor, notepad will suffice

###Preparations
- Go ahead and locate the following file in the following directory.
    - Directory: **C:\Python34\Lib\idlelib** 
        - this is the default install location
    - File name: **config-highlight.def** 
        - if you look at the **Type** column you'll notice the file is an **Export Definition File**
- Keep the location of this file handy.
- Also make a backup of this file.
    - I just copied/pasted it to my desktop and renamed it **config-highlight (original)**

###Instructions
- open IDLE (Python GUI)
- click **Options -> Configure IDLE...**
- select the **Highlighting** tab
- click **Save as New Custom Theme**
- type in the exact name of the theme to be used
    - in my case **IDLE Neon Night**
- click Ok on the current window and click Ok on the IDLE Preferences window
- close IDLE (Python GUI)
- open the file we located in the Preparations section named **config-highlight.def** in a text editor, scroll to the bottom add a space
    - copy these <a href="https://github.com/naschorr/neon-night-idle-theme/blob/master/config-highlight.cfg" target="_blank">settings</a> and paste them at the end of the **config-highlight.def** file
        - here's a <a href="https://raw.githubusercontent.com/Xkr1ptikX/images/master/editing%20.def%20file.png"  target="_blank">visual reference</a> 
- save **config-highlight.def**
- open IDLE (Python GUI)
 
###*Enjoy!*
