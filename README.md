# hardlinks
Created this programme thing to make the hardlinking process faster for me (I do it quite often).

The .bat takes one argument: the file being hardlinked.
If a file is supplied, then it will ask for the target root folder of the new hardlink.
If a file with the same name already exists in the target root folder, then it will be replaced.
Both the source file and target root folder must be located on the same drive.
This will continue until either the command prompt is closed or the ENTER button is pressed without an input.

A shortcut can be created for this .bat file with the target:
      
    C:\Windows\System32\cmd.exe /c start /b <PATH_TO_BAT_FILE> 2>&1
