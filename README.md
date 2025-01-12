<p align="center">
  <img src="https://github.com/Jalal-Hatamleh/Creating-VMs-in-Azure/blob/main/images/1.png?raw=true" alt="Installation Screenshot"/>
</p>

# Creating Virtual Machines and Storage Containers in Azure

In this project, I worked on creating a **Resource Group** and setting up a **Storage Container** within it in Microsoft Azure. This hands-on lab helped me get familiar with Azure's cloud environment and allowed me to manage files and resources easily.

## Environments and Technologies Used

- **Cloud Platform**: Microsoft Azure (Virtual Machines / Compute)
- **Remote Desktop**: For connecting to Azure VMs
- **Operating System**: Windows 10 Pro (Version 22H2)

## Steps

### 1. Create a Resource Group in Azure

The first step was to set up a **Resource Group** in Azure. This is essential for organizing all of your resources and keeping everything structured.

Here’s what I did:
1. Logged into the Azure portal.
2. Navigated to the **Resource Groups** section.
3. Clicked **Create**, named the group, and selected the region.
4. Once everything was reviewed, I hit **Create**.

![Create Resource Group](https://github.com/Jalal-Hatamleh/Creating-VMs-in-Azure/blob/main/images/2.png?raw=true)  

### 2. Create a Storage Container in the Resource Group

Next, I created a **Storage Container** inside the Resource Group to store files.

Here’s how I set it up:
1. In the Resource Group, I went to **Storage Accounts** and created a new one.
2. I chose the **StorageV2** option for the account type.
3. After the account was created, I opened it and navigated to **Containers** under the **Blob service**.
4. I clicked **+ Container** to set up a new storage container for my files.

![Create Storage Container](https://github.com/Jalal-Hatamleh/Creating-VMs-in-Azure/blob/main/images/3.png?raw=true)  


### 3. Upload a Plain Text File

Once the container was ready, I uploaded a simple text file to it. This was a basic test to make sure everything was working.

Steps I followed:
1. Created a text file on my desktop (e.g., `example.txt`).
2. Went to the storage container in the Azure portal.
3. Clicked **Upload**, selected the file from my desktop, and uploaded it.

![Upload File](https://github.com/Jalal-Hatamleh/Creating-VMs-in-Azure/blob/main/images/4.png?raw=true)  


### 4. Edit and Download the File in Azure

To make sure everything was functioning properly, I edited the text file in the Azure portal and then downloaded it back to my computer.

Here’s what I did:
1. Opened the text file in the storage container.
2. Clicked **Edit** to make changes directly in the portal.
3. Saved the changes and then downloaded the file to confirm the edits worked.

![Edit and Download File](https://github.com/Jalal-Hatamleh/Creating-VMs-in-Azure/blob/main/images/5.png?raw=true)  


### 5. Delete the Resource Group to Prevent Ongoing Costs

Once I was done, I made sure to clean up and delete the **Resource Group** to prevent any unnecessary costs.

Steps to delete:
1. Went to **Resource Groups** in the portal.
2. Selected the Resource Group I created.
3. Clicked **Delete Resource Group** and confirmed the action.


## Key Takeaways

- **Resource Group Management**: I created and organized a Resource Group in Azure to manage all my resources.
- **Azure Storage**: Set up a **Storage Container** for file storage and practiced uploading and managing files.
- **Hands-on with File Management**: I uploaded, edited, and downloaded a simple text file in Azure’s cloud storage.
- **Cost Management**: I made sure to delete the Resource Group after the lab to avoid any ongoing charges.
- **Experience with Azure**: Gained practical experience in setting up and managing cloud storage and resources within Azure.

## Conclusion

This project helped me get comfortable with Azure’s portal and resource management. I learned how to organize cloud resources, upload and edit files, and clean up after myself to avoid unnecessary costs. It was a simple but effective way to understand how cloud storage works in Azure, and it gave me confidence in managing cloud-based resources.

I hope this helps you understand how I worked through the project. Check out the images and steps in the repository for a more detailed breakdown. This hands-on experience has given me a solid foundation for working with cloud platforms and managing virtual resources in a professional environment.
