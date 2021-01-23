## I_AM_BROOT
<img src="https://img.shields.io/github/license/ggroce/I_AM_BROOT">
I_AM_BROOT is a standalone cellphone brute force pincode cracking device, created during simpler times when phone security was nigh non existent.
<br>
<br>
When I built this in 2015, there was a need for a cellphone pincode cracking machine, capable of automatically entering sequences of pincodes in order to gain access to the data of a cellphone or tablet incident to search warrants legally issued.  During this time, Android and cellphone manufacturers had yet to implement any serious safeguards against brute force pincode guessing attempts.  
<br>
<br>
<p float="left">
<img src="https://user-images.githubusercontent.com/25714007/86405870-ba3e5a00-bc77-11ea-815a-27aed227bfa9.png"> <img src="https://user-images.githubusercontent.com/25714007/86405878-be6a7780-bc77-11ea-8789-e0bdf58d38e8.png">
</p>
<br>
### Details
I_AM_BROOT is a standalone device that uses USB-OTG to interface with devices and act as a keyboard.  For phones that didn't support USB-OTG, it features separate leads that through using copper tape, could short out certain capacitive touch screens at specific points, thus simulating a user touching the screen.  The code for I_AM_BROOT contains an ordered array that is sorted by the pincodes of most common use to expedite an average pincode crack, while also featuring the ability to sequentially run through a list of numbers from any chosen start point.  Using a Teensy 3.1 microcontroller, the device was designed, fabricated, and programmed from the ground up.  
<br>
<br>
Using a custom made CNC machine and laser cutter, a break out board was fabricated to hold the Teensy, interface with power, and connect to internal mechanical replays used for controlling the simulated capacitive screen touch events.  The device is controlled by touching the touch sensitive machined hexagonal pieces of aluminum.  The BOB was designed using Eagle Cad, (design files included in repo), and casing was created using Vectric Aspire.  The code was completed in C and is uploaded to the Teensy in the same manner as an Arduino.  
<br>
<br>
<p float="left">
<img src="https://user-images.githubusercontent.com/25714007/86405946-de9a3680-bc77-11ea-80af-e5153eb10b45.png"> <img src="https://user-images.githubusercontent.com/25714007/86405949-e1952700-bc77-11ea-9c6d-203cf8d4a24f.png"> <img src="https://user-images.githubusercontent.com/25714007/86405957-e4901780-bc77-11ea-907d-d902885dac58.png">
</p>
