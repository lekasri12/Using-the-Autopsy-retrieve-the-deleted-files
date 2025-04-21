# Surveying and Preserving the Digital Crime Scene
## Register number: 212223100025
## Name: G Lekasri

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

![](./images/a1.png)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![](./images/a2.png)

### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![](./images/a3.png)

- Select **Local Disk** → **next** 

![](./images/a4.png)

- Select Disk → **Choose the VHD drive (`Drive1`)**

![](./images/a5.png)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![](./images/a6.png)

![Screenshot 2025-03-28 084850](https://github.com/user-attachments/assets/c521d64f-0152-45d0-94a9-9d3aa3bbe325)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.
![Screenshot 2025-03-28 090042](https://github.com/user-attachments/assets/37ae198e-3389-4eb1-ad47-318d9a8e1a47)

- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-03-28 084229](https://github.com/user-attachments/assets/f043d359-3eea-4502-90ed-ea543baaeeb4)


### Folder after deleting the files
![Screenshot 2025-03-28 085428](https://github.com/user-attachments/assets/d4ad6745-5d61-4b00-a7a7-9f7152e64dc3)


### Folder after extracting the deleted images using autopsy
![Screenshot 2025-03-28 085114](https://github.com/user-attachments/assets/535d88ef-18b1-4863-b752-b3ca5bcc137b)

## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
