# OpenERV-version-5_4
This is version 5.4 of the OpenERV, I expect only minor tweaks from this point on.

There are three versions in this folder now.


### Notes from Version 5.4.2:
There is a google doc linked to from the website that discusses print settings, and I will make another one that discusses assembly of the electronics and the mechanical system later.
The firmware and electronics are the same except there is no more stepper motor, so you can omit the stepper driver.  This means it's literally just the voltage regulator to power the pico, two resistors for the thermistors, and the pwm pins from the fans connect straight to the pico, and the thermistors connect to the right place, there is a separate driver board for the brushless motor, and that's it.  The driver board I'm using right now is this one off amazon, but I plan to switch to a blheli_s ESC asap, just gotta wait till it arrives from china as no one is selling them at a reasonable price on this continent.  A simonk esc doesn't work, I tried it.  A blheli one does work but makes significant noise. blheli_S should be good, blheli_32 would also be good but is more expensive.  They contain integral PID controllers. https://www.amazon.ca/DollaTek-5V-12V-Brushless-Driver-Controller/dp/B082QN3V9Q/ref=sr_1_6?crid=K8K99JYJ8HGO&keywords=brushless+motor+driver+board&qid=1656124539&sprefix=brushless+motor+driver+board%2Caps%2C91&sr=8-6
<- that one is kind of expensive and doesn't give good torque at low speed, but it's ok for now.

~Update:
ok I tried to upload the CAD files, and github won't let me upload anything larger than 25Mb, as if files are always smaller than that, right? What a joke. Come on guys, this is basic stuff.  I can't do my part if you don't do yours.  All I can do is link to the file, then, sorry: https://drive.google.com/file/d/1uDcw0WnnuMwMFIV25TjYN85AUw8yoe1H/view?usp=sharing~

Update the files for this version and several others 
