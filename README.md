# Anti-Phishing Tool #

# How to use #

*  1: Download the [Anti-Phisher.zip](/EwyBoy/Anti-Phishing-Tool/archive/master.zip)
*  2: Run the Anti-Phisher Tool, but don't type anything yet.
*(Make sure to run the exe inside the default folder it came with)
*  3: Now find a phisher website. I found one in my e-mail that looks like this:
![](https://i.imgur.com/W5y3439.jpg)
*  4: Click the link to the phisher website. Even if the websites look totaly legit you can often spot it by their URL.
![](https://i.imgur.com/1V85Qdu.jpg)
*  5: Once we are on a phisher website, hit F12 in Google Chrome.
*  6: Navigate to the "Network" tab and make sure to click the Preserve log button.
![](https://i.imgur.com/mGyZ7GT.jpg)
*  7: Fill in a fake email adress and password as seen above. **DO NOT YOU A REAL EMAIL OR PASSWORD**
*  8: Hit login and look for suspicious files. I found this named *addLogin.php*
![](https://i.imgur.com/vNxUbfp.jpg)
*  9: Click the file once to view the header content.
*  10: At the top of this file, find the "Request URL"
![](https://i.imgur.com/IeCJ5lJ.jpg)
*  11: Copy this URL and paste it into the URL input in the Anti-Pisher Tool command line window.
*  12: Scroll down to the bottom of the header content page until you see the "Form Data" section.
![](https://i.imgur.com/CTOVjxS.jpg)
*  13: Copy everything from the text before the ":" **NOT THE EMAIL YOU WROTE**
*(this can be everything from login_email to 424fg23gfg4gfh23ggv32 depending on their code)*
*  14: Paste this string into the input in the Anti-Pisher Tool command line window.
*  15: Now do the same for the password section. Same rules as above applies.
*  16: Hit enter and if you command line keeps going like this, you have done everything correct;
![](https://i.imgur.com/Pcf5uX1.jpg)
