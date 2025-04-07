# Surveying-and-Preserving-the-Digital-Crime-Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![a1](https://github.com/user-attachments/assets/0c5188d6-eaca-4717-9daa-9e8203b47b77)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![a2](https://github.com/user-attachments/assets/abd9625a-e1c1-46b1-aa6f-00afc9e7d3ea)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![a3](https://github.com/user-attachments/assets/ae8ed2cf-b37e-4399-9982-adbf768cecd6)


- Select **Local Disk** → **next** 

![a4](https://github.com/user-attachments/assets/85d4c7ad-badd-42ec-89f5-1e617e636d92)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![a5 (1)](https://github.com/user-attachments/assets/93128ae0-6c7b-41ca-a177-d98e0726dc09)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![a6](https://github.com/user-attachments/assets/3b1ca454-180c-4040-99dc-66ed73037c87)


![a7](https://github.com/user-attachments/assets/e7b36c0e-c080-4a6b-8bff-f4f6e3bf4d72)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![a8](https://github.com/user-attachments/assets/c7dbdad1-bb69-4050-87f6-ec620c1d215f)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-04-07 140239](https://github.com/user-attachments/assets/eeb3fed3-bd3b-4c83-bf60-57a1590d5d32)

### Folder after deleting the files
![Screenshot 2025-04-07 140304](https://github.com/user-attachments/assets/c77934a1-35d1-4a85-bd9a-cf887b848443)


### Autopsy Recovery
![image](https://github.com/user-attachments/assets/a33740dc-5592-45e1-83fb-7ab1def51cf5)

### Folder after extracting the deleted images using autopsy
![Screenshot 2025-04-07 140239](https://github.com/user-attachments/assets/3644ec0a-1ac2-4235-83fd-24781869140e)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
