# Caps Lock Delay Remover
One of the things that drove me crazy about MacOS was that caps lock does not turn on when you hit it quickly for the first time.  You either have to hit it multiple times or hold it down.  As described in the second answer [here](https://apple.stackexchange.com/questions/81234/how-to-remove-caps-lock-delay-on-apple-macbook-pro-aluminum-keyboard), if you simply set the caps lock key to have no action and set it to have the normal caps lock action, it will work as I expect (pressing it just once turns it on and off).  To make this easier, I wrote an apple script to automatically do this when I log in.

## Setup
To use this script, you will need to create an application with the code in the caps_lock_delay_remover.txt file.

**STEP 0:** Clone or download this repository.

**STEP 1:** Create an Application from caps_lock_delay_remover.txt:
- Open Script Editor (the default script editor on Mac) or a script editor editor of your choice and open caps_lock_delay_remover.txt in a text editor of your choice.
- Copy the text from caps_lock_delay_remover.txt and paste it into Script Editor.
- Click **Save** and move on to step two.

**STEP 2:** Save the Application
- In the **File Format** menu, select **Application**.
- Change any settings as desired (there is more information about what these settings mean in this [engadget article](https://www.engadget.com/2008/01/13/applescript-saving-scripts/)).
- Save the application and you're good to go!

## Usage
I run this script on start-up so that my caps lock key works as expected.
