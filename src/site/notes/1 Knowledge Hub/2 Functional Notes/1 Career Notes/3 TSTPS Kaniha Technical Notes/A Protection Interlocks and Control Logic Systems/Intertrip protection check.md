---
{"dg-publish":true,"permalink":"/1 Knowledge Hub/2 Functional Notes/1 Career Notes/3 TSTPS Kaniha Technical Notes/A Protection Interlocks and Control Logic Systems/Intertrip protection check/","noteIcon":""}
---

- Boiler trip --> Turbine trips
- Turbine trips & Low forward power  ----> Generator trips
	-  so while checking intertrip protection check, C&I has to simulate the low forward power bit so Generator tripping relay acts
- Generator trips & unit in sync condition ----> Turbine trips
	- this sync has to be simulated by C&I to make turbine RTS to act