# osTicket Ticket Management Lab

## Environments and Technologies Used
- **Microsoft Azure**: Utilized Virtual Machines for a remote environment.
- **Remote Desktop Protocol (RDP)**: Accessed the virtual machine for hands-on configuration.
- **Internet Information Services (IIS)**: Configured IIS to host the osTicket application.

## Operating Systems Used
- **Windows 10**

## Lab Objectives
1. **Create and Manage Tickets**: Practice ticket creation as an end-user, then observe and respond to tickets as a help desk agent.
2. **Department and Permission Management**: Modify department hierarchy and permissions, reinforcing control over ticket visibility.
3. **SLA and Ticket Properties**: Apply SLAs and assign tickets to appropriate departments and agents.

## Ticket Lifecycle Stages
1. **Intake**: Initial creation of tickets by end-users through the osTicket system.
2. **Assignment and Communication**: Assign tickets to appropriate departments and set SLA and priority. Communication with users is managed through ticket updates, which can trigger email notifications.
3. **Working the Issue**: Agents work the ticket through troubleshooting steps or escalations.
4. **Resolution**: Completing and closing tickets, ensuring issues are fully resolved.

## Key Configuration Steps and Skills Demonstrated

### Department Configuration
- **Change Department Hierarchy**: Promoted the **SysAdmins** department to a top-level department.
- **Delete Maintenance Department**: Completely removed the Maintenance department from the system (not archived).

### Ticket Workflow Examples
1. **Ticket 1**: Mobile/Online Banking System Outage
   - **Created by End User**: Entire mobile/online banking system is down.
   - **Help Desk Agent (John)**: Observed properties (Priority, Department, SLA, Assigned To).
   - **Properties Set**: **SLA: Sev-A (1 hour, 24/7)**, **Department: Online Banking**.
   - **Ticket Completed by Agent (Jane)**.

2. **Ticket 2**: Adobe Upgrade Issue in Accounting
   - **Created by End User**: Accounting department needs an Adobe upgrade.
   - **Help Desk Agent (John)**: Observed and set ticket properties.
   - **Properties Set**: **SLA: Sev-B (4 hours, 24/7)**, **Department: Support**.
   - **Ticket Completed by Agent (John)**.

3. **Ticket 3**: CFO’s Laptop Not Powering On
   - **Created by End User**: CFO’s laptop will not turn on.
   - **Help Desk Agent (John)**: Observed and set ticket properties.
   - **Properties Set**: **SLA: Sev-B (4 hours, 24/7)**, **Department: Support**.
   - **Ticket Completed by Agent (John)**.

### Escalation and Access Control
- **Escalate Tickets**: Set **Sev-A** priority for a SysAdmins ticket, rendering it inaccessible to certain agents.
- **Admin Panel Adjustment**: Re-assigned view-access to agents for escalated tickets, demonstrating permission management in escalated scenarios.

