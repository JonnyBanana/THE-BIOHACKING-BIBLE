                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


https://www.thingiverse.com/thing:866904
Simple Syringe Pump by doctek is licensed under the Creative Commons - Attribution - Share Alike license.
http://creativecommons.org/licenses/by-sa/3.0/

# Summary

There are many syringe pump designs available - just search Thingiverse! While most of these designs are very capable and can be built for various syringe sizes, they often require many vitamins (non-plastic parts), like guide rods and bearings. My goal was to create a syringe pump for a 10ml syringe that needs a minimum of vitamins. Here is the result. The Instructions explain how to assemble the pump and other important details. The FreeCAD design files will be available  on GitHub.  

Use this with my Simple Servo Valve (coming soon) to build a pump that can continuously deliver a fluid from a source to a destination.
Update 3/3/18: Simple Servo Valve is here: https://www.thingiverse.com/thing:867862
Per a request, I'm adding the FreeCAD files. FreeCAD can be used to convert the files to STEP format and perhaps others. I have no independent way to test the resulting files, so I leave that conversion to others.

# Instructions

Print one of each part except for the rails: print two of these.   
I print the carriage with support. The nut hole is hard to clean out, but leaves a nearly perfect opening to shove the M8 nut into.  
In addition to the printed parts, you'll need:  
1 M8 nut (for the carriage)  
120mm of M8 threaded rod  
4 10mm x M3 screws (for the motor)  
8 20mm x M3 screws (for the frame)  
4 12mm x M3 screws (for the clamps)  
1 10ml syringe  
1 NEMA 17 stepper motor  
Shaft coupling of some sort. The coupling design I use is discussed here: https://hackaday.io/project/3794/logs. If you use it, you'll need some brass tubing, 3 10mm x M3 screws, 3 M3 nuts, and 1 6mm x M3 set screw.  

I use an M3 tap to thread  the holes in the rails, the carriage, and the clamp holes in the syringe holder.  

The pictures show how to assemble the unit.  

I use Teensy 2 (Arduino clone), a 5V source (for the servo), and a stepper driver to run the pump.