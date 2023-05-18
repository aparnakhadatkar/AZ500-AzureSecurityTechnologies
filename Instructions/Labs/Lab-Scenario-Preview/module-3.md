# Lab Scenario Preview: AZ-500: Secure Data and Applications

## Lab 10: Key Vault (Implementing Secure Data by setting up Always Encrypted)
You have been asked to create a proof of concept application that makes use of the Azure SQL Database support for Always Encrypted functionality. All of the secrets and keys used in this scenario should be stored in Key Vault. The application should be registered in Azure Active Directory (Azure AD) in order to enhance its security posture. To accomplish these objectives, the proof of concept should include:
- Creating an Azure Key Vault and storing keys and secrets in the vault.
- Create a SQL Database and encrypting content of columns in database tables by using Always Encrypted.

>**Note**: For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

To keep the focus on the security aspects of Azure, related to building this proof of concept, you will start from an automated ARM template deployment, setting up a Virtual Machine with Visual Studio 2019 and SQL Server Management Studio 2019.

### Lab objectives
In this lab, you will complete the following exercises:
- Exercise 1: Deploy the base infrastructure from an ARM template
- Exercise 2: Configure the Key Vault resource with a key and a secret
- Exercise 3: Configure an Azure SQL database and a data-driven application
- Exercise 4: Demonstrate the use of Azure Key Vault in encrypting the Azure SQL database

### Architecture Diagram

![image](https://user-images.githubusercontent.com/91347931/157532938-c724cc40-f64f-4d69-9e91-d75344c5e0a2.png)

## Lab 11: Securing Azure SQL Database
You have been asked to review security features for Azure SQL database. Specifically, you are interested in:
- Protection against attacks such as SQL injection and data exfiltration. 
- Ability to discover and classify database information into categories such as Confidential. 
- Ability to audit database server and database queries and log events. 

> For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

### Lab objectives
In this lab, you will complete the following exercise:
- Exercise 1: Implement SQL Database security features

### Architecture Diagram

![image](https://user-images.githubusercontent.com/91347931/157533836-7250fa58-a109-4882-a55b-d3fa3baf34ab.png)

## Lab 12: Service Endpoints and Securing Storage
You have been asked to create a proof of concept to demonstrate securing Azure file shares. Specifically, you want to:
- Create a storage endpoint so traffic destined to Azure Storage always stays within the Azure backbone network.
- Configure the storage endpoint so only resources from a specific subnet can access the storage.
- Confirm that resources outside of the specific subnet cannot access the storage. 

> For all the resources in this lab, we are using the **East US** region. Verify with your instructor this is the region to use for class. 

### Lab objectives
In this lab, you will complete the following exercise:
- Exercise 1: Service endpoints and security storage

### Architecture Diagram

![image](https://user-images.githubusercontent.com/91347931/157534883-29664a05-85d1-4c70-99a7-f16d2360755d.png)