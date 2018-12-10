# Canvas Admin Style Guide

For information regarding how to do anything from an Admin perscpective on Canvas, please see the [Canvas Admin Guides](https://community.canvaslms.com/docs/DOC-10895-canvas-admin-guide-table-of-contents).

## Users

Students are added with the following format:

* email in the form _firstname.lastname@oxley.nsw.edu.au_
* login in the form of their student number with prepended 0's to make the length 6 characters, eg _001234_
* SIS ID as their student number, eg. _1234_

Teachers use the following format:

* email in the form _firstname.lastname@oxley.nsw.edu.au_
* login **and** SIS ID are both their school username, which is usually _lastname_ but sometimes _lastnamef_

## Accounts and Sub-Accounts

### Teachers as Sub-Account Admins

The key sub accounts are the academic areas (Curriculum Teams). If a staff member is a member of a Curriculum Team they also need to be added as an *Admin* to that Sub-Account, with the role *Department Member*. Curriculum Leaders should be added as and *Admin* to that Sub-Account with the role *Admin*. 

Some teachers are also Admins for the global account (Oxley College) with the _Stalker_ role. This means that they can view everything in the school but not edit - handy for heads of house and learning support.  

### Sub-Account Names for SIS import

When performing a SIS import the following are the SIS ID's for the relevant Sub-Accounts:

| Curriculum Area | Sub-Account ID |
|-----------------|----------------|
| English | SubAcc_English |
| Mathematics | SubAcc_Mathematics |
| Science | SubAcc_Science |
| Humanities | SubAcc_Humanities |
| Arts | SubAcc_Arts |
| Super Team | SubAcc_SuperTeam |
| Cornerstone | SubAcc_Cornerstone |


## Terms

The following terms are created each academic cycle (obviously the year changes each year):

| Term name | Term ID | For | Runs |
| -------- | --------- | ------------ | ---------- |
| 2019 K-10 | 2019 | K-10 courses | Jan to Dec | 
| 2019 Year 12 | 2019Y12 |  Year 12 courses finishing in 2019 | Oct 2018 to December 2019 |
| 2019 Year 11 | 2019Y11 | Year 11 courses | Jan to Oct - can also run through Y12 | 
| 2019 Semester 1 | 2019S1 | Semester 1 courses | Jan to Jun |
| 2019 Semester 2 | 2019S2 | Semester 2 courses | Jul to Dec |

Any non-academic courses will fit into the _2019 K-10_ term, or either of the Semester terms, depending on what works best. Individual courses can have their run dates changed in their internal settings and this will overide any global setting.

## Courses

The course codes from Edval / Edumate must be adjusted before performing a SIS upload. Course codes should be prepended with the year / term ID. For example _12MAT.O_ should become *2019_12MAT.O*. If this is not done the SIS ID for the course will conflict with previous years and you will get a whole bunch of errors with enrolments that are hard to understand. 

## Sections

Some Canvas courses will comprise of several classes. The ID for the Section will be the full Edval code with prepended year (e.g. *2019_9MAT.O*) and the course will omit the *.O* (e.g. *2019_9MAT*). Some senior courses will run this model (ask CL's for their preference), and the current **7 - 10** that use this are:

* Geography
* History
* PDHPE
* Mathematics
* Global Studies

## Enrolments

Enrolments can be managed by teachers, and if added manually by teachers in each individual course they then have the ability to remove students as well. If students are enrolled through the SIS Import then teachers can add students but only Admins (CL's and Canvas admins) can remove students. Note that whatever changes you make to the course codes when you create the courses you will need to replicate here before importing students. 

## Audits

Performing an audit of courses once a term is a great idea, if possible. These easiest way is to open a year groups worth of courses in seperate tabs and check the following:

* Published and home page correct and the Navigation Menu correct, then go to
* Assignements and check for Assessment Notifications in the right place and format
