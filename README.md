# DIY Sim Wheel
## Purpose
The purpose of this project is to make a powerful sim racing wheel cheaply (also i like doing this kind of stuff). But accualy the main reason i started this project was that i didn't want to buy a logitech g29 (g29 because it is the most common, known, reliable and cheap model on the market). Because the g29 was made of too much plastic, the torque was not at the level i wanted and the size of the steering wheel was not enough for me. That's why i focused on these issues in my own design. Below you can find all the details of the steering wheel.
## Motor
To be honest, when i started the project, i didn't want to make a design like the one below. I had in mind to make a direct drive sim wheel by purchasing a stepper motor with an encoder and a stepper motor driver. However, since the prices of these parts were higher ($110 for stepper motor and $110 for driver) and i couldn't see an example of a sim wheel made using with stepper motor, i decided to make this project with the motor below. My advice to you is that if you don't have a budget problem and still want to make your own sim wheel, you should continue with a servo motor. If I had used such a motor, i wouldn't have bothered with the gears, shaft or frame in this project.  
As an motor, i chose this motor which is originally used in scooters.  
![Motor](Images/Motor.png)  
Brushed DC motor. Model: MY1025  
Works with 24V and 14A (so its 250W). Also 2750RPM (actually, what i paid attention to was not the rpm but the torque).  
I think this motor will be powerful enough for the steering wheel. If you want, you can do the project by using 2 smaller motor or even using 2 of this motor. Although i didn't need such a thing.
## Power Supply
When choosing a power supply, i preferred a 24V and 15A power supply. Since the motor is 250 watt, the watt of the power supply should be slightly higher (in this case 300W).  
![Power Supply](Images/Power Supply.png)  
## Gears

## Frame

## Electronics

## Design
I made the entire design using solidworks. You can find these files in the solidworks files section.  
The thing i paid particular attention to in the design was that the shaft passes through the middle of the case. If I hadn't paid attention to this, the width of the cage could have been smaller.
## Assembly

## Pedal Shifters
The reason i opened a separate title for the pedal shifter was that i decided to add it to the steering wheel after the whole project was finished. So you don't have to do this part if you don't want to.  
## Wiring Diagram

## Software
Actually the first software i ran was the wheelconfig program but i couldn't get the system to work using this program. Also this program has a more complex schematic. That's why i preferred EMC software.  
The only thing i didn't do myself in this project and copied directly was the software. That's why i won't show how to set up the program, transfer it to arduino and make settings here. You can use the videos i put below to do these.  
![EMC](Images/EMC.png)  
After installing the software, everything that needs to be done about the steering wheel is finished.  
## Cost
In this section, i will write the prices of the pieces in turkish lira. Since my purpose in doing my projects is completely up to my enjoyment, they are spread over a long period of time like 1-2 years. That's why prices and exchange rates are variable, but as of the date i did the project, you can think of 1 dollar as 30-40 turkish lira.  
Motor: 1700 tl  
Power supply: 600 tl  
Steering wheel: 1500 tl  
## Sources
Below are the videos that i watched to gain information when starting this project. I recommend that you watch them too.  
https://youtu.be/hbCjbCfUp0g?si=NynA37pT9rn3MCQu (special thanks to this video)  
https://youtu.be/FUZKslSwfaw?si=WwYVih52zpUwfXec  
https://youtu.be/L-FAyA0VQVQ?si=nJCx8VnmU1xidO3N  
https://youtu.be/nPorcXRC3Ns?si=enejoyd5WoKqs4ha  
https://youtu.be/aYYAbcPKN8g?si=kRVGH3cPVwXVqP0q  
https://youtu.be/gG_dbnKfH5Q?si=5sSKj9XNKsQQZj4X (example using stepper motor)  
https://youtu.be/_h417VxFmWQ?si=Obe5oXemXU2WvnzE (example using servo motor)  
## Conclusion
