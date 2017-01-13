# xojo-RestrictedComboBox
A ComboBox where you can only type something that corresponds with the list

The ComboBox updates it contents if you type something that is a match within the list. This subclass can be used as a drop in. Only the AddRows is NOT useable as I needed it and made it protected.

I added a Test project that adds 100.000 rows and it seems fast enough. I tested with 1.000.000 and it was too slow.

Known issues:

-When typing a backspace, it always deletes the last character. That is ofcourse not always the case.
-Getting the current selected text etc is not working

This is meant as a sample, I will update it when I have some time to work on it.

License: Do whatever you want with it.
