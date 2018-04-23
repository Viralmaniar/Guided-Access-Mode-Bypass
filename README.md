# Guided-Access-Mode-Bypass
This write-up will provide detailed description on how to bypass Guided Access mode on Apple iPhones. 

# You can use Guided Access to:

- Temporarily restrict your iOS device to a single app
- Disable areas of the screen that aren’t relevant to a task, or areas where an accidental gesture might cause a distraction
- Disable the hardware buttons

# End a Guided Access session
- Press the Home button once.
    - Use Touch ID.
    - If you're not using Touch ID on your device, follow these steps to end a Guided Access session:

- Triple-click the Home button.
  - Enter the Guided Access passcode.

You can read more about this in here: https://support.apple.com/en-au/HT202612

# Step by step guide to Enable Guided Access Mode

- https://www.imore.com/how-use-guided-access-iphone-and-ipad

# Few articles talk about security of guided access mode or kiosk mode
There are numerous articles online, which talks about how Guided Access Mode security allows you to handover your phone to someone without worrying about them to get out of the app and read your messages or look into your private photos.

1) How to use Guided Access to secure your iPad or iPhone: 
https://www.computerworld.com/article/3162738/apple-ios/how-to-use-guided-access-to-secure-your-ipad-or-iphone.html

2) How to Use Guided Access Feature to Secure Your iPhone: 
http://www.tweaklibrary.com/2017/07/06/how-to-use-guided-access-feature-to-secure-your-iphone/

3) How to Use Guided Access for Security Reasons: 
https://snapguide.com/guides/use-guided-access-for-security-reasons/

4) How to Put an iPad Into “Kiosk” Mode, Restricting It to a Single App:
https://www.howtogeek.com/252670/how-to-put-an-ipad-into-kiosk-mode-restricting-it-to-a-single-app/

# Risk
- User privacy
- Data leakage
- False sense of security while using Guided Access mode

# Steps to reproduce:

Please follow the steps to break out of the Guided Access mode and see users text messages, photos, notes and reminders.

1)  Go to settings and turn on the Guided Access feature <br>
![image](https://user-images.githubusercontent.com/3501170/39089917-8d8c3616-4614-11e8-9481-33c64389dd4a.png)

2) It allows user to set the passcode. Set the passcode so that user cannot disable the feature and snoop into other application.<br>
![image](https://user-images.githubusercontent.com/3501170/39089927-dbc1b874-4614-11e8-99c7-29764e101d3b.png)

3) Open Safari Browser on the device and press the home button thrice to put the phone into <B><I>Guided Access Mode or Kiosk Mode</I></B>. Here the user assumes that one should not be able to read or use other applications on the phone as the phone is in Guided Access mode. <br>

![image](https://user-images.githubusercontent.com/3501170/39089937-2f67aaec-4615-11e8-9d18-4009f05b4274.png)

4) Try to call the application directly from the URL using hard links. <Br>
- To open: Mail type: message:// <Br>
- To open: Messages type: sms:// <Br>
![image](https://user-images.githubusercontent.com/3501170/39090144-379786b0-461a-11e8-8963-6ac92ff35dac.png) <Br>
    
5) User gets the warning message saying that the “Guided Access is enabled. Triple-click the home button or use Touch ID to exit”. Basically, at this point of time user can’t access the message application and hence can’t read any text messages on the device.<br>

![image](https://user-images.githubusercontent.com/3501170/39090201-c1485ffa-461b-11e8-834b-87d98967b12e.png)

6) On clicking the home button thrice user needs to put the PIN to access other applications on the phone.<br>

![image](https://user-images.githubusercontent.com/3501170/39090210-01582d00-461c-11e8-9f7b-f75a467bd58b.png)

7) Now, click on the share option in the Safari Browser to see where can we share the Browser link.<br>

![image](https://user-images.githubusercontent.com/3501170/39090285-7b6aeac2-461e-11e8-919e-be5d18a57699.png)

8) Click on the Message icon<br>
![image](https://user-images.githubusercontent.com/3501170/39090220-3fb985a8-461c-11e8-98da-132bf8ec25cc.png)

9) It opens the Message application inside Guided Access mode. Now click on the ⊕ button to see the contact details.<br>
![image](https://user-images.githubusercontent.com/3501170/39090223-618862e4-461c-11e8-8e2f-79ebab5040b6.png)

10) Choose the individual contact from the contacts and one can read all the text messages between 2 parties even though one is using Guided Access mode.<br>
![image](https://user-images.githubusercontent.com/3501170/39090235-c0f58fb8-461c-11e8-841e-1d5b361a2161.png)

11) Same goes for the other applications. Share the link from Browser with Notes or Reminders application to get access to sensitive information from those applications.<br>

![image](https://user-images.githubusercontent.com/3501170/39090258-7a38afb4-461d-11e8-801c-8cacd93fe5db.png)

12) Going into Photos is bit tricky from the Browser, however, it's not impossible.
- After clicking on the ⊕ button and choosing the contact name long press on the contact name from the messaging application. <br>
![image](https://user-images.githubusercontent.com/3501170/39128185-793f02c4-474a-11e8-827c-31e35bc81bc6.png)

- This opens the contact application with edit option as shown below <br>
![image](https://user-images.githubusercontent.com/3501170/39128529-5a50c752-474b-11e8-82ea-659fda762201.png)

- Click on edit button allows a user to upload a photo for a contact.
![image](https://user-images.githubusercontent.com/3501170/39129462-e4795370-474d-11e8-8f31-bdc3fe17a873.png)

- Click on "Choose Photo" option which will open photo album of a user.
![image](https://user-images.githubusercontent.com/3501170/39129666-67471d28-474e-11e8-8fba-5df3601c7d38.png)

- User gets full access to photo album from Guided Access Mode
![image](https://user-images.githubusercontent.com/3501170/39129812-c7abdd02-474e-11e8-9140-300bdecffc1f.png)

13) While browsing to other non-iOS applications, Apple check for Guide Access Mode and doesn't allow one to look into that application.
For eg: using share from Safari to read Whatsapp or Gmail messages.

I hope you find this information useful. If you have any questions, ideas or suggestions - just tweet me on [@ManiarViral](https://twitter.com/maniarviral)

Happy hunting!



