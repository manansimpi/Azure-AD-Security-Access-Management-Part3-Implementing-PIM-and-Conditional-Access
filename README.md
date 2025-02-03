# Azure AD Security Access Management Part3 Implementing PIM and Conditional Access
## Step 1: Enabling Privileged Identity Management (PIM) and Conditional Access.
1. Getting Azure P2 licence as Conditional Access and PIM is the functionality offered only on the P2 License.

![10 1 Getting Azure P2 Liscense for Condition Access](https://github.com/user-attachments/assets/b0744900-c806-4a05-bb3c-0b8df35297f6)


2. Navigate to Azure Active Directory.
3. Select Identity Governance present on the left blade > PIM > Start the free trial if not used > Microsoft Entra Roles.

![Screenshot 2025-01-30 221219](https://github.com/user-attachments/assets/4694830e-d81b-41e5-bfd8-d2d1a43474b7)

<br><br>

![Screenshot 2025-01-30 220558](https://github.com/user-attachments/assets/2b34acf9-03d4-4991-a1ab-7b93172d4706)




## Step 2: Assigning Eligible Role and Privilidged Identity Management.

1. Selecting a privileged role like Global Administrator or Security Administrator to the TestUser with no roles at the moment.
 
![Screenshot 2025-01-30 224402](https://github.com/user-attachments/assets/f9a35a24-e21b-47d4-ba33-9b3c6e111a8b)

<br><br>

![Screenshot 2025-01-30 224636](https://github.com/user-attachments/assets/3531637e-b560-4d95-af59-a5a62244b28f)

<br><br>

![image](https://github.com/user-attachments/assets/b5a80ed6-852e-4a17-a146-41a6572d6179)

<br><br>

![Screenshot 2025-01-30 225829](https://github.com/user-attachments/assets/8adbdfd7-aeba-4bce-b5b7-0943fd9b8233)

2. To grant a permanent role tickmark the Checkbox but if required to grant a role for a limited time period then just play around with the Assignment start/Assignment end.

![Screenshot 2025-01-30 230306](https://github.com/user-attachments/assets/15b56c38-ac4e-4a2e-9dde-78787bd82e55)

<br><br>

![Screenshot 2025-01-30 231928](https://github.com/user-attachments/assets/fcff7b23-a2a5-4a69-a940-032ee4d8e2fa)

<br><br>

![Screenshot 2025-02-02 230139](https://github.com/user-attachments/assets/12c82c9d-b2f5-4749-81e8-4c4eb9b7935e)

<br><br>

![Screenshot 2025-02-02 230420](https://github.com/user-attachments/assets/2c90da5f-30ca-466d-8db4-106120a8efdd)

## Step 3: Implementing Just In Time Access.


## Step 4: Implementing Conditional Access.

1. Go to Portal.azure.com and search for Conditional Access and create a new Conditional Access Policy.

![Screenshot 2025-01-26 233713](https://github.com/user-attachments/assets/cb8feff8-5d43-4948-ae03-7f1bc9fc4689)

<br><br>

![Screenshot 2025-01-26 233918](https://github.com/user-attachments/assets/84589156-0fff-43ae-9828-b959c500b83c)

- Don't forget to exclude one account be it the Owner or a Global Administrator just to make sure you don't get locked yourself with all the other users just in case.

![Screenshot 2025-01-26 233939](https://github.com/user-attachments/assets/dc96c5da-7c53-4014-99fa-47a9755f09dc)

<br><br>

![Screenshot 2025-01-26 234804](https://github.com/user-attachments/assets/7de99f7c-75b6-499b-9f19-3154aaa44310)

- Azure is like if you want to override our protection setup then please turn of our Security Default. Just follow the link provided by Azure portal shown in the below image.

![Screenshot 2025-01-26 234804](https://github.com/user-attachments/assets/a8510d41-c203-41e9-b671-34d1dcd13c45)

<br><br>

![Screenshot 2025-01-26 235043](https://github.com/user-attachments/assets/0bff79a3-0e38-43ee-985f-af624cb68770)


2. 


