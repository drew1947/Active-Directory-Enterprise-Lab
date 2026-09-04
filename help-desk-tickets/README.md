# Help Desk Ticket Lab

## Overview

I created this part of the project to practice handling support requests from beginning to end instead of only making changes in Active Directory.

The tickets are based on situations that could happen in a real business environment at BWA Stay Hotel. I used Jira Service Management and Spiceworks to keep track of each request, the work I completed, and the final result.

## My Ticket Process

For each ticket, I worked through the same basic process:

1. Read the request and identify the actual problem.
2. Check the affected user, computer, group, or resource.
3. Investigate the configuration before making changes.
4. Complete the needed work in Active Directory, PowerShell, Group Policy, or Windows Server.
5. Test the change from the Windows 11 client when needed.
6. Update the ticket with what I did.
7. Verify the issue was resolved before closing it.

![BWA Stay Hotel help desk ticket workflow](../screenshots/help-desk-ticket-workflow.png)

## Types of Tickets Practiced

### Account Support

- Password resets
- Locked account troubleshooting
- Disabled account review
- Login problems

### User Administration

- New-user provisioning
- Department or role changes
- Security-group membership updates
- Employee offboarding

### Access Support

- Department shared-folder access
- Mapped-drive problems
- File and NTFS permission troubleshooting
- Removing access that was no longer required

### Windows and Domain Support

- Domain login troubleshooting
- Group Policy application problems
- DNS and connectivity checks
- Windows 11 client verification

## What I Document for Each Ticket

A completed ticket case study includes:

- The original request
- The affected user or system
- What I checked during the investigation
- The cause of the issue
- The action I took
- Screenshots showing the work
- How I tested the result
- The final resolution entered in the ticket

I use the established BWA Stay Hotel employee roster when creating tickets for existing users. New names are only introduced when the ticket is specifically for a new hire. This keeps the lab consistent and makes the support scenarios connect to the same business environment.

## Skills This Lab Demonstrates

- Help desk ticket ownership
- Active Directory account support
- User provisioning and offboarding
- Role-based access management
- Security-group administration
- Password and account-lockout support
- File-permission troubleshooting
- Group Policy troubleshooting
- PowerShell verification
- Testing and documenting resolutions
- Communicating technical work clearly
