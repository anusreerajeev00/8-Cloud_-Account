# Task 8 - Cloud Account (Alternative Path using Azure CLI)

## Objective
This task is to learn the basics of cloud computing, compare free-tier offers of cloud providers, and demonstrate cloud access using CLI when a new cloud account signup is not possible.

---

## Cloud Provider Used
Microsoft Azure (Azure CLI on Linux)

---

## Why I Used the Alternative Path
I was unable to create a new cloud account using Azure / GCP / AWS websites due to signup or verification errors.
So I completed this task using the Azure CLI device-code / no-browser login method.

---

## What I Accomplished

### A) Authenticate via CLI
- Logged in using Azure CLI device-code login (browser approval required)
- Confirmed login success and subscription context using CLI output

### B) Discover Basic Account Context
- Verified which account identity is active
- Verified the active subscription
- Listed available Azure regions/locations

### C) List Cloud Resources
- Listed existing resource groups
- Listed currently available resources (even if empty)
- Listed enabled/registered Azure providers/services

### D) Create and Cleanup Something Safe
- Created a safe Azure Resource Group
- Verified it exists
- Deleted the Resource Group (cleanup)
- Confirmed it was removed successfully

### E) Alternative Path Acknowledgement
- Cloud provider used : Microsoft Azure  
- Login method used : Azure CLI device-code / no-browser login (no passwords shared)  
- What this demonstrates : This submission proves CLI-based Azure access and operations even without completing a new cloud account signup  
- Security note : Temporary access used for this task was revoked/removed after completion  

---

## Repository Contents
- `research.md` → Free tier comparison of cloud providers (Part A)
- `steps.md` → Detailed steps followed for login and operations (Part B–D)
- `cli-proof/commands-used.txt` → Commands used in terminal
- `cli-proof/outputs.txt` → Terminal outputs as proof (A–D)

Note : Sensitive information such as full subscription IDs, tenant IDs, and emails are masked/hidden.
