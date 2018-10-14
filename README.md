### A Mac Keylayout for Arabic language which maps latin sounds to their Arabic equivalent

To install it simply copy the "ArabicAzerty.keylayout" and "ArabicAzerty.icns" files in /System/Library/Keyboard Layouts/ directory.

    REPO=https://raw.githubusercontent.com/akram/arabic-azerty-keylayout/master/
    wget $REPO/ArabicAzerty.keylayout
    wget $REPO/ArabicAzerty.icns
    sudo cp "ArabicAzerty.*"  /Library/Keyboard Layouts/

Then restart finder (Force quit, then Relaunch on Finder process).

Then go to Keyboard menu in System preference pane and add Others/ArabicAzerty as the keyboard layouts list. It should be located in the region name "Others".

This keyboard layout relies on a simple principle: Each letter that sounds like its equivalent in latin is mapped to an azerty key:
- س -> s
- ص -> c
- ك -> k
- ق -> q
etc...

Then, each arabic letter which have a similar letter with lesser or more diacryphes (points) will be accessible using SHIFT + the letter:
- س -> s => ش -> SHIFT+s
- د -> d => ذ -> SHIFT+d
- ح -> j => خ -> SHIFT+j => ج -> ALT+j

For other ambiguous keys, you can use the Show Keyboard Feature to discover them. 


بسم الله!!!!
