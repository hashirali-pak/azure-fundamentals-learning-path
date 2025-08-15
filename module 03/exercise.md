# Exercise - Create a storage blob

## 1. Create a storage account
- Sign in to the Azure portal at " https://portal.azure.com ".
- Select Create a resource.
- Under Categories, select Storage.
- Under Storage account, select Create.
- On the Basics tab of the Create a storage account blade, fill in the following information. Leave the defaults for everything else.
- On the Advanced tab of the Create a storage account blade, fill in the following information. Leave the defaults for everything else.
- Select Review to review your storage account settings and allow Azure to validate the configuration.
- Once validated, select Create. Wait for the notification that the account was successfully created.

![Task Screenshot](screenshots/m3_ex(taska).png)

- Select Go to resource.

## 2. Work with blob storage
- Under Data storage, select Containers.
- Select + Container and complete the information.
- Select Create.
- Back in the Azure portal, select the container you created, then select Upload.
- Browse for the image file you want to upload. Select it and then select upload.
- Select the Blob (file) you just uploaded. You should be on the properties tab.
- Copy the URL from the URL field and paste it into a new tab. You should receive an error message similar to the following.

![Task Screenshot](screenshots/m3_ex(taskb).png)

## 3. Change the access level of your blob
- Go back to the Azure portal.
- Select Change access level.
- Set the Anonymous access level to Blob (anonymous read access for blobs only).
- Select OK.
- Refresh the tab where you attempted to access the file earlier.

![Task Screenshot](screenshots/m3_ex(taskc).png)

