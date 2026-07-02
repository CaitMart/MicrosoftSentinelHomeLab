# Microsoft Sentinel Lab Setup


The setup for the lab involved creating a resource, creating a log analytic workspace to ingest the data into Sentinel.

## Step 1 
1. Log into the Azure portal and search for Sentinel in the search bar. 
2. Create a new workspace 
3. Choose subscription, resource group, workspace name, and region*
4. Select review + create, then finalize it by selecting create

*The region selected in the workspace and resource creation must match. 

<img width="1028" height="487" alt="create workspace pic 1" src="https://github.com/user-attachments/assets/44b90706-72d8-4200-890a-3c59d79449c4" />

## Step 2 
Add Microsoft Sentinel to the workspace that was created in Step 1

## Step 3 
Connect your workspace to Sentinel by going to the Defender Portal (The Sentinel Portal in Azure has moved to Defender)


##Step 4
Now you can deploy the Microsoft Sentinel Training Lab solution that I found on Microsofts Community Hub. 
Ensure that regions match and that you use the same subscription, resource group, and workspace that was created earlier. 

<img width="890" height="598" alt="lab environment deployment pic 2" src="https://github.com/user-attachments/assets/171e5be2-4de7-4e94-8b7e-25951f16218d" />


