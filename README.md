# FitnessOK


Project Overview
- Project name:- FitnessOK.
- Group members:- [Vipul Koli](https://github.com/KoliVipul2000), [Vaishnavi Patil](https://github.com/VaishPatil2002).

   A comprehensive fitness management platform. Importance of technological integration in the fitness industry. Scope and objectives of the paper and Understanding FitnessOK Architecture. Core components and functionalities. Role of HTML, CSS, and JavaScript in user interface design. PHP and server-side scripting for dynamic content generation. Utilization of MySQL for database management. Overview of Azure Web App Service and its significance in FitnessOK architecture.

  Prerequisites:
  - An Azure account with an active subscription. [Create an account for free.](https://azure.microsoft.com/en-us/free/?WT.mc_id=A261C142F)
 
  Video:- https://drive.google.com/file/d/1QRShXC9Qez-NduRRp8Z2CRz8EQU73V_p/view?usp=sharing
  
  Project Demo Url:- https://vaishnavi.vipul.cloud/
  
  Project pdf URL:- https://drive.google.com/file/d/1mOmY-XdQkBH8pPg9LPseFRcxAMcqrwB7/view?usp=sharing
     
Azure Services Used:
1. App Service.
2. MySQL Flexible Server.
3. DNS Zone.
4. Application Insight.
5. Azure AI Question and Answering Service using Language Studio.

    LOGIN TO AZURE PORTAL
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/be581485-47e9-42ef-af4f-b79efcba70a1)
    Search APP SERVICE in the search bar and open APP SERVICE
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/1fa9e2a3-9b14-4366-96ea-4f17a786b39d)
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/b4746109-8ef1-42d5-8a83-c05b1600459d)
    Click on CREATE & WEB APP SERVICE
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/d57eed1f-9c44-44fe-88d6-cb5cf43d1f93)
    Fill in the required fields Such as Resource Group, Registry name and location.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/bf150be1-bc71-4386-9dd0-aab69f4db84a)
    Go to Deployment and enable the Basic Authentication.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/64a831a1-1288-4179-ac0a-61340e42cac6)
    Click on Review and Create. After validating, the create option will be enabled and then click on create.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/1d400b0d-85e6-4d49-b823-666da428a799)
    After creating the Azure web app, click on “go to resources”, and you will be redirected to resources.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/cbd95254-ae13-4f85-bdc7-c9bf27c51ce3)
    Go to the deployment center and then go to FTPS credentials.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/c42e013a-3349-443b-85de-43b35d025872)
    Download and Open the File Zilla app.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/51605583-5663-40a0-ae8e-17cd49c60a53)
    We have to copy and paste the credentials from the web app FTPS credentials and paste them in the file Zilla application above.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/c7db4e2b-40f1-4af7-947c-0888869949ac)
    Click on Quick Connect, after clicking Quick Connect the message will appear connection successfully.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/ab9ad1a9-30d8-4fd8-bc45-54f03d3e276c)
    Now drag/copy and paste the project file, make sure to keep the .html file with hostingstart.html.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/72ca5695-f7a3-4c66-a4ae-60e5a330820e)
    Now we have to connect our SQL database with the app service.
    Download and install MYSQL & MYSQL WORKBENCH on your PC.
    Open MY SQL WORKBENCH.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/e055a59b-1986-4c07-8c6b-fc5454c21b7e)
    Go to the Azure portal and search for Azure Database for the MYSQL server
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/8267fec2-d5d7-4f6b-8cbb-1b93a2c517e3)
    Click on Create.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/260045c6-c501-4e2f-9be8-342353b92aab)
    We have to create a flexible server, so click on a flexible server.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/2755964e-fcd2-4faa-b7c5-bd6da7f49aa2)
    Fill in the credentials, go to review and create, and create it, after creating click on go to resources.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/8bb8703f-9ceb-4d0e-a8d8-80dbf035ed0e)
    In resources, go to networking allow we have to allow public access and add our public IP address.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/70eb1c31-cc7f-4e5a-a046-8e47dab08ba5)
    Download the SSL certificate from above.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/3117399a-8065-41b3-8051-087e2c016102)
    Go to Connect.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/da2795fd-26ea-497d-be50-9fc464d76c5e)
    There we will see our connection details are given, now expand the MySQL Workbench and follow the steps given below.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/4db1ca3d-73ac-4690-9eae-9f7ecc089120)
    Open the workbench and beside the MySQL connection there is + sign click on it and a box will appear.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/cf41524e-40a3-41e0-99ed-5ce35ea4fe51) Fill the details/ follow the steps given in azure MySQL service and click ok
    Now open the connection.
    After opening the connection, go to the file and click on open SQL script.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/00acb6b4-2a2a-43aa-8b78-23161b6942ee)
    We have to add our database there, and if it is not working then we have to add on the top of the database code
    To create database fitnessok;
use fitnessok;
    You have to make changes in the PHP code as shown
    Fill the correct credentials in the server, user, password & database.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/65ff1a0c-0144-423a-9e62-79d6e18f3b86)
    Then your database is connected to Azure.
    You can open your website by clicking the default domain in the app service.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/fa1587ee-17a3-4804-a794-6bccb233ccdd)
    In the search bar, we can see the default domain.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/4ad63230-0bda-47f5-8dc7-2288280d6301)
    Now we have to change our domain name, we can change using DNS.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/b046e2fc-57bd-4b23-8d97-2c52473bbd6f)
    Click on Create and fill in the credentials, we have to set the domain name in it.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/869340f2-de59-4382-bd55-147e73014e27)
    Go to review and create and click on create.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/b40cc133-74a4-4e17-b9f7-d29ac528defe)
    Go to the resource.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/b49f50ec-c0ec-4d3b-9675-ae18f8acff47)
    We have to add the record set first, click on the record set and fill in the credentials properly.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/3f415971-fe29-455a-b603-7bd85b04ddb5)
    Then try opening the website by the domain name you have named.
   ![image](https://github.com/VaishPatil2002/FitnessOK/assets/166396026/4598de28-1101-4f46-9d9e-db7232cc64d7) As you can see in the search box my domain name is set.
    Now we need alerts if the website is taking too much of a load, then search & create an application insight service.
   ![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/35bb4353-b8a0-4ab4-abc8-4bd2880cefcf)
   
Project Screenshots: Landing Page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/ac75b645-a0d4-42ac-a8e9-37baf21bb907)

About page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/89f5bf73-d567-42f7-bf28-9ef0dc49f832)

Service page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/fd90644d-b39c-4ae2-9c8b-83626e2c3d4f)

Trainer page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/ec7ec355-06b2-4232-9b0e-9296037d9e14)

Plan page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/f1c243d8-13fb-4066-ae98-d8842a5ce682)

Register page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/65e9b2d8-7609-4f5d-ac36-bc3c384f51f3)
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/bd4feeef-c969-47e6-843e-7ed67a181d59)

Contact page
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/a142e4ac-0461-4833-b829-18b901ffc723)

Transaction pages
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/1e175a86-0156-4b4b-be47-e5e8078f5371)
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/526eb1ce-39fe-471f-806a-4226b4dcbd8f)
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/0f827588-016e-4505-985e-241b8ca06324)
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/420085bb-0fba-4afd-acf1-8a101694c159)
![image](https://github.com/Vipulkoli2000/PROJECT-FitnessOK/assets/115494015/7269c54d-a56a-4fcc-a6f8-f417631a4e4b)





