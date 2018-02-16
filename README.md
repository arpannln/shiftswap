# shiftswap

## Flex Project-Proposal

### About
Shift swap is designed to fill a need in the ever changing retail and service industries. Those who work in these spheres are plagued with schedules that change from week to week, and often find that their their assigned schedule conflicts with prior commitments and obligations. Shift Swap solves this issue by allowing employees to trade shifts with one another. It allows users to request to trade shifts, drop shifts, and pick up shifts. It handles the handoff between request and response between two employees as well as updating the store schedule.

There are multiple layers of functionality which will build on one another depending on time available to work. These will occur in phases as outlined below.


#### Phase 1
* Users can be created and/or login
* Workplace can be created/added by users
* Users can create and add their schedule to a store
* Users can view schedule at their store for all employees

#### Phase 2
* Users can request shift trade and receive trade requests (email/text)
* Shifts can be swapped
* Users can login with Facebook or Google

#### Phase 3
* Users can modify their schedule
* Users can add schedule of other users
* Stores are validated via Google maps
* Personal calendars are updated by application

#### Phase 4
* Users can authenticate one another (after several have designated a store)
* Schedule can be added via picture/ocr
* Calendar can be sorted by people working

#### Phase 5
* Multiple shift types can exist (busser, server, manager) and shift swaps depend on position
* Users can work at multiple locations

### Technologies & Technical Challenges
Backend: Node.js
Frontend: REact/JavaScript


## Accomplished over the Weekend
* Complete a Node.js tutorial
* Create database according to scheme
* Implement user athentication


## Group Members & Work Breakdown
#### Kyle Brackebusch, Dylan McCapes, Arpan NLN

#### Day 1
* Do Work
#### Day 2
* Do Work
#### Day 3
* Do Work
#### Day 4
* Do Work
#### Day 5
* Do Work


## Datbase Scheme

### Users
| Column Name  | Data Type |
| ------------- | ------------- |
| id  | integer  |
| name  | string  |
| email | string |
| phone_number | integer |
| password_digest | string |
| session_token | string |

### Workplaces
| Column Name  | Data Type | 
| ------------- | ------------- | 
| id  | integer  |
| name  | string  |
| address | string |

### Shifts
| Column Name  | Data Type | 
| ------------- | ------------- | 
| id  | integer  |
| user_id  | integer  |
| workplace_id | integer |
| date | date 	(ISO 8601)| 
| start_time | time (ISO 8601)|
| end_time | time (ISO 8601)|
