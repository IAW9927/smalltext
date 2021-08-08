
# Text editor for Windows in only ~2KB, able to run on Windows, FreeDOS
# 
# @echo off
# title SmallText v1.0 (please improve this program)
# echo ----------------------------------------------------------
# echo New File - NEWFILE
# set file=
# set ext=
# set /p file=What file to create ...
# set /p ext=Write extension... 
# echo You are in a command prompt text editor...
# echo BEGINNING OF FILE
# echo. >> %file%.%ext%
# :edit
# echo You can do 4 more lines before autosaving...
# set /p write_text=
# echo %write_text% >> %file%.%ext%
# set /p write_text1=
# echo %write_text1% >> %file%.%ext%
# set /p write_text2=
# echo %write_text2% >> %file%.%ext%
# set /p write_text3=
# echo %write_text3% >> %file%.%ext%
# 
# set /p write_text4=
# echo %write_text4% >> %file%.%ext%
# title Command Line Text Editor - %file%.%ext%
# goto :edit
# [Smallest Text Editor.zip](https://github.com/IAW9927/smalltext/files/6950703/Smallest.Text.Editor.zip)
# [Smallest Text Editor - MS-DOS version.zip](https://github.com/IAW9927/smalltext/files/6950710/Smallest.Text.Editor.-.MS-DOS.version.zip)
# Can you add features like new file, open file, and save file, and add features like Exit, Zoom In and Zoom Out, word wap, measurement units, Paste, Copy, Windows fonts, Print, page setup, and send in email, & ruler and status bar, font size, every feature in WordPad and Notepad (can be a GUI, must be a CMD (command prompt program) in Notepad, and the About Smallest Text Editor... dialog box, and shortcuts for doing stuff. to my program? Can you send me the source code you written to me? send it to me as a CMD file or code in comments...
