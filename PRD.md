# PRODUCT REQUIREMENTS DOCUMENT (PRD) by Commit Crew

1. Document Information

-   Product Name: HostelFix
-   Version: 1.0
-   Authors: Commit Crew
-   Date: 11/23/2026
-   Status: Draft

2. Product Overview

HostelFix is a web-based hostel maintenance reporting system designed to
track maintenance issues in hostels and act as a bridge between the
students, hall administrators and artisans.

The application allows students to register and login, input their room
and hall details, publish their complaints/issues in the management
system then track, verify and receive updates on the status of the issue
reported.

The system will also provide an interface for the hall administrators to
receive the complaints and tools to assign an artisan to the issue
according to the category. The artisans are not left out as users, they
can receive notifications on categorized issues in the rooms which
allows for seamless maintenance.

The primary objective is to eliminate the time-consuming process of
manually reporting an issue to a hall administrator where in the end,
the matter is not urgently attended to.

#3. Problem Statement

Hostel residents in Babcock University experience maintenance issues
such as faulty switches, damaged furniture, empty taps or mold
infestations. However, reporting these issues can go unheard and become
difficult when making verbal complaints

In a hall of 700 six-person rooms, students rely on verbal complaints
and informal communication to report their maintenance issues. This
results in delayed responses, half solved problems or even difficulties
tracking the progress of reported issues.

This is where HostelFix comes in, a hostel maintenance reporting system
that helps residents to submit complaint forms and receive progress
reports on the issue while hall administrators manage the requests and
assign maintenance tasks to artisans.

Key problems:

1.  Inefficient reporting
2.  Poor tracking
3.  Delayed Responses
4.  Communication gaps
5.  Improper categorization of maintenance issues

## 4. Goals and Objectives

i.  Simplify maintenance reporting: Provide students with an accessible
    platform for reporting hostel maintenance issues.

ii. Improve communication: Establish a more effective communication
    channel between students, hall administrators and artisans

iii. Improve issue categorization: Allow maintenance complaints to be
     categorized according to their nature such as electrical, plumbing,
     carpentry and so on

## 5. Stakeholders(i-iv) and Target users(ii-iv)

i.  The founder- needs business growth and product success

ii. The student-  needs to communicate issues to hall admin and track it
    to be solved as quickly as possible

iii. The hall admin- needs to categorize the issues and assign the
     issues to the respective artisans on a schedule to reduce costs and
     expenses.

iv. The artisans- needs to know maintenance issue to be solved.

# 6. Functional Requirements


           Description         
  
  FR-01  Students, hall admins   
        and artisans can        
        register and log in     

  FR-02 Students must specify   
        hostel details and      
        submit maintenance      
        complaints              

  FR-03  Students must be able   
        to upload photographs   
        of the reported issues  

  FR-04  Students must select a  
        category that describes 
        the issue               

  FR-05  Administrator must be   
        able to filter          
        complaints by category  

  FR-06  Administrator must be   
        able to assign tasks to 
        artisans                

  FR-07  Artisans must be able   
        to view maintenance     
        requests                

  FR-08 Students must be able   
        to view status of       
        submitted complaints    

  FR-09  Artisans must be able   
        to provide updates on   
        tasks                   

  FR-010 Administrator must have 
        access to maintenance   
        history                 
  

# 7. Non-Functional Requirements

-   Performance: The system should load its main pages within 3 seconds
    under normal network conditions.
-   Security: The system must implement role-based access control to
    restrict access to unauthorized users
-   Availability: The system should be accessible to authorized users
-   Scalability: The system should accommodate an increasing number of
    students, administrators, and artisans
-   Usability: The complaint reporting process must require minimal
    steps
-   Reliability: The system must record submitted maintenance complaints
    accurately

# 8. User Stories

-   As a student, I want to submit maintenance so that hostel management
    can be informed about issues in my room.
-   As a hall administrator, I want to assign maintenance requests to
    artisans based on their expertise so that issues are handled by
    qualified personnel.
-   As an artisan, I want to update the status of assigned maintenance
    requests so that administrators and students can monitor progress.

# 9. Acceptance Criteria

i.  User Registration and Login:

-   Targeted users can create accounts using the required registration
    information

ii. Maintenance complaint submission

-   Students can submit a maintenance complaint, attach photographs of
    the issue, select a category, and receive confirmation

iii. Complaint tracking

-   Allows students to track their complains while administrators and
    artisans update request statuses throughout the maintenance process

iv. Notifications

-   Users receive notifications when important complaint activities
    occur

v.  Categorization and Review

-   Complaints can be categorized, reviewed and reclassified by
    administrators

# 10. Scope and Priorities

  In-Scope (MVP)

i.  User Authentication and Access Control
-   Account login for students, hall administrators, and artisans.
- Only authorized users can log in
ii. Maintenance issue reporting

-   Submission of maintenance complaints.
-   Description of reported issues.
-   Uploading photographs of maintenance problems.

iii. Complaint Tracking 
-   Tracking complaint progress.


iv. Maintenance Request Management
-   Viewing and organizing submitted complaints.


v.  Repairs Verification
-   Artisan can update status.
-   Uploading photographs of completed work.
-   Administrator final verification of completed maintenance requests.

 Out-of-Scope features

-   Use of Computer Vision to categorize maintenance issues

# 11. Assumptions and Open Questions
The founder assumes that:
i.  Students, hall administrators, and artisans have consistent internet
    access

ii. All targeted users have basic technical knowledge

iii. Administrators will use the system.
