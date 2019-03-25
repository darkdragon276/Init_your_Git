# Init_your_Git
Some necessary init your Git

## Add SSH key 
1. Get SSH key from local
```
$ sudo apt-get install openssh-client
$ ssh-keygen // enter 2 times
$ cat ~/.ssh/id_rsa.pub
```  
![Your SSH key like](asset/Add_SSH_key/ssh_key.png)  
2. Coppy SSH key to your setting  
- Open Your "setting" below your avartar on the top left of the site  
![Your setting](asset/Add_SSH_key/Your_setting.png)  
- Open "SSH key and GPGs key"  
- Click "New SSH key"  
![](asset/Add_SSH_key/newsshkey.png)  
- Coppy your key to the box
![](asset/Add_SSH_key/addsshkey.png)  
- Click "Add SSH key"  

Done

## Save your username and password

```
$ git config credential.helper store
$ git push origin master
Username for 'https://github.com': <your-username  
Password for 'https://darkdragon276@github.com': <your-password  
$ git pull  // for new password and user name
```
