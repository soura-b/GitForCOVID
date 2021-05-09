# GitForCOVID
Using GitHub to organize COVID emergency response.


# The Question
Can we use GitHub to maintain patient records in a hospital? Here is a possible approach, and some illustrations.


# Motivation
With second wave of COVID burning through India, many organization are responding by setting by hospitals. I learnt about one such organization, Doctors for You (https://doctorsforyou.org/), which has - as on May 09 2021 - set up 16 COVID hospitals.

From a leader in this organization, I found out that these hospitals require the following:
1. Supply chain management - for drugs
2. Personnel management - for doctors, nurses and paramedics
3. Bed allocation - these hospitals are inpatient care facilities
4. Patient tracking - admission, treatment and discharge

This post seeks to address items 3 and 4.


# Approach
GitHub is likely the world's most used software development, and it's bug/ spec management feature (called `Isssues`) lends itself to tracking information in general. Issues are composed of comments, they can be tagged, assigned to users, added to milestones, and opened/ closed. These features are mapped to patient management and bed allocation functions in the next section.

Other features of the GitHub platform that are useful in this scenario are - organization-based data access control, role-based edit/ view access control, data isolation (using repositories), and the availabiilty of robust, well-design iOS and Android apps.

If you prefer, you can jump straight to examples by clicking here [INSERT URL TO SAMPLE ISSUE].


# Stucture
## Issue Content > Patient Records
1. Issue Title > Patient Name
2. Issue Comment 1 > Gender, DoB/ Age, Emergency contact Mobile # & Address
3. Issue Comment 2 > Date of Admission, Chief Complaint, Workup/ triage details
4. Issue Comment 3 > Medication plan
5. Later issue comment > notes from care providers 

## Assignment > Users (Care Providers)
1. Issues can be assigned to users (more on user management later). In this case, users = care providers. 
2. Issues can be assigned to multiple users at a time. GitHub allows up to 10 simultaneous assignees, which is sufficient to cover 3-shift operations with both medical and nursing staff.
3. Users can assign an issue to other users, and unassign themselves (if they have the requisite permission). 

## Tagging > Labels (Bed Number)
1. Issues can be tagged with labels. 
2. Labels = a composite of Ward & Bed number.
3. Labels can be color coded.

## Opening and Closing Issues
1. Once a patient is discharged from the hospital, or in the event of death, their records can hidden from view by closing the issue.
2. Issues can be reopened in case of re-admission.
3. Users can also comment on closed issues - in case they want to add details post-discharge.
4. Once an issue is closed, it should be unassigned and untagged.


## Example
[WORK IN PROGRESS]
1. Sample hospital with 10 beds
  1. 5 in a male ward (green), and 5 in a female ward (blue).
2. aa


