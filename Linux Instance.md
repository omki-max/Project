## **1) How to create _EC-2_ (For Linux)?**

1) Click on **_Launch Instance_**

2) **Step 1:** Search for 
               
              >Amazon Linux 2 AMI (HVM), SSD Volume Type - ami-0323c3dd2da7fb37d (64-bit x86) / ami-0ce2e5b7d27317779 (64-bit Arm)
               
    in search box and then click on **Select**.
  
    ![](Image/Linux1.JPG)
 
3) **Step 2:** Click on check box of **_t2.micro_** instance type and then click on **Next:Configure Instance Details**.
 
    ![](Image/Linux2.JPG)
    
4) **Step 3:** **Configure Instance Details page**
 
      **Keep every field and check boxes on the page as it is and don't do any changes**\
      Click on **Next: Add Storage**.
    
    ![](Image/Linux3.JPG)
    
 5) **Step 4:** **Add Storage page** appears
                Increase the storage size to **30 GiB** and then click on **Next: Add Tags**
                
    ![](Image/Linux4.JPG)            
                
 6) **Step 5:** **Add Tags page**
 
       Click on **Add Tag** buton\
                Fill the fields like **Key**,**Value**
                Click on **Next: Configure Security Group**
                
    ![](Image/Linux5.JPG) 
    
 7) **Step 6:** **Configure Security Page** appears
 
       Fill the field names **Security group name**,**Description**
       Click on **Review and Launch**
                
    ![](Image/Linux6.JPG)
    
 8) Click on **Review and Launch**.
 
 9) **Step 7:** **Review Instance Launch** page appears
 
       Check all your filled details
       Then, Click on **Launch** button.
                  
    ![](Image/Linux7.JPG)
    
 10) **Step 8:** **Important Step**
 
        **A dialog box appears to select Key-Pair**
        Select **Create a new Key pair**
        Give **Key pair name**
        And **Don't forget to _Download Key Pair_**
        After downloading key pair Click on **Launch Instances**
                   
     <img src="Image/Linux8.JPG" width=500>
     
 11) Click on **View Instances** , Your Linux EC-2 instance is ready in Running state.   
           
                
                 
     
