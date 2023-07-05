# Investigating-Security-Incident-Using-SQL-queries

In this project the analyst was tasked with investigating a recent security incident.


Tools used: LInux command line to run SQL queries in an organizational database.

First, retrieved login events made after a certain date:

 After 2022-05-09: 

![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/8a0a75a1-518e-4e1f-8c79-3ef9e4594e04)
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/04e9eeb8-a4ab-47ce-9f0f-92e9d60a9a93)


 On or before 2022-05-09: 

![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/8876983f-5881-42da-afe7-a497142df3d0)
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/77d08740-8687-483c-8e39-783861affe79)


Second, narrowed the focus of the search to filter logins in a date range:

![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/08076141-bae0-4e9c-8894-fc87a6249dda)
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/43b07d15-59a1-45ba-8723-e233b6fbb999)


Third, investigated logins that were made at certain times.

 Before 07:00:00 
 
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/ac376a6b-bb8d-4569-a2df-51d23bd491a3)

 Between 06:00:00 and 07:00:00:
 
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/8e21f869-5d3f-4d2b-9151-6b90591695fa)


Finally, filtered login attempts based on their event IDs.

 Event Id equal to or greater than 100:
 
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/d7d14f6b-3f1d-4f01-9603-9122231d7e95)
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/4c7faaa2-c689-4b6f-98b9-b2b155df813e)


 Event Id between 100 and 150:
 
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/d58d1ac2-c596-41bf-b0f6-17a54ccb9af5)
![image](https://github.com/MarcoSantibanez/Investigating-Security-Incident-Using-SQL-queries/assets/138132151/ae701b4f-9af0-4d12-94e9-98ee18395ead)





 



