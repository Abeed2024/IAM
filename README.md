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
      
       
         

         
         

               
 

    

           


       



  
 



