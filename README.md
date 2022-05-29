# MsgBox Generator
 https://discord.gg/jKjzG5YjGD

# Why was it made
 Well, a lot of people do not know how to program, or create MsgBox then i dicided to make this script to help this type of people

# How it works?
 It is a little bit hard to understand it but i will try to show how it works

# Account System
 * User :
 ```
 :nm
 [...]=What is the account name? 
 if %name% equ Example goto pass
 if %name% equ * goto wrong
 
 :wrong
 cls
 echo Wrong Info!
 pause >nul
 cls
 goto nm
 ```
 * Pass :
 
 ```
 [...]=What is the password?
 [...]
 ```
 * Main :
 ```
 :main
 cls
 [...]= What is the MsgBox title? : 
 cls
 goto 2
 
 :2
 cls
 [...]= What is the MsgBox content? : 
 cls
 goto nb
 
 :nb
 cls
 echo What type of MsgBox do you want?
 echo 1) OK button only
 echo 2) OK and Cancel buttons
 echo 3) Abort, Retry, and Ignore buttons
 echo 4) Yes, No, and Cancel buttons
 echo 5) Yes and No buttons
 echo 6) Retry and Cancel buttons
 echo 777) System modal (all applications wont work until the user responds to the message box)

 [...]=Which one do you want? : 
 [...]
 ```
 Generator :
 
 ```
 :m1/m2/m3/m4/m5...
 echo Here is the script :
 echo [...]
 echo.
 echo Now just copy this script, if you press any button, it will open a menu for you paste the script in it. When you paste it, just press F6. The file will be saved  in the "files" folder
 echo By the way, if you do this process again, change the saved file (only if you want to create another one)
 PAUSE >nul
 cls
 [...]
 cls
 [...]
 cls
 goto main
 ```
 * [...] = Censured Script
# Why would you use
 * Create Pop-Ups
 * Create TikTok videos
 * Send it to your friends
# Download Link
 https://cdn.discordapp.com/attachments/980127861371449436/980327251679797279/MessageBoxGen.zip
 
# Tutorial
 https://streamable.com/f8i0vd
