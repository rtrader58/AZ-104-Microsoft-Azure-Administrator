# AZ-104T00 All Learning Paths Errata

Updated July 2024 <br>
 
# Learning Path 1: Manage identities and governance in Azure (90)

### LAB 01 - Manage Microsoft Entra ID Identities ~ Time 30 Min

Task 1: Create and configure user accounts  <br>
Step 5: Stay in the First AAD Tenant you created in the previous exercise  <br>

Task:  Create a new user  <br>
Step 2:  Copy the User Prinicipal Name and the password to notepad  <br>

### Lab 02a (Lab 2)  - Manage Subscriptions and RBAC ~ Time 30 Min

Task 2: Review and assign a built-in Azure role  <br>
Step 7: Select Help Desk Supprot person  <br>
Step 9: Hint Select Role Assignments  <br>

### Lab02b (Lab 3) - Manage Governance via Azure Policy ~ Time 30 Min

Task 3: Apply tagging via an Azure policy  <br>
Step 3: The policy is called Require a tag and its value on resources  <br>

### Lab 03 (Lab 4) - Manage Azure resources by Using Azure Resource Manager Templates ~ Time 50 Min

Task 2: Edit an Azure Resource Manager template and then redeploy the template  <br>
Step 5: disks_az104_disk1_name should be lines 6 and 15 az104-disk1 should be line 6  <br>
Step 9: Change disks_az104_disk1_name to disk_name should be line 5  <br>

Task 3: Configure the Cloud Shell and deploy a template with PowerShell <br>
Step 10:  Line 6 is the disk name <br>

Task 5: Deploy a resource by using Azure Bicep <br>
Step 6: Replace diskname in line 2 with az104-disk5 <br>

# Learning Path 2: Configure and manage virtual networks for Azure administrators

### Lab 04 (Lab 5) – Implement Virtual Networking ~ Time 40 Min

Task 2: Create a virtual network and subnets using a template > Deploy the custom template <br>
After step 3 add the following <br>
Select Edit parameters > Load the parameters.json you changed in the previous steps > Click Save <br>

### Lab 05 (Lab 6) – Implement intersite connectivity ~ Time 30 Min

No Errata <br>

### Lab 06 (Lab 7) – Implement traffic management ~ Time 60 Min

Task 2: Configure an Azure Load Balancer <br>
Add a rule to determine how incoming traffic is distributed <br>
Step 5:  I had to refresh over 20 time to get it to switch - if you understand the concept move on <br>

Task 3: Configure an Azure Application Gateway <br>
Step 5: Click Add <br>
Step 13: After configuring the step select review Review and Create <br>
Step 14: In the Add a route rule page select Add multiple targets to create a path-based rule <br>

## Learning Path 3: Implement and manage storage in Azure (~40 Min)

### Lab 07 (Lab 8) – Manage Azure storage ~ Time 40 Min

No Errata <br>

## Learning Path 4: Deploy and manage Azure compute resources (~150 Min)

### Lab 08 (Lab 9) – Manage Virtual Machines ~ Time 90 Min

Task 2: Manage compute and storage scaling for virtual machines <br>
Step 2:  Took ~15 minutes to complete  <br>
Task 2: Manage compute and storage scaling for virtual machines <br>

Task 3: Create and configure Azure Virtual Machine Scale Sets <br>
Step Delete the existing V-Net <br>

Task 4: Scale Azure Virtual Machine Scale Sets <br>
Scale out rule <br>
Step 1: Add a rule is in the yellow highlighted area <br>
Step 3: Add not Save <br>

Scale in rule <br>
Step 4: Add not Save <br>

### Lab 09a (Lab 10) – Implement Web Apps​ ~ Time 30 Min

No Errata <br>

### Lab 09b (Lab 11) – Implement Azure Container Instances​ ~ Time 15 Min

No Errata <br>

### Lab 09c (Lab 12) – Implement Azure Container Apps ​~ Time 15 Min

No Errata <br>

## Learning Path 5: Monitor and back up Azure resources (~95 Min)

### Lab 10 (Lab 13)– Backup virtual machines​ ~ Time 50 Min

Task 3: Configure Azure virtual machine-level backup <br>
Step 8: After the deployment is complet click Go to resource <br>

Task 4: Monitor Azure Backup <br>
Step 6: Diagnostic setting is located under Monitoring <br>

### Lab 11 (Lab 14) – Implement monitoring​ ~ Time 45 Min

Task 3: Configure action group notifications <br>
Step 1: Select Use action groups <br>
Step 4: Click review and create then Create to create the action group <br>

Task 4: Trigger an alert and confirm it is working <br>
It took 45 minutes before the alert email was recieved and created an alert in the Azure portal <br>

Task 6: Use Azure Monitor log queries <br>
Step 8:  There is an extra | in line 2, remove the first one <br>
