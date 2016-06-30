# NewTerminal
This is an AppleScript file that can be rolled into an app. so that it is easier to open a new terminal window in the current desktop on Mac OSX.

## Setup
There are **two options** for setting up this app.  You can either create the application from newterminal.txt or from newterminal.scpt, which is a compiled, AppleScript file.  Creating it from newterminal.txt is more secure because you know for sure what code is running in the application.

**STEP 0:** Clone or download this repository.

**STEP 1, *Option A*:** Creating an Application from newterminal.txt
- Open Script Editor (the default script editor on Mac) or a script editor editor of your choice and open newterminal.txt in a text editor of your choice.
- Copy the text from newterminal.txt and paste it into Script Editor.
- Click **Save** and follow the instructions in the **STEP 2: Saving the Application** section.

**STEP 1, *Option B*:** Creating an Application from newterminal.scpt
- Open the newterminal.scpt in Script Editor (the default script editor on Mac) or a script editor of your choice.
- In Script Editor, go to **File > Export** and follow the instructions in the **STEP 2: Saving the Application** section.

**STEP 2:** Saving the Application
- In the **File Format** menu, select **Application**.
- Change any settings as desired (there is more information about what these settings mean in this [engadget article](https://www.engadget.com/2008/01/13/applescript-saving-scripts/)).
- Save the application and you're good to go!

## Usage
Once you have packaged the script as an app, I like to use spotlight search (⌘ + Space) to quickly bring up a new terminal window in the current desktop (just type ⌘ + Space, start to type "newterminal" and hit enter once the newterminal application comes up).
