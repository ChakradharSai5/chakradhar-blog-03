---
{"dg-publish":true,"permalink":"/1 Knowledge Hub/2 Functional Notes/1 Career Notes/3 TSTPS Kaniha Technical Notes/A Protection Interlocks and Control Logic Systems/Main TG Protection/","noteIcon":""}
---

- The protection trip from vacuum is as you know , peculiarly done here
	- Normal vacuum maintains at 0.88ksc that is in DCS (-)655mmhg
	- Tripping from LP exhaust pressure at 0.25ksc equivalent to (-)550mmhg or -0.75ksc **if FCB is close(or technically NOT open)**
	- **if FCB is open**, that is while lightup, we got 85ksc, and other temp. parameters and we rolled the Turbine, yet haven't switched to "No load with Excitation" from "No load" or switched and yet to close FCB then, in that particular case we have margin of Vacuum going up to 0.35ksc, equivalent to -0.65ksc or (-)478mmhg before tripping the turbine
- Vacuum Tripping
	- Our normal Vaccum maintains around 660mmhg which corresponds to -0.88ksc
	- Our tripping of TG is at 0.25ksc i.e -0.75ksc, i.e 550mmhg, CONDITION Field breaker in not open (that is close) meaning, when unit is in with Field breaker closed and unit is in running  