# Exercises 1-4

Exercises 1-4 are introductory exercises that explore threat hunting by using KQL 
to search through logs, enabling MDTI and querying the ThreatIntelIndicators table, 
viewing MITRE ATT&CK coverage matrix, and creating automation rules to tag incidents
and escalate severity. 

## Exercise 1 -- Exploration: Hunting Across Your Data 
Get familiar with the data ingested into your Microsoft Sentinel workspace 
by running Advanced Hunting queries across multiple data sources. Then create 
your own custom detection rule based on a pattern you discover.

## Exercise 2 -- Threat Intelligence: Microsoft Defender Threat Intelligence 
Enable the Microsoft Defender Threat Intelligence (MDTI) data connector in Microsoft 
Sentinel to ingest threat intelligence indicators, then use the ThreatIntelIndicators 
table to match IOCs against your environment's telemetry.

## Exercise 3 -- MITRE ATT&CK Coverage
Use the MITRE ATT&CK page in Microsoft Sentinel to visualise which tactics and techniques 
your detection rules cover, identify gaps, and understand how the lab's attack chain maps 
to the framework.

## Exercise 4 -- Automation Rules 
Create a Microsoft Sentinel automation rule that automatically adds tags and adjusts severity 
when a specific alert fires with a specific entity. This exercise demonstrates how automation 
rules streamline SOC triage without requiring a full playbook (Logic App).
