### A Mac Keylayout for Arabic language which maps latin sounds to their Arabic equivalent

To install it simply copy the "ArabicAzerty.keylayout" file in /System/Library/Keyboard Layouts/ directory.

Then restart your finder (Force quit, then Relaunch on Finder process).

Then go to Keyboard menu in System preference pane and add Others/ArabicAzerty as the keyboard layouts list. It should be located in the region name "Others".

    sudo cp "ArabicAzerty.keylayout"  "/Library/Keyboard Layouts/"

This keyboard layout relies on a simple principle: Each letter that sounds like its equivalent in latin is mapped to a azerty key:
- س -> s
- ص -> c
- ك -> k
- ق -> q
etc...

Then, each arabic letter which have a similar letter with lesser or more diacryphes (points) will be accessible using SHIFT + the letter:
- س -> s => ش -> SHIFT+s
- د -> d => ذ -> SHIFT+d
- ح -> j => خ -> SHIFT+j => ج -> ALT+j

For other ambigous keys, you can use the Show Keyboard Feature to discover them. 


بسم الله!!!!
