## Automated Leave Request System
## Overview

This project is an automated Leave Request System built using Microsoft Power Platform tools. It digitises the traditional manual leave approval process by allowing employees to submit leave requests via Microsoft Forms, storing the data in SharePoint, and automating approval workflows through Power Automate with email notifications.

The system improves efficiency, tracking, accountability, and communication within an organisation.

## Tools Used
Microsoft Forms
Microsoft Power Automate
SharePoint Online
Outlook (Email Automation) 

##  System Workflow
Employee submits a leave request using Microsoft Forms
Response is automatically sent to Power Automate
Flow retrieves form response details
Data is stored in a SharePoint List
Manager receives an approval request email
Manager approves or rejects the request
System sends email notification to employee
SharePoint list updates the request status

## SharePoint List Structure

List Name: Leave Requests

Column Name	Type
Full Name	Single line of text
Email Address	Single line of text
Leave Category	Choice
Start Date	Date
End Date	Date
Reason	Multiple lines of text
Supporting Document	Attachment
Status	Choice (Pending, Approved, Rejected)

## Microsoft Form Fields

Form Name: Leave Request Portal

Full Name
Institution Email Address
Leave Category
Leave Start Date
Leave End Date
Reason for Leave

## Power Automate Flow Design

Trigger:

When a new response is submitted (Microsoft Forms)

## Actions:

Get response details
Create item (SharePoint)
Start and wait for an approval

## Condition:

If Outcome = Approve
Send approval email to employee
Update SharePoint status = Approved
Else
Send rejection email to employee
Update SharePoint status = Rejected
📧 Email Notifications

## The system sends:

Approval request email to the manager
Approval confirmation email to the employee
Rejection notification email to the employee

## Screenshots

## Microsoft Form Preview
<img width="1600" height="759" alt="Form Interface" src="https://github.com/user-attachments/assets/a5d27e76-2ccb-4e91-82d2-77f35a94bd02" />

## SharePoint List
<img width="1584" height="764" alt="Sharepoint List" src="https://github.com/user-attachments/assets/663738dc-dd18-4135-8220-810a74c09fca" />


## Power Automate Flow
<img width="1596" height="712" alt="Power Automate Flow" src="https://github.com/user-attachments/assets/31bfaad6-26b9-46eb-9676-7d026aab9eb1" />

## Approval Email 
<img width="1201" height="566" alt="Approval and Reject email" src="https://github.com/user-attachments/assets/f8b85a3b-18e9-4003-95b9-0aa954025ef0" />

## Project Outcome

This project demonstrates how a manual HR process can be fully automated into a digital workflow, improving:

Efficiency
Accountability
Tracking
Communication




## Author

Mashudu Motaung
Aspiring Cloud Engineer | Microsoft 365 Automation | Cloud & Support Enthusiast
