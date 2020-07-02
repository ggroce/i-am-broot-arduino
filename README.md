## I_AM_BROOT
A legacy cellphone brute force pincode cracking machine.\
<br>
When built in 2015, there was a need for a cellphone pincode cracking machine, capable of automatically entering sequences of pincodes in order to gain access to the data of a cellphone or tablet.  During this time, Android and cellphone manufacturers had yet to implement any serious safeguards against brute force pincode guessing attempts.  
<br>
![image](https://user-images.githubusercontent.com/25714007/86405870-ba3e5a00-bc77-11ea-815a-27aed227bfa9.png) ![image](https://user-images.githubusercontent.com/25714007/86405878-be6a7780-bc77-11ea-8789-e0bdf58d38e8.png)
<br>
<br>
I_AM_BROOT used a USB-OTG to interface with devices, acting as a keyboard.  For phones that didn't support USB-OTG, it featured separate leads that through using copper tape, could short out certain capacitive touch screens at specific points, thus simulating a user touching the screen.  The code for I_AM_BROOT contains an ordered array that is sorted by the pincodes of most common use, while also featuring the ability to sequentially run through a list of numbers from any chosen start point.  Using a Teensy 3.1 microcontroller, the device was designed, fabricated, and programmed from the ground up.  Using a custom made CNC machine and laser cutter, a break out board was fabricated to hold the Teensy, and casing was created, using the CAD files found within this repo.  
<br>
![image](https://user-images.githubusercontent.com/25714007/86402310-3bdeb980-bc71-11ea-8d42-c0a0054d0baa.png)
![image](https://user-images.githubusercontent.com/25714007/86402341-47ca7b80-bc71-11ea-9b80-5b64eac50f90.png)
![image](https://user-images.githubusercontent.com/25714007/86402372-531da700-bc71-11ea-8a2b-3ee626c9af66.png)
![image](https://user-images.githubusercontent.com/25714007/86402499-86f8cc80-bc71-11ea-84e9-50796feae50b.png)
