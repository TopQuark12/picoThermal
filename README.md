picoThermal is a fork off of picoReflow by [apollo-ng]. It is intended to make it more 
versatile (suited for reflow oven or ceramic kiln) by adding several features:

* Ability to disable cooling, air, door sensor, etc.
* Handling of two separate heaters
* Automatic PID tuning
* Time and temperature units defined per profile
* Temperature PWM loop separated from control loop
* Option to wait for system to reach target temperature before going to next profile stage
* For ceramic kilns, dynamic calculation of end temperature based on heat rate  

This fork intends to add the following functions
* Support for MAX31865 RTD converter chip for PT100/PT1000 support  

This software is now in active use controlling my electric kiln and is working reliably. The added options make it suitable for a much wider range of thermal controllers than the original. 
