Thanks for downloading this template!

Template Name: Gp
Template URL: https://bootstrapmade.com/gp-free-multipurpose-html-bootstrap-template/
Author: BootstrapMade.com
License: https://bootstrapmade.com/license/

**Deploying a static website using Blob Storage in Azure**
  1. Let's create a storage account first. Go to Azure portal and search for storage account.
  2. Click on "+" account to start creating.
  3. For resource group, you can choose any existing resource group or create a new one, i created a new one, lets name it "StorageWebsite".
  4. Now for storage account name, you need to give sunique name, it should be unique in whole Azure space, i give it "website123456".
  5. In next section which is advanced under Access Tier choose "cool" since, it used to infrequent accessed data.
  6. In networking section, make sure "Network Access" i set to public.
  7. Now in Encryption section make "Enable support for customer-managed keys" to All service types.
  8. Now review and create it.

<img width="915" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/ca3f3a4b-b76e-4222-b93d-e4a0d515fd90">
<img width="746" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/70fe743e-49d2-4271-ac24-9e4ab7677b89">
<img width="699" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/e3a9d23b-41e9-4ed4-8e58-b0f3a4674b9c">
<img width="646" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/22ccd980-31d9-47bc-bdc2-b2a06ae4e594">


Since our storage account is now created, we will need a website to deploye on it. For this i am using a template from bootstrapmade.com
If you have youw own template, you can use it, or you can download it from above mentioned website.

Once you storage account is created, let's make some changes in it.
  1. Open the storage account.
  2. In left pane of storage account, under data management search for static website option.
  3. Select that static website option, inside this enable the static website flag.
  4. For index document name provide the name of you index file for me it is index.html.
  5. For error document path either you can provide error.html or you can leave it blank.
  6. Now click on save and save it.
  7. Under left pane search for container option.
  8. Inside that you will find, you will find a container with name "$web".
  9. Open that container, click on upload option, a new window will get open.
  10. Now drag and Drop you whole template/Project folder in it, and upload it.
  11. Now get back to static website option from left pane and copy "Primary endpoint" and paste it in a new tab in browser.
  12. Your website/Template should be accessible now.

Note: This is just a method to deploy **Simple Static Website** and probably cheapest way to do it.
  
<img width="1259" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/d92272a4-3f2d-4d3e-968e-0ee399616005">
<img width="1237" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/bb7ade90-e4e7-4079-92d5-d2ef481a348f">
<img width="1262" alt="image" src="https://github.com/SRJ1307/BlobStorage/assets/157812379/086709ff-a3b2-4d0b-b695-9f5b1e47b94a">

