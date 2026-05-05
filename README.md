## SharePoint List Structure

## List Name: Leave Requests

Column Name	Type
Full Name	Text
Email Address	Text
Leave Category	Choice
Start Date	Date
End Date	Date
Reason	Multiple lines of text
Supporting Document	Attachment/File
Status	Choice (Pending, Approved, Rejected)
📝 Microsoft Form Fields

Form Name: Leave Request Portal

## Fields included:

Full Name
Institution Email Address
Leave Category
Leave Start Date
Leave End Date
Reason for Leave

## Create an automated cloud flow:

Trigger: When a new response is submitted
Action: Get response details
Action: Create item (SharePoint)
Action: Start and wait for an approval
Condition: Outcome = Approve
YES branch: Send Approved email + Update SharePoint status
NO branch: Send Rejected email + Update SharePoint status
📧 Email Notifications

## The system sends:

Approval request email to the manager
Approval confirmation email to the requester
Rejection confirmation email to the requester  

##  Project Outcome

This project provides a real-world example of automating a manual HR/admin process into a fully digital workflow, improving:

Efficiency
Tracking
Accountability
Communication

## Screenshots

Microsoft Form Preview
<img width="1600" height="759" alt="Form Interface" src="https://github.com/user-attachments/assets/a5d27e76-2ccb-4e91-82d2-77f35a94bd02" />

SharePoint List
<img width="1584" height="764" alt="Sharepoint List" src="https://github.com/user-attachments/assets/663738dc-dd18-4135-8220-810a74c09fca" />


Power Automate Flow
<img width="1596" height="712" alt="Power Automate Flow" src="https://github.com/user-attachments/assets/31bfaad6-26b9-46eb-9676-7d026aab9eb1" />

Approval Email 
<img width="1201" height="566" alt="Approval and Reject email" src="https://github.com/user-attachments/assets/f8b85a3b-18e9-4003-95b9-0aa954025ef0" />




## Author

Mashudu Motaung
Aspiring Cloud Engineer | Microsoft 365 Automation | Cloud & Support Enthusiast
