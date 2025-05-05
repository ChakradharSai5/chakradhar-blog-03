---
{"dg-publish":true,"permalink":"/1-knowledge-hub/2-functional-notes/1-career-notes/3-tstps-kaniha-technical-notes/a-protection-interlocks-and-control-logic-systems/intertrip-protection-check/","noteIcon":""}
---

- Boiler trip --> Turbine trips
- Turbine trips & Low forward power  ----> Generator trips
	-  so while checking intertrip protection check, C&I has to simulate the low forward power bit so Generator tripping relay acts
- Generator trips & unit in sync condition ----> Turbine trips
	- this sync has to be simulated by C&I to make turbine RTS to act