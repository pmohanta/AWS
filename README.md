Install Visual Studio Code : https://code.visualstudio.com/download 
Install Node.js(6.10) : https://nodejs.org/en/blog/release/v6.10.2/
Open Command Prompt
1) Check node.js and npm version by a) node -v and b)npm -v

Create development folder e.g. C:\Palash\Development\NodeLambda
Go to folder : cd C:\Palash\Development\NodeLambda
Install serverless : Run command : npm i serverless -g 
Install Git : (Git-2.11.0-64-bit.exe)
Open Git command prompt
Run 
git config --global user.email "you@example.com"
  
git config --global user.name "Your Name"

Run Visual Studio code
Click on link "Clone from Git repository"

In browser go to git url: https://github.com/pmohanta/AWS
Find dropdown "Clone or download" and expand
Copy url e.g. https://github.com/pmohanta/AWS.git

Paste in Visual Studio Code for Repository URL
Choose dev folder e.g. C:\Palash\Development\NodeLambda

Follow on screen instructions in Visual studio Code

Try Checking Commit , Push, Pull to see if git is working on or not. 
-----------------------------------------------------------------------------
install serverless in command prompt : npm i serverless -g 
install aws in command prompt : npm i aws -g

Go to credentials file e.g (C:\Users\Administrator\.aws\credentials) [Note: The dot before aws and credentials has no extension] and save your 
aws credentials in that file like 

[default]
aws_access_key_id = Your access key
aws_secret_access_key = Your secret access key
-----------------------------------------------------------------------------
