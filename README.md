# BerryBot
Compact klipper-powered plotter using a 5-bar SCARA mechanism

Berry Bot is a project born out of a desire to not leave artists out on an in person collaborative art event.

I wanted to design a portable machine that would allow all of the artists participating in the event to be able to sign remotely, regardless of location.

After researching a few different types of kinematics I decided on a 5-bar SCARA linkage to allow the final build to be extremely compact, as it would need to fit in a backpack.

I decided to implement this with a custom klipper kinematics module, as klipper has a very solid motion framework to easily build off of.

The project is comprised of an RP2040 mcu with two tmc2209 stepper drivers, an Orange Pi Zero2, a USB C PD module set to 20V, a buck converter stepped down to 5V for servo and LED power, and a mg996r servo for actuating the pen.

While this project can certainly be recreated at home, this was made under a budget constraint of almost nothing, so part selections are suboptimal due to me simply working with spare parts from other projects outside of thrust bearings, the buck converter, and the servo.

Please contact me at [brueter918@gmail.com](mailto:brueter918@gmail.com) with any questions or employment opportunities
