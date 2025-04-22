# EXP 4 : USING THE AUTOPSY RETRIEVE THE DELETED FILES

## AIM:
This experiment aims to demonstrate:

  •	Create a Disk Partition.
  
  •	Adding, deleting, and recovering files using Autopsy.
  
  •	Understanding the forensic recovery of deleted data.
  
  •	Removing the disk partition after the process.

## EQUIPMENTS REQUIRED:
  ●	Hardware: PCs

```
Register Number:212222040095
Name: Mahisha S
```

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.


## PROCEDURE:
### Step1: Create a New Disk
  •	The new Disk Partition is created
  ![image](https://github.com/user-attachments/assets/ef24e3d5-dca4-4bb8-86af-ca0db57194d9)


### Step2: Adding and Deleting Files for Recovery
  •	Open File Explorer → Navigate to the newly created drive (C: or D:).
  
  •	Transfer images or files into it.
  ![image](https://github.com/user-attachments/assets/a224a29a-9d92-4b5e-9a57-4e28f4b39a61)

  
  •	Select one or more files → Press Delete.
  
  •	Empty the Recycle Bin to permanently remove them.
  
### Step3: Recovering Deleted Files Using Autopsy
1. Launch Autopsy and Set Up a New Case:
 
  •	Run Autopsy as Administrator.

  •	Click Create New Case.
  ![image](https://github.com/user-attachments/assets/2a61d108-a014-4d70-a1f4-a58f715649f4)

  •	Enter a case name (e.g., Autopsy1).
  
  •	Select a location for the case folder → Click Next → Finish.

  ![image](https://github.com/user-attachments/assets/01ea9cd7-d912-4735-ab2c-6da5dc2546e7)

  

  •	Add optional information
  
  ![image](https://github.com/user-attachments/assets/a1f93a40-a4ca-4706-baa3-3a48aff7abc5)


2. Add the Partition as Evidence:
  •	Click Add Data Source → Choose Host.
  ![image](https://github.com/user-attachments/assets/297fdc29-ec74-4760-b757-fc20c3952c17)


  •	Select Local Disk → Click Next.Create a Disk Partition.
  ![image](https://github.com/user-attachments/assets/c020adcb-965c-4823-bcf5-c573f3cefec4)


  •	Choose Disk → Select the VHD drive (Drive1).
  ![image](https://github.com/user-attachments/assets/c9ad282e-c06d-4010-8179-742ba70515e2)


  •	Click Next → Keep the default settings → Click Finish.
  

  •	Allow Autopsy to process the disk.

## OUTPUT: Extract Deleted Files:
  •	In the left panel, navigate to File Views → Deleted Files.
  
  •	Locate your deleted images.
  ![image](https://github.com/user-attachments/assets/7bbe576c-fac3-45cf-a726-4c354304bece)
  


  •	Right-click an image → Click Extract File.
  
  •	Choose a folder for saving the recovered files (e.g., C:\image_recovery).
  
  •	The deleted images are now restored!
  ![image](https://github.com/user-attachments/assets/3a879359-632e-4559-80ca-0ed5c45917b9)
  


## Removing the Disk Partition (Optional Cleanup)
1.Using Disk Management:

  •	Open Disk Management (Win + X → Disk Management).
  
  •	Identify the created partition.
  
  •	Right-click on the partition → Select Delete Volume.
  
2.Alternative Method via Settings:

  •	Click the Start button → Go to Settings.
  
  •	Select System → Click Storage.
  
  •	Click Advanced Storage Settings → Select Disks & Volumes.
  
  •	View the list of available disks.
  
  •	Select the created partition → Click Properties.
  
  •	Click the Delete option to remove it.


## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
