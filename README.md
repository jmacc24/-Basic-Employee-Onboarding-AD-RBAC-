# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
Northstar Medical lacked proper structure for their infrastructure, which was previously managed by an MSP. Every new user had to be manually granted access to different systems and resources, with no governance or audit trail to make the process seamless for admins. This created a risk of falling out of compliance due to lack of visibility into who was accessing what, as well as orphaned accounts and orphaned groups.

## Solution Overview
Created AD DS as the identity database for our users, with a DC (Domain Controller) as the mechanism that references AD DS during login and silently determines in the background what each user has access to. Established scopes in our infrastructure to enforce boundaries and prevent permission sprawl or accumulation. Added OUs for our four departments (HR, IT, Operations, Finance), containerizing each department to its own resources, and added users as members of their designated security groups, granting access to specific resources.

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
