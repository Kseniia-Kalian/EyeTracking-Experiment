This software allows to use eye tracker as an input device to trigger the pop-up messages with the translation of certain predefined words in texts.

Before launching this software make sure that the eye tracker is connected to the computer, calibrated and functioning properly - otherwise it will not launch. This software was tested with Tobii 4C eye tracker, but it should also work with other models (not garanteed).

To launch it open file "1.lnk" and then file "2.lnk". If it does not launch - make sure that "Target" field and "Start in" field in the "Shortcut" tab in the Properties of each ".lnk" file contain correct information (it depends on the location where those files are on your computer).

You may also need to edit ".py" files in the folder "Python files" and make sure that informatino there is also correct. You need Python for it to work.

To add or change texts or to add or change interactive words in texts - go to "Python files" folder and edit:
- "textNUMBER heading.txt" - to change the heading of the corresponding text.
- "textNUMBER special words.txt" - to change the interactive words (those that trigger the appearance of a pop-up window when you hover a mouse corse over it) and to change what should be displayed in the pop-up window for each such word. 
- "textNUMBER.txt" - to edit the text itself. 
File names contain actual number (like 1, 2, 3, etc.) instead of "NUMBER".
New texts can be addded by creating new files with subsequent numbers (3 files for each text as described above).

Settings: 
- "Gaze activation time" - it determines how soon the pop-up window should appear when you are looking at the interactive word or when you hover a mouse over it. By default it is set at 0.5 seconds, but it can be changed by pressing "Increase" or "Decrease" buttons.
This software was used in "Efficiency of ‘Gaze-controlled translation’ vs conventional approaches to education in the sphere of teaching foreign languages: a comparative analysis" master's thesis written by Kseniia Kalian.
