**1**.Open **Kissflow-xg** folder  in pycharm.  
**2**.Search for **docker-compose-mock.yml** file and open the file.  
**3**.After opening the file search for &nbsp;**mongo-service** in the file and uncomment lines below mongo-service till the line with same indentation level spotted  
&nbsp;&nbsp;*NOTE*:For mac m1 chip,under mongo-services include the following command for successful exexcution 

        platform:linux/amd64
**4**.Then search for **reddis-service** and in the file and uncomment lines below reddis-service till the line with same indentation level spotted.  
**5**.Then find the **admin** directory and set it as a Sources Root.  

&nbsp;&nbsp;&nbsp;**To set directory as a Sources Root**

        i)Right click the directory
        ii)Click "Mark directory as " which is last in dropdown
        iii)Click Sources Root
**6**.Under **Admin** directory find **tests** directory and run the directory  

&nbsp;&nbsp;&nbsp;**To run a *test* directory**

        i)Right click the tests directory
        ii)Click "Run  python tests in test.."
               (OR)
       i)Click the tests directory and press control+shift+R
