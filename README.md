# FORENSIC-DATA-ANALYSIS
AN INVESTIGATIVE ANALYSIS OF THE MURDER OF AN ART COLLECTOR 'ROLAND GREENE' USING SQL ANALYTICAL SKILL

## INTRODUCTION

The investigation centers on solving the murder of Roland Greene through digital forensic analysis using SQL. By querying the following dataset available: access logs, call records, forensic events and suspect data, i looked into the events leading up to, during, and after the crime. The aim was to identify inconsistencies in alibis, determine suspect movements, and uncover potential motives.

## OBJECTIVES

- To identify the prime suspects based on digital evidence.
- To validate or invalidate alibi claims using access logs and call records.
- To critically look into the timeline around the time of death (~8:00 PM).
- To pinpoint key events, including who last saw the victim, gunshot timing, and emergency call placement.

## TOOLS

- SQL (Structured Query Language) – Used for querying relational data tables (suspects, access_logs, call_records, forensic events) and comprehensive data analysis.
- Relational Database Management System – SQL Server
- Time-based forensic correlation – Cross-referencing timestamps for pattern detection.

## TECHNIQUE AND SKILLS
- Data Joins & Filtering – Combining multiple tables (e.g., suspects with access logs) to build a timeline of activities.
- Time Range Queries – Narrowing down activities to critical windows (e.g., 7:59 PM–8:03 PM).
- Alibi Verification – Matching stated alibis against actual log-ins.
- Behavioral Pattern Analysis – Noting unusual or suspicious activity (e.g., access to vault room, call timing).
- Anomaly Detection – Identifying inconsistencies between records and alibi statements.

## DATASOURCE
<a href = https://github.com/Shanu998/FORENSIC-DATA-ANALYSIS/blob/main/access_logs_large.csv> Download the Microsoft Excel file </a>
## DATA MODEL: 
![Data Model](https://github.com/Shanu998/MYSELLAR-GLOBAL-STORE/blob/main/IMAGES/MYSELLAR%20DATA%20MODEL.png)


## INSIGHTS
![Overview Dashboard](https://github.com/Shanu998/MYSELLAR-GLOBAL-STORE/blob/main/IMAGES/MYSELLAR%20MAIN%20OVERVIEW.png)
- Robin Ahmed was the last person to see the victim alive at 7:57 PM.
- Gunshot occurred around 8:00 PM — activities around this time are crucial.
- Jamie Bennett was active in the building during the shooting, found in the vault hallway at 20:00:55.
- Alex Shaw made a call seconds after the shooting — suspicious timing.
- Susan Knight was recorded as the last person to call the victim before the murder.
- The vault room was accessed by Victor Shaw, Robin Ahmed, and Jamie Bennett around the murder timeframe.
- Security feed was cut at 20:03. It was assumed that security controls are likely to be located in the office; hence, Susan Knight could be a person of interest since her movements recorded on the access log show she accessed the office at 8:02 PM before the security feed was cut off.
- The emergency call at 8:05:45 was not linked to any suspect in the call logs — indicating potential foul play or tampering.
- Inconsistencies were found between alibi claims and actual movements from access logs.

## RECOMMENDATIONS
- Focus interrogations on the top suspects: Victor Shaw, Robin Ahmed, Jamie Bennett, and Susan Knight.
- Investigate Alex Shaw’s call timing — it may imply prior knowledge or involvement.
- Cross-check for missing call logs or tampering, especially for the emergency call.
- Review vault room access policies, as it appears central to the suspects’ movements.
- Recommend surveillance system audits to understand why the office security feed cut at 8:03 PM.




