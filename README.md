# DjangoVM
This repository contains a virtual image with Visual Code, Django and Python 3 for web development.
The VM works with VMWare, which you can download for free here: https://www.vmware.com/go/getplayer-win
The user name of the image is: Developer
The password of the image is: 123456

The image includes Visual Code with all the plugins required to run python & python 3. 
To set up your Git account using Visual Code do the following:
1. Create a new folder on your local computer
2. Open the folder and open a command terminal (CMD, PowerShell) if you have VSCode you can use the embeded terminal by clicking on the "Terminal" option on the tab menu on Top of the window or type " Ctrl + Shift + ~ "
5. In the command window type the following commands to set your name and e-mail with the following commands 
``` shell
  git --global user.name "GIT-USERNAME"
  git --global user.email "GIT-EMAIL"
```
3. Typethe following to clone this repository
```shell
  git clone http://repo
```
4. Open VMWare Player and navigate to where the repository was clonned
5. Open the vmlk file and wait for the image to boot
6. Log in
7. open VS Code 
8. Repeat the initial steps to set your Git account 
9. Clone your repository
10. Execute the following command to visualize your site
```shell
  python3 manage.py runserver
```
Have fun!!!

      
