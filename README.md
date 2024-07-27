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
2. **Activate PDQ Deploy:**
   - If you're using the free version, continue without activation.
3. **Download 7-Zip Package:**
   - Go to the Package Library tab.
   - Search for "7-Zip" and download the package.

### Step 4: Deploy 7-Zip Using PDQ Deploy
1. **Create Deployment Package:**
   - Select the downloaded 7-Zip package.
2. **Add Targets:**
   - Click "Deploy Once" and choose your target computers (e.g., from AD, manual entry, or import from file).
3. **Deploy 7-Zip:**
   - Click "Deploy Now" to start the deployment.
4. **Monitor Deployment:**
   - Monitor the deployment progress in the PDQ Deploy console.
5. **Verify Deployment:**
   - Confirm that 7-Zip is installed on the target machines.
