Go to the Visual Studio Code website https://code.visualstudio.com/, and follow the instructions to download and install it on your computer. 
 ![Image](1.png)

Once oppened
There is a first step you need if you’re on Windows: install git for Windows, which comes with some useful tools we need:

Git for Windows

Once installed, use the steps in this post to set your default terminal to use the newly-installed git bash in Visual Studio Code:

Using Bash on Windows in Vscode
Then going back to the vs code window.
press and hold Ctrl + ` to open the terminal.
Open the command palette using Ctrl + Shift + P.
Type - Select Default Profile
Select Git Bash from the options
Click on the + icon in the terminal window
The new terminal now will be a Git Bash terminal. Give it a few seconds to load Git Bash
 ![Image](2.png)
Now you can see different terminals on the right just like this, which you can navigate inbetween.
 ![Image](3.png)
 
Then just put in this command $ssh+ your class account to loging in, type in the password that pumps up in below. Then you will be logged into the application.



Here are some command code:
cd ~

cd

ls -lat

ls -a

ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the abc is one of the other group members’ username

cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/

cat /home/linux/ieng6/cs15lsp23/public/hello.txt

Here are the what those codes stand for:

"cd" which stands for "change directory" and allows you to change your current working directory.

"ls" which stands for "list" and shows you the contents of your current working directory.

"ls -a"shows you all the files and directories in your current working directory, including hidden files.

To copy the file "hello.txt" from the directory "/home/linux/ieng6/cs15lsp23/public/" to your home directory, you can use the "cp" command followed by the source and destination 

The tilde (~) symbol represents your home directory.

To view the contents of the file "hello.txt", you can use the "cat" command followed by the path to the file

Here I am running some of the command on my vscode:

 ![Image](4.png)
 ![Image](5.png)
 
 As you can see, here I first ran "cd" which means change my current working directory with a "~" stands for the home directory. So I first change my working directory to my home directory and print this working directory use the command "pwd". Then I ran "is -a" to  show all the files and directories in your current working directory, including hidden files.
 
 Please try few interesting command on your own! Feel free to reach out if you have any questions, happy coding!
