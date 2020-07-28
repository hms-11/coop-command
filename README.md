# coop-command
Open Source Chicken Coop Automation
This project seeks to help hobby farmers reduce their workload and increase the laying efficiency of their hens. The CoopCommand project aims to accomplish these goals:
1) Automated coop door based on daylight.
2) Heated water for winter conditions with monitoring and control loop
3) Ventilation fan for summer conditions with heat/humidity monitoring and control loop
4) "LayLight" to ensure hens receive ~14 hours of lighted conditions to maintain laying year-round. 
5) Display monitor w/control to monitor current coop status

For ease of installation, CoopCommand will be optimized to run off of 12v DC power, capable of being supplied by a multitude of sources (lead acid, Li-Ion, wallwart, etc) with the board creating its own onboard 5v supply for sensors, IC's, etc. 
CoopCommand also aims to have all required components integrated into the main board, to reduce technical knowledge needed for installation. Pull-up resistors, hardware debouncing and a stable, filtered power supply (assuming 12v DC input) is all integrated into the main board. The main board is also capable of running without the OLED display board if desired. 
