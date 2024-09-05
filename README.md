# Create-Flow-Logs

Search storage account
![Screen Shot 2024-09-04 at 4 02 45 PM](https://github.com/user-attachments/assets/12c9af2f-0ed6-4883-b027-db406044f836)

Click "+ Create"
![Screen Shot 2024-09-04 at 4 36 46 PM](https://github.com/user-attachments/assets/24faf367-3ac2-4c04-b66a-c2d95d19d69a)

Select your “subscription” and “resource group” that the VMs you have are on. Make sure you select the same “region” as the VMs as well. Select standard for “performance”. Click “Review + Create” and when it is done click “Create”.
![Screen Shot 2024-09-04 at 5 05 43 PM](https://github.com/user-attachments/assets/9b0b8e37-e25c-4c33-8f16-98e2fcf0595b)

Search NSG or Network Security Groups. Select the windows or linux VM. Doesnt matter which one you will put them both in flow log.
![Screen Shot 2024-09-04 at 6 32 56 PM](https://github.com/user-attachments/assets/f34bc753-1bc9-4263-80cc-5dcdc71b15fa)

Select your “Subscription”. Flow log type should be Network security group. Click “+ Select target resource”
![Screen Shot 2024-09-04 at 7 20 41 PM](https://github.com/user-attachments/assets/50e91ec4-861b-4c48-aa3f-471502233d85)

Select both VMs like as said before. Then click "Confirm selection".
![Screen Shot 2024-09-04 at 7 38 04 PM](https://github.com/user-attachments/assets/f8d0ac14-a9b8-4e06-97c4-942707ba3a83)

Subscription and Storage accounts should be the same as earlier. Retention days should be 60. Then select “Next”
![Screen Shot 2024-09-04 at 7 53 13 PM](https://github.com/user-attachments/assets/ffef9e52-4868-4d59-ba96-b45671f3a0c1)

Make sure to use Flow Log Version 2. Enable traffic analytics. Processing interval should be Every 10 mins. Same subscription and workspace as before. Click "Review + create". Click "Create" again when available
![Screen Shot 2024-09-04 at 9 52 02 PM](https://github.com/user-attachments/assets/9464d430-07aa-485e-a184-b0e08387bf94)
