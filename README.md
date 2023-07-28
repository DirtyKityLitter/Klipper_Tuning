# Klipper_Tuning Voron 2.4 SB Tool Head and Sprite for Dannocluase
My set of tuning parameters

This page serves as a place where I can go to find all of my tuning parameters, information, research, what worked, and more.


The things to know and check for tuning
   
   &#x1F535; Extruder Gear Ratio+
   
   &#x1F535; Extruder Microsteps
   
   &#x1F535; Full Steps Per Rotation

Regardless of what extruder and gear set you have the above information is crucial.

   _A sample printer.cfg looks like this for the extruder section_
  
[extruder]

step_pin: EBBCan: PD0

dir_pin: EBBCan: PD1

enable_pin: !EBBCan: PD2

&#x1F535; microsteps: 32

&#x1F535; rotation_distance: 22.6254

&#x1F535; gear_ratio: 50:10 

nozzle_diameter: 0.400

filament_diameter: 1.750

full_steps_per_rotation: 200

heater_pin: EBBCan: PB13

sensor_type: ATC Semitec 104NT-4-R025H42G

sensor_pin: EBBCan: PA3

control: pid

pid_Kp: 37.805

pid_Ki: 4.942

pid_Kd: 72.302

min_temp: 0

max_temp: 300

pressure_advance: 0.03005

[tmc2209 extruder]

uart_pin: EBBCan: PA15

run_current: 0.650

stealthchop_threshold: 999999_


