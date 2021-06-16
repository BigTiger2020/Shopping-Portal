* Title: Shopping Portal arbitrary file upload vulnerability
* Exploit Author: Thinkland Security Team
* Vendor Homepage:https://phpgurukul.com/shopping-portal-free-download/
* Software Link:https://phpgurukul.com/wp-content/uploads/2018/03/Online-Shopping-Portal-project.zip
* Version: 3.1
* Vulnerability verification
1. Enter username and password to log in
2. go to http://192.168.50.34/shopping/admin/update-image1.php?id=2,upload php file  
![image](https://github.com/BigTiger2020/Shopping-Portal/blob/main/1.png)  
3. Command execution  
![image](https://github.com/BigTiger2020/Shopping-Portal/blob/main/rce.png)  
