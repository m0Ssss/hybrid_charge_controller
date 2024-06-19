# hybrid_charge_controller development board version 1 and (energy meadow) version 2 *Work In Progress* 
Low voltage solar/wind/ other generator hybrid charge controller -  power conditioning circuit development board, and version 2 with built in charger. 
<br>MPPT (Maximum Power point tracking) using ST's SPV1040 IC
<br> 0v charging function to regenerate over-discharged batteries that can no longer be charged with conventional chargers. 
<br>0.3v - 30 volt in AC or DC 
<br>5v Out
<br>Temperature sensor for over and under temperature protection
<br> over voltage, over current, over discharge protection
<br> Constant Current and Constant voltage charging
<br>still a lot of issues need to e resolved. e.g. wrong placement of load in relation to charge protection IC (BQ2980), footprint wrong for SPV1040... etc. Issues in Bill of Materials. 
<br>Designed as part of the Windternet Project with Regenerative Energy Communities + Solar Internet, where we are wanting to run a raspberry pi 0 server on the experimental farm "VXO Farmlab" in Sweden. 
<br> <br> space for both 18650 batteries or LIPO with JST connector;
<br> The plan is to regenerate over-discharged batteries with renewable energy. We find a lot of 18650s in the e-waste bins.
<br> We made a large input voltage range to allow for many different types of generators; specifically we wanted to design for e-waste motors and other discarded materials (e.g. magnets from harddrives and copper wire from old relays) to be reconditioned into wind generators. 

<br> A massive thanks to Urs Gaudenz GaudiLabs for the support, assistance and motivation in designing these 2 (my first 2) PCBs. 

