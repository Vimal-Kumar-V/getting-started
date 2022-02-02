                        
# Steps to  access code 
**1**:
*create a github account*  
**2**:
*Once account is created go to your account.Click your profile_image which is in top right corner.*   
**3**:
*Once clicked copy the webpage url which is your profile link.*  
**4**:
*Goto kissflow website and open chat*  
**5**:
*In chat search for vivekmadurai and send the copied profile link to him and ask him to give you code*.  
**6**:
*After getting access , join by [click here](https://github.com/OrangeScape/kissflow-xg/) and 
this link will redirect you to github where you can see **FORK** in top right corner.Click the fork button.*  
**7**:
Create a new folder with name as your wish in Documents .
It can done by opening terminal and typing the following command. 
      
      cd Documents
      mkdir kf
**8**:After creating folder navigate to that folder by typing.  

      cd Documents/kf
**9**:Then create a ssh clone by typing.  

      ssh-keygen -t ed22519 -C "(your github linked email address)"
      Then press return until you got the key which will start as "RSA" adn endswith your email address
**10**:*Copy the key and goto your github account*  
**11**:Click your **profile image** and goto **settings**.In settings search for **ssh and gpg keys**  
**12**:Click **SSH and GPG KEYS** and then click **new SSH keys** which is in top right corner below your profile image  
**13**:In **Title** section give title as your wish and **Paste the key in key section**.  
**14**:Go to the your repository and copy the git ssh  
&nbsp;&nbsp;To Copy git ssh:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i)Click the **CODE** button   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii)Select **SSH** in the drop down  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii)Copy the **Link**  
**15** To set your repo as origin 

 &nbsp;&nbsp; &nbsp;&nbsp;Open **Terminal** and type the following command
 
    git remote add origin "Paste the Link"
**16**:Go to the kissflow-xg repository and copy the git ssh  
&nbsp;&nbsp;To Copy git ssh:  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i)Click the **CODE** button   
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii)Select **SSH** in the drop down  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii)Copy the **Link**    

**17**:Open **Terminal** and clone the kissflow-xg  by   

    git remote add upstream "Paste the Link"
    git pull "Paste the Link"
    git fetch upstream
    git clone "Paste the Link" 
**18**:Open the cloned folder with pycharm and you can access the base code.  





 

      
     




          
