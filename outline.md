## Roster Generator

**Purpose:** The cafe manager handwrites a roster for its staff every single week and releases it on a Saturday. They send a message to each individual staff of their respective schedule for the following week. We'd like to automate this task so that the cafe manager does not have to make the roster every single week.

---

**Problems to consider:**
* staff availability/days requested off (certain times of day they are able to work)
* budgeting (cannot overstaff as this is out of budget)
* understaffing (need sufficient staff to run the cafe)
* availability conflicts (produce warning if staff availability cannot fully cover cafe hours)
* over-working (produce warning if any staff works more than 5 days in a row)
* special hours (for bank holidays, etc)
* special dependencies (ex. at least one manager always working)
* add feature to allow for last minute call-outs + suggessted solutions
* figure out the optimal way to create the schedule as there are several different possibilities

**What we want the UI to look like:**
* Enter program, welcome screen
* Program displays shop name with table containing workers 
* Can click each individual worker to view details on their availability
* Shop details can be edited (ex, hours)
* button at the bottom to view the current week's roster
* button to generate roster

**What we want the result to look like:**
* possibly email the workers their roster for the week