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

![Screenshot 2025-03-28 092304](https://github.com/user-attachments/assets/c1d7cf2a-7780-4e02-b991-83342580d981)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

![ss 1](https://github.com/user-attachments/assets/cd522d61-6cbf-4de0-9bd5-498357691a58)


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![ss2](https://github.com/user-attachments/assets/f12adf9a-f76b-4cde-ba41-67e0aa593315)


- Select **Local Disk** → **next** 

![ss3](https://github.com/user-attachments/assets/ca19af55-e1b2-4269-b8e5-bf1bad0220d5)


- Select Disk → **Choose the VHD drive (`Drive1`)**

![ss4](https://github.com/user-attachments/assets/e21850ae-d758-40ff-9017-c284007b1bee)


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![ss5](https://github.com/user-attachments/assets/16467e93-a16c-45a2-9e27-235d3fa07858)


![ss6](https://github.com/user-attachments/assets/4d78e4d0-27ec-483a-9b8f-fcbe93a71955)



- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.

![ss7](https://github.com/user-attachments/assets/d5a10ab8-9db5-449e-af51-15206f5f96a9)


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files


### Folder after deleting the files


### Folder after extracting the deleted images using autopsy


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
