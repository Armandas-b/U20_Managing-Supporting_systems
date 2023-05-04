# Unit 20 Managing & Supporting Systems A2

This paper documents the management and support infrastructure of IT systems in a business.
It will cover the following points:

- Setting up PC's, server and printers
  - 30 PC's that share the same configuration which include:
    - Background image: ![Bg IMG](img/Logo.PNG)
    - Shortcuts to some apps listed below:
      - Word
      - Excel
      - Calculator
      - File Explorer
      - Google Chrome
  - A server which provides the following shared folders:
    - General folder
    - Policies and procedures folder
    - Management folder

Following the table below access control will be set up for the shared folders:

| Folder | User | Read | Write | Full |
|:-------|:-----|:-----:|:------:|:----:|
|General|All|-|-|X|
|Policies and procedures|Jr. Staff, Managers|X|-|-|
|Management|Managers|X|-|-|
|Management|Jr. Staff|-|-|-|
|All|Directors|-|-|X|

A mock-up of the management and support infrastructure which includes:

- Network code of practice
- Support request and escalation procedures
- contingency plan
- user support documentation
- security policy, access control and traffic management expectations
- user desktop interface
- backup procedures

## Planning

Using task management tool ('Click Up') I have created a list of tasks that need to be completed in order to set up the infrastructure. The tasks are listed below as a Gantt chart:

![Task List](img/TaskList.PNG)

Each task progress can be documented inside, also the tasks can be assigned a status and a priority.
I decided to go with these Statues:

- Mockup - The task is not yet started/ or is being written up as a draft
- Implementation - The task is being worked on and implemented.
- Complete - The task is completed.

![Statuses](img/Status.PNG)

## System Setup

College Computers do not allow for the creation of different accounts **To be done at home**

------

## **Managing and Supporting Systems documentation**

## Network code of practice

The network code of practice is a document that outlines the rules and regulations of the network. It is important to have this document as it will help to keep the network secure and running smoothly. The document will be available to all users of the network and will be signed by them to show that they have read and understood the rules.

The document will include the following:

- Responsible and ethical use of the network

- Regular maintenance of the network and the standard

- Access control

- Network Traffic monitoring

- Network incident reporting/response

The document will be signed by all users of the network and will be reviewed every 6 months.

The document can be found in this folder named 'CWA ENTERPRISE Network Code of Practice.docx'

Below is a screenshot of the completed task in 'Click Up':
![Plan](img/Following_the_plan1.PNG)

## Support request and escalation procedures

The support request and escalation procedures are a set of rules that need to be followed when a user has a problem with their computer. The document will be available to all users of the network and will be signed by them to show that they have read and understood the rules.

The document will include the following:

- How and where to report a problem

- What to do if the problem is not resolved

The document will be signed by all users of the network and will be reviewed every 6 months.

The document can be found in this folder named 'CWA ENTERPRISE Support Request and Escalation Procedures.docx'

Below is a screenshot of the completed task in 'Click Up':
![Plan](img/Following_the_plan2.PNG)


## Service Level Agreement

The service level agreement is a document that outlines the level of service that the IT department will provide to the users of the network. The document will be available to owners of the business and will be signed by them to show that they have read and understood the terms.

The document will include the following:

- Service description

- Service availability

- Respone/Resolution times

- Costumer duties

- Service credit

- Termination

- Law

- Entire agreement

The document will be signed by the owners of the business and will be reviewed every 2 years.

The document can be found in this folder named 'CWA ENTERPRISE Service Level Agreement.docx'

Below is a screenshot of the completed task in 'Click Up':

![Plan](img/Following_the_plan3.PNG)

### User support documentation

The user support documentation is a set of documents that will help the users of the network to resolve common problems in the system thus reducing amount of issues raised. The guide will be available to all users of the network and will be reviewed every 2 months(DEPENDING ON HOW MUCH IT HELPS).

The document will include the following:

- How to resolve common problems

- How to contact the IT department

- How to submit an issue via ClickUp

Below is a screenshot of the completed task in 'Click Up':

![Plan](img/Following_the_plan4.PNG)

## Security policy, access control and traffic management expectations

Security policy is a document that outlines the rules and regulations of the network. It is important to have this document as it will help to keep the network secure and contained from outside threats.

The document will include the following:

- Password policy
  
- Traffic management

  Includes:

  - Firewall

  - Intrusion detection system(IDS)

  - Virtual Private Network(VPN)

- Incident response

- Compliance

- Enforcement

Below is a screenshot of the completed task in 'Click Up':

![Plan](img/Following_the_plan5.PNG)

## Backup procedures

Backup procedure will define how the data will be backed up by the organisation.

The document will include the following:

- Backup schedule

- Backup location

- Compliance

Below is a screenshot of the completed task in 'Click Up':

![Plan](img/Following_the_plan6.PNG)


## Network and System requirements

System and network requirements are critical considerations when deploying software or applications within a business organization. In order to ensure optimal performance and avoid any technical difficulties, it's important to have the appropriate hardware and software specifications in place.

For a business organization that requires 30 computers and printers, it's recommended to have at least one server to manage the network and data storage. The server should meet the following specifications:

Processor: A modern multi-core processor with clock speeds of 2 GHz or higher.
Memory (RAM): At least 8 GB of RAM or higher, depending on the number of users and applications that will be running on the server.
Storage: Sufficient storage capacity to accommodate the organization's data needs. For example, 1 TB or more of hard disk space may be required.
Operating system: A server operating system such as Windows Server or Linux that is compatible with the organization's applications and network infrastructure.

For the 30 computers, the minimum system requirements should be as follows:

Processor: A modern multi-core processor with clock speeds of 2 GHz or higher.
Memory (RAM): At least 4 GB of RAM or higher, depending on the applications that will be used.
Storage: At least 500 GB of hard disk space or more, depending on the amount of data that will be stored locally.
Operating system: A modern operating system such as Windows 10 or macOS that is compatible with the organization's applications.
The printers should be network-enabled and compatible with the organization's network protocols. It's recommended to choose printers with high-capacity ink or toner cartridges to minimize the need for frequent replacements.

In terms of network requirements, the organization should have the following:

Sufficient bandwidth to accommodate the number of users and data transfer needs.
Low latency to ensure smooth communication between the computers, printers, and server.
Adequate security measures, such as firewalls and anti-virus software, to protect against potential cyber threats.
Overall, having the appropriate system and network requirements in place can help ensure that the business runs smoothly and efficiently. It's important to consult with IT professionals to ensure that the organization's hardware and software infrastructure is optimized for the business's specific needs.

## User desktop interface(System setup)

System setup consists of the following requirements:

- Applications:
  - Word(Word processing software)
  - Excel(Spreadsheet software)
  - Google Chrome(Web browser)

- Uniform desktop background
  - The desktop background should be the same for all users of the network. This will help to keep the network uniform and professional
  
    ![bg](Img/Logo.PNG)

- Relevant folders

  - Only the users that have access to the specifc folder may see it on the desktop. This will help to avoid clutter on the desktop and keep it clean.

### Setting up the shared folders

1. Right click on the folder that you want to share and select 'Properties'

    ![properites](Img/properties.PNG)

2. Select the 'Sharing' tab and click on 'Advanced Sharing'

    ![sharing](Img/sharing.PNG)

3. Tick the box that says 'Share this folder' and click on 'Permissions'

    ![permissions](Img/permission.PNG)

4. Select the users that you want to have access(Read, Write, Full) to the folder and click on 'OK'

5. Apply changes and click on 'OK'

6. Repeat the process for all the folders that you want to share

### Setting up the desktop background

1. Win + R and type 'gpedit.msc' and click on 'OK'

    ![gpedit](Img/gpedit.PNG)

2. Navigate to 'User Configuration' -> 'Administrative Templates' -> 'Desktop' -> 'Desktop'

    ![desktop](Img/desktop.PNG)

3. Double click on 'Desktop Wallpaper'

    ![wallpaper](Img/wallpaper.PNG)

4. Select 'Enabled' and type in the path to the image that you want to use as the desktop background and press 'Apply' and 'OK'

    ![path](Img/path.PNG)

5. Right click on the Start Menu Button and select command prompt or command prompt (Admin) to open the CMD window. Type: gpupdate /force and hit ENTER.

    ![gpupdate](Img/gpupdate.PNG)

6. Close the CMD window and check if the desktop background has changed (May require to sign out and sign in again)

    ![dbg](Img/dbg.PNG)


### Final result

This section will show what the desktop will look like for each user type.

#### Jr. Staff

![jr](Img/jr.PNG)

#### Managers

![ManagerDesktop](Img/ManagerDesktop.PNG)

#### Directors

![DirectorDesktop](Img/DirectorDesktop.PNG)

## Testing, Optimisation and Evaluation

For testing my solution I have decided to share my folders with my colleagues and ask them to give me feedback on the solution and the policies.

To keep track of all my feedback my peers have written the feedback in a relevant clickup task like this:

![feedback](Img/feedback.PNG)
### Feedback section:

|ID|Feedback|Document in review|
|---|---|---|
|1|![Network COP](Img/NetworkCOP.PNG)| Network Code of Practice|
|2|![Escalation](Img/Escalation.PNG.jpg)| Support & Esclation procedures|
|3|![UserSupport](Img/UserSupport.PNG)| User Support Documentation|

## Issue tracking via clickup

Clickup is a project management tool that allows you to create tasks and assign them to people. It also allows you to create subtasks and checklists to keep track of the progress of the task.

Clickup also allows you to create a 'Space' which is a collection of folders that are related to each other.

I have decided to use clickup to track network issues in the organisation. I have created a list called 'Issue_Tracking', which will allow employees to create issues as tasks(with a template) and assign them to the IT department.

![issue](Img/issue.PNG)

The issue task then can be used for communications, updates and to keep track of the progress of the issue.

![statuses](Img/StatusesIssues.png)

- Issue raised: The issue has been raised by an employee and is waiting to be recognised by the IT department

- Issue escalated: The issue has not been resolved or has taken too long to resolve and has been escalated to the next level

- Issue troubleshooting: The issue is being investigated and fixed by the IT department

- Issue fixed: The issue has been fixed and the employee has been notified, no further action needed.

- Out-Of-Date: To avoid clutter on the board, the issue will be deleted or archived after 30 days of being fixed.

### Tracking issues

For the issue not to get lost the template has been created to ensure that all the relevant information is provided, click up also allows provides task ID's and custom ID's to keep track of the issues. The task will also have set dates.

### Testing the solution

To test the solution I have been provided with a list of sample issues that I have to resolve. The issues are as follows:

|ID|Issue|
|---|---|
|1|"I am unable to access my email account through the company's email server. Can you help me troubleshoot this issue?"|
|2|"I cannot access any of the shared files on the network. Is there something wrong with the network settings?"|
|3|"I am receiving an error message when I try to access a specific website. Is there something wrong with the network or is it a problem with the website?"|

Now to begin troubleshooting the issues the user will have to provide the information in this format

1. He creates a new task and selects the template 'Report an issue'

    ![template](Img/template.PNG)

2. He fills out the template and provides the information that is required

    Issue #1:

      The user has provided the following information and started a thread in the task to communicate with the IT department:

      ![info](Img/info1.PNG)

      IT Technician has responded to the issue and has asked the user to provide more information(This information will be stored in the task description to keep note for the future):

      ![info2](Img/info2.PNG)

      IT Technician has set the task as 'Issue troubleshooting' and has started to troubleshoot the issue:

      ![info3](Img/info3.PNG)

      IT Technician has fixed the issue and has set the task as 'Issue fixed':

      ![info4](Img/info4.PNG)

    Issue #2:

      The user has provided the following information and started a thread in the task to communicate with the IT department:

      ![info5](Img/info5.PNG)

      IT Technician has responded to the issue and has asked the user to provide more information(This information will be stored in the task description to keep note for the future):

      ![info6](Img/info6.PNG)

      IT Technician has set the task as 'Issue troubleshooting' and has started to troubleshoot the issue. The IT Technician has also escalated the issue to the next level(Due to the issue being more complex):

      ![info7](Img/info7.PNG)

      The IT technician has found out that Jr. Staff is trying to access a folder without clearance, the IT technician has informed the user that he should not be able to access the folder and has noted down the possible security concerns in the task description, to make sure that directors are aware of the issue:

      ![info8](Img/info8.PNG)

      ![info9](Img/info9.PNG)

      The network not found error was caused by the user not being able to access the folder, the issue has been fixed, but the task will remain escalated due to potential security concerns.

    Issue #3:

      The user has provided the following information and started a thread in the task to communicate with the IT department:

      ![info10](Img/info10.PNG)

      IT Technician has responded to the issue and has asked the user to provide more information(This information will be stored in the task description to keep note for the future):

      ![info11](Img/info11.PNg)

      IT Technician has fixed the issue like this:

      ![info12](Img/info12.PNG)

## Justification of the solution

### Documents

#### Network Code of Practice

This document outlines the standard operating procedures for managing and maintaining the network. It helps ensure that all IT staff and users follow the same protocols, thereby reducing the risk of errors, system failures, and security breaches.

#### User Support Documentation

This document provides users with the necessary information to troubleshoot basic issues on their own without relying on IT support. It also helps IT support to address user issues more efficiently, as users can provide detailed information about the issue they are facing.

#### Backup procedures

This document details the backup procedures for critical data, applications, and system settings. It ensures that data is backed up regularly, reducing the risk of data loss due to hardware or software failures, natural disasters, or cyber-attacks.

#### Serivce Level Agreement(SLA)

This document specifies the expected level of service from IT support and outlines the responsibilities of both IT support and users. It helps manage user expectations and sets clear guidelines for resolving issues in a timely and efficient manner.

#### Support & Escalation procedures

This document outlines the steps that IT support staff should take when they encounter an issue that they are unable to resolve. It ensures that issues are escalated to the appropriate person or team, ensuring timely resolution and reducing downtime for users.

#### Security Policy

This document outlines the policies, procedures, and guidelines for securing the network and protecting sensitive information from unauthorized access or theft. It helps ensure that all users and IT staff are aware of their responsibilities in maintaining network security and minimizing the risk of data breaches.

### Desktop interface

A unified desktop interface can bring several benefits to a business.

First, it can improve the overall user experience by providing employees with a consistent and familiar interface across all applications and tools they use in their daily work. This can reduce the learning curve for new tools and increase productivity by reducing the time spent switching between different interfaces.

A unified desktop interface can simplify IT management by reducing the number of different interfaces and tools that need to be supported. This can reduce the workload for IT staff and lower the overall IT costs for the business.

Similar desktop interface can enhance security by enforcing consistent security policies across all applications and tools. This can reduce the risk of security breaches and improve compliance with regulatory requirements.

### Use of Clickup to track issues

ClickUp is an effective tool for tracking IT issues for several reasons. It allows IT teams to easily create, assign, and prioritize tasks, ensuring that nothing falls through the cracks. The ability to attach files and add comments to tasks means that important information is readily available, reducing the need for additional communication and speeding up the resolution process.

Customizable task statuses and workflows which make it easy for teams to track the progress of issues and identify any bottlenecks. It also provides automated notifications, keeping team members up-to-date on changes and ensuring that everyone is on the same page.

Useful features that can be used across IT teams, such as time tracking, integrations with other tools(like GitHub). This can help teams to improve their productivity and efficiency and bring everything together in one place.

It provides a centralized platform for IT teams to track, manage, and resolve issues quickly and efficiently
