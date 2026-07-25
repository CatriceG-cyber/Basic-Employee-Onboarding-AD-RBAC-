# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
While working at NorthStar Medical Group, they were dealing with a poor infrastructure due to an MSP's disorganized initial setup. One of the main risks they were concerned about was HIPAA compliance because employees had different levels of access based on their roles. When an employee left the company, their access was not always disabled, creating a risk that someone could access confidential information. Additionally, employee accounts were set up manually within the infrastructure, and there was no documentation of their permissions or passwords.

## Solution Overview
I created an Active Directory domain for the company so that each employee would have access to their systems. This solved the identity infrastructure issues by setting up Organizational Units (OUs) and applying different security policies. I then set up a domain controller to manage the domain and ensure that each employee logging in was properly authenticated. I also created security groups to organize users based on their job roles and make permission management more efficient. A Role-Based Access Control (RBAC) model was implemented so employees were only granted access to the resources required for their specific responsibilities, helping improve security and support HIPAA compliance.
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
* [Add your second key accomplishment here]
* [Add your third key accomplishment here]
