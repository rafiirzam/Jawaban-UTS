# UTS Sistem Administrasi Server - IT 02-01
## Muhammad Rafi Irzam (1202190063)
---
## QUESTION
![image](https://user-images.githubusercontent.com/83237598/143668703-57cb45ba-60b0-46ed-9574-c102457b5c38.png)
## ANSWER
### 1. Download ISO Installer Windows Server 2022
https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022
- Select Download ISO and then continue until file downloaded
![image](https://user-images.githubusercontent.com/83237598/143668763-75b4b61c-2c4f-4de6-8d2d-57f4d9dfb831.png)
### 2. Installation Windows Server 2022 pada virtual box
- Open virtual box and create virtual machine
![Screenshot (128)](https://user-images.githubusercontent.com/83237598/143668512-cfd08455-4788-49b2-847a-f96b3f07e41d.png)

- Choose name and operating system (Windows Server 2022)
![image](https://user-images.githubusercontent.com/83237598/143668845-798795cd-4d24-40e9-8782-91dc9ad1ea99.png)

- Select the amount of memory (RAM)

   ![image](https://user-images.githubusercontent.com/83237598/143668865-2b27aa97-590d-4f50-a6cb-293269c77b74.png)

- Create a virtual hard disk

   ![image](https://user-images.githubusercontent.com/83237598/143668869-a71111ad-955a-4a0d-89c2-cd6f2cb83e1e.png)

- Choose virtual hard disk file type

   ![image](https://user-images.githubusercontent.com/83237598/143668872-0c78af47-0e7e-49ca-9065-2240e350bf86.png)

- Choose storage on physical hard disk

   ![image](https://user-images.githubusercontent.com/83237598/143668878-f87b6b50-7e51-4336-9806-e2f16d5d1360.png)

- Select file location and size of the virtual hard disk
![image](https://user-images.githubusercontent.com/83237598/143668885-644c251e-7374-435a-bee2-c9fb4a675f94.png)

- Go to Storage setting and attach ISO Windows Server 2022 file
![image](https://user-images.githubusercontent.com/83237598/143668906-78a82365-86e1-4964-b7a8-f0dc26a7df42.png)

- Go to network setting and set to bridge adapter
![image](https://user-images.githubusercontent.com/83237598/143668916-33bbc12b-d5d7-43aa-9d9b-48e72532bf18.png)

- Start Virtual Machine and setup windows
![image](https://user-images.githubusercontent.com/83237598/143668972-d8227e10-cef7-4710-abaf-22af8cc5f526.png)

- Click "Install Now"
![image](https://user-images.githubusercontent.com/83237598/143669116-ef25a7b4-e82c-438a-8872-b5ede7cabba3.png)

- Select Windows Server 2022 (Desktop Experience)
![image](https://user-images.githubusercontent.com/83237598/143669141-455a7804-75fd-4e63-8971-039d1d23a5c9.png)

- Accept license terms
![image](https://user-images.githubusercontent.com/83237598/143669150-799e7a8b-f1a0-498c-b6b4-954177c8fb21.png)

- Select Custom Installation
![image](https://user-images.githubusercontent.com/83237598/143669187-0da02c3d-7626-4fa4-83ce-f2d82488ca18.png)

- Location of Windows Server 2022 Installation
![image](https://user-images.githubusercontent.com/83237598/143669220-4d637cff-b0fe-4d97-8ebe-08311eaa15ab.png)

- Installation Progress
![image](https://user-images.githubusercontent.com/83237598/143669235-ef99042e-9252-479a-aee4-b5160fc4b4c6.png)

- Set Password
![image](https://user-images.githubusercontent.com/83237598/143669403-aaa766a6-d561-4864-bdaa-96ed6dd1fa62.png)

- Lock screen display Windows Server 2022
![image](https://user-images.githubusercontent.com/83237598/143669442-84fd2470-33a1-4a9e-9f38-71ab97798035.png)

- Choose "Ctrl + Alt + Del" in input menu then input password
![image](https://user-images.githubusercontent.com/83237598/143669597-61746d1f-c716-4523-bd2e-032d14f48984.png)

- Windows Server 2022 Succesfully Installed
![image](https://user-images.githubusercontent.com/83237598/143669654-3f07b14c-abe2-446f-8cc9-dda3cd6f7e6f.png)


### 3. Installation Active Directory Domain Services
- Before installation, change computer name
![image](https://user-images.githubusercontent.com/83237598/143669774-0bb2cbcb-54bb-40e7-8aa3-fce671287df6.png)

- Go to server manager >> dashboard >> add roles and features 
![image](https://user-images.githubusercontent.com/83237598/143669864-e51d8680-b3cc-44a3-8abe-9349bc852a65.png)

- Click Next
![image](https://user-images.githubusercontent.com/83237598/143669884-bc716a95-7d59-4301-a537-07724cf46a58.png)

- Select Role-based or feature based installation
![image](https://user-images.githubusercontent.com/83237598/143669908-9328912c-a899-4ebb-9bf8-92d73ea95236.png)

-  Select a server from the server pool
![image](https://user-images.githubusercontent.com/83237598/143670553-91c47847-07f5-4ac7-b6c1-82c641629f49.png)

-  Checklist at Active Directory Domain Services Roles then next
![image](https://user-images.githubusercontent.com/83237598/143670663-64757dde-7d83-4a69-befb-49c65720705a.png)

-  Checklist Group Policy Management then next
![image](https://user-images.githubusercontent.com/83237598/143670718-5096235c-d8ee-4552-8bbd-5337cd27757e.png)

-  Click Next and install
![image](https://user-images.githubusercontent.com/83237598/143670762-d441e3f1-5105-498f-a95f-748ebd94e86c.png)

![image](https://user-images.githubusercontent.com/83237598/143670798-9936793a-7e01-4c92-9c43-7611a9d7f366.png)

-  Installation Succeeded
![image](https://user-images.githubusercontent.com/83237598/143671012-63ffa622-c10d-4443-9497-754ed5e8c45b.png)

### 4. Installation DNS Server
- Go to server manager >> dashboard >> add roles and features >> Server Roles >> Checklist DNS Server then install
![image](https://user-images.githubusercontent.com/83237598/143671595-b60e4d63-8b4f-486c-b016-e46c2429b6c0.png)

- Installation Suceeded
![image](https://user-images.githubusercontent.com/83237598/143671655-80677c28-4fe7-43bb-b5d1-2cd18e225058.png)


### 5. Installation NET Framework 3.5
- Go to server manager >> dashboard >> add roles and features >> Features >> Checklist NET Fraamework 3.5 then install
![image](https://user-images.githubusercontent.com/83237598/143672201-50bd6061-4caf-4354-94c8-578ae37f8a37.png)

- Installation Suceeded
![image](https://user-images.githubusercontent.com/83237598/143672325-cfac01fd-3ef0-401d-bf1c-2e8dc56c65d1.png)

### 6. Promote server to a domain controller
- Go to command prompt and type "sconfig"
![image](https://user-images.githubusercontent.com/83237598/143672385-75769295-8418-4e94-a576-49f24250ac83.png)

- Choose Network Settings
![image](https://user-images.githubusercontent.com/83237598/143672407-02eb0892-3661-4dbe-ac75-e0ce0ae8c381.png)

- Setting IP to static
![image](https://user-images.githubusercontent.com/83237598/143676544-c9c149ae-b9d5-4c41-9151-d996f8340514.png)

![image](https://user-images.githubusercontent.com/83237598/143676597-b2fc105b-9385-4d97-8325-e6ea3cbcf6a2.png)

- Set IP Addres Server-AD DS and Set DNS Server
![image](https://user-images.githubusercontent.com/83237598/143676721-edbd4c9b-fdd2-400a-bea4-bac5b7a53c43.png)

-  Click Action "Promote this server to a domain controller"
![image](https://user-images.githubusercontent.com/83237598/143676856-f1ec6170-ceed-4ec7-af2d-7488ea306b18.png)

-  Select "Add a new forest" and type root domain name
![image](https://user-images.githubusercontent.com/83237598/143676940-32907eb3-1d06-4100-8ce8-1e7458e97d07.png)

-  Set configuration as picture below
![image](https://user-images.githubusercontent.com/83237598/143677016-6b323394-498d-40d1-8f34-983306076f50.png)

-  Click Next
![image](https://user-images.githubusercontent.com/83237598/143677060-147ff386-f57a-48c6-b568-adeaf2bb9800.png)

-  Verify NetBios Domain Name
![image](https://user-images.githubusercontent.com/83237598/143677135-8a187884-be34-47bd-afbf-289d3c9b2abe.png)

-  Click Next
![image](https://user-images.githubusercontent.com/83237598/143677339-54c04cb4-22fb-49ec-b02f-72524e0a8326.png)

-  Review configuration, if everything ok then next
![image](https://user-images.githubusercontent.com/83237598/143677397-d25424f1-211f-4bb0-968c-29fccc8bb787.png)

-  If appear "All prerequisite check passed successfully" then click install
![image](https://user-images.githubusercontent.com/83237598/143677431-24e51bf5-43b6-42e6-93ba-f33b785aae00.png)

-  Wait until installation finished
![image](https://user-images.githubusercontent.com/83237598/143677495-ce3063fd-6ab5-416d-825b-ed963efbaa59.png)

-  After installation finished, machine restart automatically
![image](https://user-images.githubusercontent.com/83237598/143677585-69eea69b-679b-4baf-b58e-c9fe9997f780.png)

-  Check configuration result
![image](https://user-images.githubusercontent.com/83237598/143677656-cdc51dec-e2eb-4337-8cd2-85c23862adb8.png)

# FINISH (=
