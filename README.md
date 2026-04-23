# Manual Testing Artifacts – OrangeHRM

## Overview
Manual test cases and bug reports created for the OrangeHRM web application as part of QA testing practice.

## Application Tested
OrangeHRM– Open-source HR management system  
Type: Web application  
Testing Type:Manual & Exploratory Testing

## Test Coverage
|               Module                      |            No. of Test Cases           |
|               Login                       |                 9                      |
|       PIM – Employee Management           |                 6                      |
|             Recruitment                   |                10                      |
| Admin – User Management & Access Control  |                 5                      |
|              Attendance                   |                 8                      |
|          Logout & Session Security        |                 3                      |
|   Dashboard, Performance, Buzz, Directory |                 9                      |
|                Total                      |                50                      |

## Bugs Found (High Severity)
-  Session not terminated after logout — back button exposes dashboard (Security Bug)
-  Normal ESS user can edit attendance records without permission (Access Control Bug)
-  System allows same Punch In and Punch Out time — 0 working hours recorded (Functional Bug)
-  Duplicate Employee ID accepted in some flows (Data Integrity Bug)

## Tools Used
- Test Management:Google Sheets
- Application: OrangeHRM (demo instance)
- Bug Reporting fields:Severity, Impact, Suggested Fix

## Files
| File                        | Description                                                                         |
| `orangehrm-test-cases.xlsx` | 50 test cases with steps, expected vs actual results, severity, and suggested fixes |
