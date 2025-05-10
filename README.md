# Workflow Project
## Project Summary: Document Tracking and Review System

### Overview:
This project is a web-based document tracking system designed to manage and streamline document review workflows for a small team. It ensures controlled access, progress tracking, and automated email notifications, enhancing efficiency and accountability.
The user cannot edit or make changes to document within the tool. The tool is only used to send a mailn to the relevant parties and the user will need to download and review and upload the file if needed.

#### Tool Features: 
- Option to upload files.
- Submit documents.
- Send Mail to the next team and admin as per workflow design.

## What each role means.
Admin has full access to all the workflows. He can edit or change the status of any workflow.
Manager can assign a workflow to the member in his team or assign it to himself. The manager also approves the workflow after a memeber has worked on it.
Member can only see workflows assigned to him and can upload the document and send it for review. 

### Key Features:
#### User Authentication:
- Secure login system with username and password.
- Two roles: Team Member (restricted access), Team Manager and Admin (full access).

#### Document Tracking:
- Documents go through seven sequential review stages.
- Each stage is assigned to a specific team or admin for review and approval.
- Only the relevant team can edit and submit the document at their assigned stage.
- Admin has full access to all documents at any stage.
- Users can view progress but cannot edit outside their assigned stage.

#### Email Notifications:
- Automatic notifications sent when a document is ready for review.
- Relevant team and admin receive emails via SMTP integration.

#### Document Storage:
- Documents are securely stored in a centralized storage system.
- Ensures easy access, retrieval, and tracking.

### Workflow Summary:
1. User logs in and uploads a document.
2. Document is stored in Storage and assigned the initial stage.
3. Only the designated team can edit and submit the document.
4. Upon submission, the document progresses to the next stage.
5. Email notifications alert the relevant team and admin for the next review.
6. The process continues until final approval.
7. Admin can monitor and manage all documents and users.

For time being the storage is in my local system in "\storage"
user.json contains all user data
workflow.json contains all workflow data.

![Process Flow](C:/Users/teenu/OneDrive/Desktop/Ujwal/Software/Python/Workflow%20Project/Process%20Flow.jpg)
