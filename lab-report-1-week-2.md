# Lab Report 1 - Oscar Martinez Angulo 
In this first lab report we learned how to log into our course specific account.

1. First thing you need to do is download VSCode [link](https://code.visualstudio.com/). ![image](/images/image3.png)

You download Vscode and then are prompted to this screen.![image](/images/image4.png)

2. Next what you do is connect you to a remote host, in this case the UCSD's remotes host.

First what you do is check if you have downloaded OpenSSH which will allow you to connect to the host [link](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse). 

Once downloaded you want to go into the termimnal VSCode and sign in using SSH. type ssh (username).ieng6.ucsd.edu in the terminal, then enter password. ![image](/images/image2.png)

3. Now that you have connect, try out different commands. try cd, cd~, ls, ls -lat, ect. I tried out cd, which basically changes the directory to where your files are on your computer or on the SSH. ![image](/images/image5.png)


4. To move files from and to the server, use SCP. first type scp (name of the file) (directory you want to move it to). It will wask you for your password and once you put it in you will be able to see the file transferred. ![image](/images/image1.png)

5. Now, if you don't want to keep typing your password everytime you try to enter into the SSH, you can set it up with a SSH key. In the terminal write ssh-keygen and press enter. Then set the directory to where you want to save your keygen. From that, enter all the options that pop up as default. Once the key is generated, copy the public key and transfer it by using scp to the remote directory. Now you can go into SSH without putting in your password everytime.(on the right side). ![image](/images/image6.png)

6. If you want to be more effecitve, you can put everything on a line of code. This made me run my code a little fast around 10 seconds faster.![image](/images/images/Screenshot%20(252).png)