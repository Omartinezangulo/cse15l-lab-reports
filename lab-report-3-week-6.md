# lab-report-3

## 1st choice, Streamline ssh Configration 

Something that is common when you log in is you havew to type your whole ```ssh Username``` when trying to get into the server. You don't have to do that now! All you have to do is 
follow these steps.

1. First you want to go on to the terminal go back into your directory untill you get to users directory.then you want to type ``` cd .ssh```.![image](/images/Screenshot344.png)
2. After you want to type the comand ```~/.ssh/config```.![image](/images/Screenshot345.png)This will prompt you to a screen to where you can put in the host name and your username. In User put your username that starts with ```cs15lsp22zzz```.![image](/images/Screenshot346.png) 
3. Finally try the command ```ssh ieng6``` which should automaticallysign you in into your account.  ![image](/images/Screenshot347.png)
4. This is me copying a file using my ssh coinfiguration.![image](/images/Screenshot352.png)


## 2nd choice, Set up Github Access from ieng6 
1. This is my public key in my github.![image](/images/Screenshot355.png)
2. This is my private key to access it. ![image](/images/Screenshot356.png) 
3. This is me using github commands and pushing it. ![image](/images/Screenshot361.png) And here is the link [link.](https://github.com/Omartinezangulo/markdown-parser/commit/53382e3b07165c766617858580251fb447d21a01)

## 3rd choice, Copy Whole Directories with ```scp -r```

Copying everything down to a directory is alot of work. But now we can avoid this with just a simple command.

1. You want to type ```$ scp -r . cs15lsp22@ieng6.ucsd.edu:~/markdown-parse``` which lets you copy all your files to your account on the server. ![image](/images/Screenshot349.png)
2. Then you can re sign in and you can open it up and see that all your files are in there. ![image](/images/Screenshot348.png)
3. This is an example of what you can do once in your account. I was able to complie and run tests in the terminal. ![image](/images/Screenshot353.png)
4. This is me running multiple commands at once.![image](/images/Screenshot360.png)