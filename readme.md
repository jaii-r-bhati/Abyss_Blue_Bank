## Features
- Secure login and signup system with md5 encryption
- OTP verification 
- Two Step verification with google authenticator
- Admin & user panel
- Withdraw and deposit section
- Money transfer system
- KYC verification
- Email alerts after every transaction
- Saving page
- Request debit card 


## Steps to run Project 
(1) Xampp Installation
(2) Code Edit Steps  
1. Copy Abyss_Blue_Bank Project Folder And Paste in htdocs folder (htdocs found in xampp Setup)  
1. Copy Abyss_Blue_Bank Project Folder And Paste in htdocs folder (htdocs found in xampp Setup)  
2. Open Abyss_Blue_Bank Folder With VScode or other editor   
3. Create app password in google and copy it (follow the video tutorial -> how to make app password [video link -> https://youtu.be/J4CtP1MBtOE] )  
4. Now Open config.php file which is in root directory     
5. Now Save File
6. Setup Database  
    1] Run xampp.exe  
    2] Start Apache then start mysql  
    3] click on Admin botton in front of mysql OR  type this url in browser (http://localhost/phpmyadmin/)  
    4] Create New Database With The Same Name of (Abyss_Blue_Bank)  
    5] click on import tab  
    6] click on Choose File Button and Select Database file from Project Folder Location : Abyss_Blue_Bank > database > Abyss_Blue_Bank.sql  
    7] click on go Button   


7. now start project with this link (http://localhost/Abyss_Blue_Bank/)  
8. Create Account  
9. To Make Admin Account follow the step given Below  
    1] Create Normal User Account  
    2] Go to mysql Database   
    3] Open login tabel  
    4] to edit any value in database just double click on it. So double click on Status.  
    5] repalce value in the status coloumn with "Super" and in State = 1   
    Note: Without Admin Account User Account Cannot Activate  

11. Now Make User Account. Then Login to Admin Account > click on menue > select Verify Accounts > Click On Verify Button to activate user account
12. Now login As User    
