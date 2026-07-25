# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
This project was based on a fictional company called NorthStar Medical Group. The company a poor IT infrastructure that resulted because it was initially set up by a third-party MSP (Managed Service Provider). Their identity infrastructure lacked RBAC policy in place and no audit trail, resulting in one of many concerns including violating HIPAA compliance because employees had different levels of access based on their roles. 

## Solution Overview
The solution was to setup a Active Directory domain for the company so that each employee would have access to their systems. This solved the identity infrastructure issues by setting up Organizational Units (OUs) and applying different security policies. I then set up a domain controller to manage the domain and ensure that each employee logging in was properly authenticated.  A Role-Based Access Control (RBAC) model was implemented so employees were only granted access to the resources required for their role.
## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* I accomplished setting up a centralized system that allowed the company to become more secure and organized and fully documented every step of the process.
*I completed a mock support ticket where I discovered an employee had the wrong level of access because they were placed in the wrong Organizational Unit (OU).
