<p align="center">
       
![AWS_logo_new](https://github.com/user-attachments/assets/a7a389ae-0c58-4096-afdf-d0586aaa44e3)

   

</p>

<h1>AWS Cloud </h1>
AWS (Amazon Web Services) is a comprehensive and widely adopted cloud platform that offers a variety of on-demand computing services, storage, networking, and analytics, enabling businesses to scale and innovate with flexibility and efficiency.

<h2>Requirements</h2>

- Computer with Internet Connection
- Credit Card (Required for free AWS credits)

<h2>Configuration Steps</h2>


<h3>Step 1: Create an AWS Account</h3>

- Select Sign up
- Follow the prompt to create the account 
     - The person or user who creates their AWS account will be the root user be sure to remember your User name and Password
       
     - You may also go to [AWS SIGN UP](https://signin.aws.amazon.com/signup?request_type=register) to start

![Screenshot 2024-12-04 142259](https://github.com/user-attachments/assets/5ae5b053-3370-4f82-b671-da116523074d)

![Screenshot 2024-12-04 142337](https://github.com/user-attachments/assets/da87ee2d-51e7-4ffb-8369-33b768ed253f)

![Screenshot 2024-12-04 144332](https://github.com/user-attachments/assets/d9c5f22c-70f1-4afe-ba87-7aa29c934c2b)






<h3>Step 2: Create an IAM User with Amazon S3 Access</h3>

- Go to the search bar at the top and search "IAM"
- Select Users tab to the left 
- You will need to name the user JohnDoe 
- 
    - For this example, we will be using Web-vm for the name and (US) East US 1 for the region
 
![image](https://github.com/user-attachments/assets/57eb214d-7520-45b2-812a-8b83a7b28f5a)

![Screenshot 2024-12-04 143236](https://github.com/user-attachments/assets/209a1f7c-0c77-4369-87ed-869bdb6f82e5)

![Screenshot 2024-12-04 143727](https://github.com/user-attachments/assets/fe05ddf6-bafa-43a4-9ef8-0cad535fc875)


![Screenshot 2024-12-04 143754](https://github.com/user-attachments/assets/e6d56d10-09d9-461d-a420-ad73f4652bb8)


![Screenshot 2024-12-04 143953](https://github.com/user-attachments/assets/d636cb79-6e74-4a8b-b859-0fb763253c10)


![Screenshot 2024-12-04 144025](https://github.com/user-attachments/assets/962700ee-03ea-4240-9961-83db19d8fb90)


![Screenshot 2024-12-04 145254](https://github.com/user-attachments/assets/8589c3a8-f924-461d-a997-695276fa8a55)


![Screenshot 2024-12-04 145335](https://github.com/user-attachments/assets/5bfff862-501b-48ce-b18a-97467e75497a)








<h3>Step 3: Create a Storage Account</h3>

- Go to the search bar and search "storage account"
- Select Create Storage Account
- You will need to select the same resource group, the same region, and create a name for the storage group
    - For this example, we will name the storage group "rglab1"
    - Use the same resource group and region as step 2
- Select Review, then Create



![Screenshot 2024-11-24 215932](https://github.com/user-attachments/assets/b880adb5-0550-4f7c-a3fb-e2198a9fff01)



<h3>Step 4: Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

![Screenshot 2024-11-24 215513](https://github.com/user-attachments/assets/ee0a9a8c-ba5b-48cf-9a1b-c451e856a9ec)

![Screenshot 2024-11-24 215525](https://github.com/user-attachments/assets/612bc7dd-b922-457b-a7d7-328550a2b6df)


![Screenshot 2024-11-24 215602](https://github.com/user-attachments/assets/41ab1e7e-01a5-4b3e-b949-16050448f1a9)



* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<h3>Step 5: Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

![Screenshot 2024-11-24 220704](https://github.com/user-attachments/assets/769ca32c-744e-42f5-8790-f619c597e2f9)

![Screenshot 2024-11-24 220734](https://github.com/user-attachments/assets/32a508d6-391a-4132-b941-92280303c5c4)


![Screenshot 2024-11-24 220854](https://github.com/user-attachments/assets/21a6e24e-6781-4fd9-a151-d66d9c975e62)




* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK







You have created your first virtual machine within Azure!




