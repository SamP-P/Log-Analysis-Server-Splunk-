----

Description:
  An Ubuntu server that can recieve system logs from a Windos pc (on LAN), through splunk universal forewarder, this information should then be analysed and filtered
  Alerts and an analysis of the data should be recieved in the event of a suspicious change.

----

List of filters:
  - Data outside work hours (09:00 - 17:00)
  - Brute force attack
  - All privalage escalations / account changes or additions
  - Unknow programs or programs running from suspicious locations
  - sys changes
  - Large data transfers to unknow IPs
  - Port scanning detection

----

Goals:
  - Basic SOC for an individual PC
  - Real time alerts and descriptions for all filterd data

----

Skills:
  - Log collection
  - Event monitoring
  - Linux + Windows Handling
  - setting static IPs

----
![Network Diagram](Network-Diagram.png) 
![Log-Flow-Diagram](Log-Flow-Diagram.png)
