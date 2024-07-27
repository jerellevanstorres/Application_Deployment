# Windows 10 Deployment and Configuration Lab

## Overview
This lab demonstrates the deployment and configuration of Windows 10 systems using PDQ Deploy for on-premises software deployment.

## Table of Contents
1. [Objective](#objective)
2. [Tools Needed](#tools-needed)
3. [Part 1: PDQ Deploy for 7-zip](#part-1-pdq-deploy-for-7-zip)
   - [Step 1: Download and Install PDQ Deploy](#step-1-download-and-install-pdq-deploy)
   - [Step 2: Prepare Your On-Premise Environment](#step-2-prepare-your-on-premise-environment)
   - [Step 3: Download 7-zip Package from Package Library](#step-3-download-7-zip-package-from-package-library)
   - [Step 4: Deploy 7-Zip Using PDQ Deploy](#step-4-deploy-7-zip-using-pdq-deploy)


## Objective
Showcase deployment and management of Windows 10 systems using PDQ Deploy

## Tools Needed
- PDQ Deploy Free Version

# PDQ Deploy for 7-Zip

### Step 1: Download and Install PDQ Deploy
1. **Download PDQ Deploy:**
   - Visit the [PDQ Deploy download page](https://www.pdq.com/pdq-deploy/) and download the latest version.
   ![Download PDQ](https://github.com/user-attachments/assets/57168067-196d-4394-8441-0c56be474c83)
2. **Install PDQ Deploy:**
   - Run the installer and follow the installation prompts.

### Step 2: Prepare Your On-Premise Environment
1. **Set Up Active Directory:**
   - Ensure you have an Active Directory domain set up.
   - Join the computers you want to manage to the AD domain.
2. **Network Configuration:**
   - Ensure all devices are connected to the same network.

### Step 3: Download 7-Zip Package from Package Library
1. **Launch PDQ Deploy:**
   - Open PDQ Deploy from your Start menu or desktop shortcut.
   ![Welcome PDQ](https://github.com/user-attachments/assets/1033f369-51f8-4977-9953-6d8d45a3a574)
2. **Activate PDQ Deploy:**
   - If you're using the free version, continue without activation.
       ![PDQ Main](https://github.com/user-attachments/assets/b1ce8e30-9296-412a-9187-8a94f5c060c2)
3. **Download 7-Zip Package:**
   - Go to the Package Library tab.
   - Search for "7-Zip" and download the package.
   ![package library](https://github.com/user-attachments/assets/75831313-6abd-45cb-bd61-9f2dd747000d)


### Step 4: Deploy 7-Zip Using PDQ Deploy
1. **Create Deployment Package:**
   - Select the downloaded 7-Zip package.
   ![7 zip install](https://github.com/user-attachments/assets/668e273b-d6af-4dea-8530-9dc7aa7d1422)

   ![deploy once](https://github.com/user-attachments/assets/47bc95a5-3b58-4ced-be6f-f9587b1438df)
2. **Add Targets:**
   - Click "Deploy Once" and choose your target computers (e.g., from AD, manual entry, or import from file).
   ![Deploy targets](https://github.com/user-attachments/assets/d3164e97-9ab3-497d-8b2a-e31cbd3363ed)
3. **Deploy 7-Zip:**
   - Click "Deploy Now" to start the deployment.
4. **Monitor Deployment:**
   - Monitor the deployment progress in the PDQ Deploy console.
   ![deployment in progress](https://github.com/user-attachments/assets/baa8da4b-98c3-4d5a-b73e-874f3938232c)
5. **Verify Deployment:**
   - Confirm that 7-Zip is installed on the target machines.
   ![zip deployed](https://github.com/user-attachments/assets/c3ffe960-165b-4d6c-aa98-a07a9081e6bd)

