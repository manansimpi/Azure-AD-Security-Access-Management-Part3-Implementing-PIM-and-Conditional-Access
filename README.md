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

## Step 3: Implementing Just In Time Access(JIT for a VM).

1. Microsoft Defender for Cloud > Workload Protection > Just-in-time VM access.

![Screenshot 2025-02-03 011759](https://github.com/user-attachments/assets/62bf7a97-0bfe-4805-86fa-6f43b46dbfd6)

 <br><br>

 ![Screenshot 2025-02-03 011838](https://github.com/user-attachments/assets/5d6b9bc6-4362-462e-b122-58c5f5d92e76)

 - Adding the port configurations with the specific IP Address access.

![Screenshot 2025-02-03 013638](https://github.com/user-attachments/assets/4f60381c-f2e0-4b3f-bb47-179099d8bd2c)

<br><br>

- Temporarily pausing this part or would include this in some other project due to facing some license-related issues as below.

![Screenshot 2025-02-03 013704](https://github.com/user-attachments/assets/0b6e2aea-11c7-4147-8627-ac9f2390c983)

Basically, I am planning as follows:
a. Configure JIT settings for VM.
b. Request JIT Access from the VM configured for JIT then choose the required port and specify the duration.
c. If all the requirements align to the JIT settings configured then access to the VM is granted.
d. Monitor JIT activity(Approved JIT requests/Active sessions/Failed access attempts)



## Step 4: Implementing Conditional Access.

1. Go to Portal.azure.com search for Conditional Access and create a new Conditional Access Policy.

![Screenshot 2025-01-26 233713](https://github.com/user-attachments/assets/cb8feff8-5d43-4948-ae03-7f1bc9fc4689)

<br><br>

![Screenshot 2025-01-26 233918](https://github.com/user-attachments/assets/84589156-0fff-43ae-9828-b959c500b83c)

- Don't forget to exclude one account be it the Owner or a Global Administrator just to make sure you don't get locked yourself with all the other users just in case.

![Screenshot 2025-01-26 233939](https://github.com/user-attachments/assets/dc96c5da-7c53-4014-99fa-47a9755f09dc)

<br><br>

![Screenshot 2025-01-26 234804](https://github.com/user-attachments/assets/7de99f7c-75b6-499b-9f19-3154aaa44310)

<br><br>

![Screenshot 2025-02-04 220530](https://github.com/user-attachments/assets/97e751fb-ed9b-43c9-aa52-674520493b40)

<br><br>

![Screenshot 2025-02-04 220548](https://github.com/user-attachments/assets/394f784f-a737-4cb7-855a-cd0fa94fb376)

<br><br>

![Screenshot 2025-02-04 220622](https://github.com/user-attachments/assets/807ded41-afcb-4ccc-8fa0-3e5d6d49a5e9)

<br><br>

![Screenshot 2025-02-04 220716](https://github.com/user-attachments/assets/7ee63145-4980-4983-9414-80a3f101e442)


- Azure is like if you want to override our protection setup then please turn off our Security Default. Just follow the link provided by the Azure portal and it will redirect to 
 the page as shown below.

![Screenshot 2025-01-26 235043](https://github.com/user-attachments/assets/0bff79a3-0e38-43ee-985f-af624cb68770)




