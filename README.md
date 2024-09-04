# WHAT IS IAM

1. IAM is stands for (Identity and Access management)
2. Identity is authentication it means credintials like user id and password to login the AWS account but we don't have access to operate the services in aws account
3. Access is authorization it means permissions we can operate the specific services only in AWS acount
4. For IAM user having restrictions for using of AWS services
# FEATURES OF IAM
1. You can share your AWS account to others without giving them your credentials
2. You can give permission for users but restrict them to read only access for ec2 service then the user can read only he can't able to write and change the ec2 service
# IAM ARCHITECTURE
 ![architecture](https://github.com/user-attachments/assets/4ba8f76e-23a9-48ca-8942-89449af73a6b)
# STEPS TO CREATE IDENTITY OR AUTHENTICATION IN IAM
 1. Go to AWS console and sign-in as root user
 2. Search IAM service in search bar and select the IAM
 3. it will take you to IAM dash board
 4. Click on user and create one user
 5. Give the user name as shown in below figure
    ![user](https://github.com/user-attachments/assets/ca28734a-d0f9-4364-9ee2-bbd40399a49c)
 6. Select the provide user access to the AWS management console option as shown in below figure
    
    ![user1 5](https://github.com/user-attachments/assets/a6dcbd88-8f9d-4848-a846-80ff18fe5ca2)
 7. Select i want to create an iam user option
    
    1. Select auto generated password option in console passord
    2. Select user must create a new password option it is optinal as shown in below figure 
    ![user2](https://github.com/user-attachments/assets/05385e2d-cfa5-4d71-b24a-7855426d3f59)
 8. click on next option
 9. Select the add user to group in permissions options as shown in below figure
     
    ![user3](https://github.com/user-attachments/assets/22a61432-eb5a-48ce-904e-244552734eb9)
10. Click on next and click on create user
11. You can see console sign-in details

    1. copy the console sign-in URL or click on download .csv file as shown in below figure
       ![user4](https://github.com/user-attachments/assets/4aa1e5ac-391d-49d6-8fca-3934140aeee4)
12. Paste the copied url on new web page
13. It will take you to sign-in console of IAM

    1. Enter the user name and copied password as shown in below figure
       ![user5](https://github.com/user-attachments/assets/cad4d186-0479-47b6-8c4a-e1c86eb82c2f)
14. We enter into the AWS account with only authentication but we don't have any permissions to access services as shown in below figure
    
    ![user7](https://github.com/user-attachments/assets/79782ae0-649c-4a98-aca6-ed7217b2fbe6)
__________________________________________________________________________________________________________________________________________________________________________________
# STEPS TO CREATE ACCESS OR AUTHORIZATION IN IAM
 1. Go to AWS console and sign-in as root user
 2. Search IAM service in search bar and select the IAM
 3. it will take you to IAM dash board
 4. Click on user and create one user
 5. Give the user name as shown in below figure
    ![use2](https://github.com/user-attachments/assets/7a3e6369-ccdc-4dfb-a6b6-803e44dbe258)
 6. Select the provide user access to the AWS management console option as shown in below figure
    
    ![user1 5](https://github.com/user-attachments/assets/13bb81c7-2f60-4a84-89b3-45f071f213b8)
 7. Select i want to create an iam user option
    
    1. Select auto generated password option in console passord
    2. Select user must create a new password option it is optinal as shown in below figure    
       ![user2](https://github.com/user-attachments/assets/05385e2d-cfa5-4d71-b24a-7855426d3f59)
  8. click on next option
  9. Select attach policies directly option in permissions options as shown in below figure
      
      1. I select ec2full access it means giving permissions to ec2 services only

         ![use7](https://github.com/user-attachments/assets/81b62028-6745-42d2-8928-bbf51bec3c7d)

  10. Click on next and click on create user
  11. You can see console sign-in details

      1. copy the console sign-in URL or click on download .csv file as shown in below figure

          ![use4](https://github.com/user-attachments/assets/a3d7430d-31eb-4420-bef0-38be9edb3d01)
  12. Paste the copied url on new web page
  13. It will take you to sign-in console of IAM

      1. Enter the user name and copied password as shown in below figure
         ![use5](https://github.com/user-attachments/assets/8308dd50-edb2-4c48-a7ed-8791056d9b29)
  14. We enter into AWS account with authentication and authorization it means i allowed the permissions for only ec2 services and other services like s3,IAM is not worked
  15. Worked status of ec2 is shown in below figure
      ![use8](https://github.com/user-attachments/assets/b30220e2-9fe0-4034-8507-289bb257ed71)
__________________________________________________________________________________________________________________________________________________________________________________
# WHAT IS USER GROUP IN IAM
 1. User groups in IAM are used to manage permissions for multiple users frequently. instead of assigining permissions to each user individually, you can create a group, assing 
    permissions to that group, and then add users to that group.
# STEPS TO CREATE USER GROUPS IN IAM
**STEP 1:**
 1. Go to IAM console
 2. Select the user groups option and click on create user group
    1. Give the name for user group as shown in below figure
       ![group](https://github.com/user-attachments/assets/926bfb95-8212-47ca-8d98-dd3ccc9a74ad)
    2. No need to add user it is optional as shown in below figure
       ![group  5](https://github.com/user-attachments/assets/61f258fa-0b30-49ad-b5fc-d3f8831c3c1b)
    3. Attach the policies for the groups i choose s3full sevice as shown in below figure
       ![group1](https://github.com/user-attachments/assets/0e7fb927-1ea4-4a4a-957f-ad8818e12a46)
    4. Click on create user group then user group is created
       
**STEP 2:**
  1. Go to users option and click on create user
     1. Give the name tag
     2. Select the provide user access to the aws management console option
     3. select the i want to create IAM user option
     4. select auto generated password in console password option
     5. select these all options as shown in below figure
        ![group2](https://github.com/user-attachments/assets/53ed5dcf-507c-4730-8a33-9409b069b54e)
  2. Select the created group in user
  3. Then the user is attached to the created group as shown in below figure
     ![group3](https://github.com/user-attachments/assets/586222b9-2e84-403c-bd8e-97e2243e2e22)
  4. Click on next and click on create user then it is created
     
**STEP 3:**
  1. Go to user groups
  2. Observe the created group there you see two users are attached as shown in below figure
     ![group6](https://github.com/user-attachments/assets/1a125a1b-c8bc-4863-b4b6-a8a026981cd0)

       

       
   
   

      
       
         

         
         

               
 

    

           


       



  
 



