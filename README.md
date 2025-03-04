# newsletter
Newsletter with Python on Excelsheet


Heylo! People have asked me how I do the newsletter sendout for music purposes -- I'm using this python code in combination with a spreadsheet listing people's names, mail addresses and all sorts of variables.
I've been trying to get this started to not be dependent on email servers like mailchimp. I'm also not claiming to own any of this, most of this code I combined from other websites to my liking and added some stuff -- that's why I thought of making this git, to have it applied to music and this specific beauty-mail I guess. 
I'm going to write some pro's and con's to see if you'd like to continue:

Pros: 
- Independency // autonomy
- Own database
- Fun with coding 8-)
- Free to adjust mail with all sorts of variables etc. you can go super crazy! :-P 

Cons:
- Some code experience, hassle to set-up with Server granting you authority to use third-party login/send-out (will go into more detail about this later)
- Time-consuming, lol
- Angry with coding when stuff fails >:-(
- Need to find a way still to make a cool automation of adding // deleting mails from excelsheet (thought of using g's App Script for Spreadsheets but would be happy to hear alternatives)

1.
Before you start you'll need to get python (I'm using Jupyter):
https://jupyter.org/install

2. 
once you have this you need to !pip install the different libraries i.e. smtplib and pandas

3.
You'll need to somehow grant access to your mail when you usually have a two-factor authentication. 
Example google:
https://support.google.com/a/answer/9003945?hl=en

4.
make sure you're having a spreadsheet with your contacts, make sure that you work with the right capitalization i.e. 'Email' and 'email' 

5.
Use the right paths in the script. i.e. I'm using "cover_image.jpg" because the image is in the same folder as my python code.

6. 
Check your email server for the right server // port

|||||

That should do the trick more or less -- if you're trying it out and run into issues you can contact me and I could try my best to help. I'm not the best with this either though and have only tried this using gmail // and some other servers, so I can't guarantee it may work for you.

XXXX LZRD
