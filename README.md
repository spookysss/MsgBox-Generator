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
 set /p name=What is the account name? 
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
 set /p ps=What is the password?
 if %ps% equ * goto wrong2
 if %ps% equ Example goto main
 ```
 * Main :
 ```
 :main
 cls
 set /p tl= What is the MsgBox title? : 
 cls
 goto 2
 
 :2
 cls
 set /p ct= What is the MsgBox content? : 
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
 echo 7) Critical Message icon
 echo 8) Warning Query icon
 echo 9) Warning Message icon
 echo 10) Information Message icon
 echo 11) System modal (all applications wont work until the user responds to the message box)

 set /p mi=Which one do you want? : 
 if %mi% equ 1 goto m1
 if %mi% equ 2 goto m2
 if %mi% equ 3 goto m3
 if %mi% equ 4 goto m4
 if %mi% equ 5 goto m5
 if %mi% equ 6 goto m6
 if %mi% equ 7 goto m7
 if %mi% equ 8 goto m8
 if %mi% equ 9 goto m9
 if %mi% equ 10 goto m10
 if %mi% equ 11 goto m14
 ```
 Generator :
 
 ```
 :m1/m2/m3/m4/m5...
 echo Here is the script :
 echo spookyssmsgbox=msgbox("%ct%" ,0, "%tl%")
 echo.
 echo Now just copy this script, if you press any button, it will open a menu for you paste the script in it. When you paste it, just press F6. The file will be saved  in the "files" folder
 echo By the way, if you do this process again, change the saved file (only if you want to create another one)
 PAUSE >nul
 cls
 cd files
 cls
 copy con msg.vbs
 cls
 goto menu
 ```
# Why would you use
 * Create Pop-Ups
 * Create TikTok videos
 * Send it to your friends
# Download Link
 
