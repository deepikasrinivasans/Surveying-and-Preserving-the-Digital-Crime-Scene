### REGISTERR NUMBER: 212222230028
### NAME: DEEPIKA S
# LAB-2 Surveying and Preserving the Digital Crime Scene

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

![autopsy1](https://github.com/user-attachments/assets/c849cafe-e437-4494-9320-da79026790ae)

- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  
![autopsy2](https://github.com/user-attachments/assets/2eaea9f9-6253-4696-a333-8d7d5610f0ca)



### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

![autopsy3](https://github.com/user-attachments/assets/9f3d7a7e-2cdf-484f-bd53-89684c67368d)


- Select **Local Disk** → **next** 

![autopsy4](https://github.com/user-attachments/assets/8e461d41-da59-410c-94ed-3e1f010f74c6)


- Select Disk → **Choose the VHD drive (`Drive1`)**


![autopsy5](https://github.com/user-attachments/assets/c6a39860-0dd3-4211-b578-52695f8d807b)

- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

![](./images/a6.png)


- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

![FIRST1](https://github.com/user-attachments/assets/f71b9403-e7b7-4e62-8f35-7609d9645512)
- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![FIRST](https://github.com/user-attachments/assets/46666410-72ee-4489-b7a4-3de34d63156a)


### Folder after deleting the files
![SECOND](https://github.com/user-attachments/assets/00ad6d88-df08-4f4a-bdce-9a094169ac1a)


### Folder after extracting the deleted images using autopsy
![THIRD](https://github.com/user-attachments/assets/c380904b-0ba0-4193-87de-69234baa7e58)


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
