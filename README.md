# camDAQ

LabVIEW 2015 is used to control a third party camera.

G-code has been tested successfully with Basler Ace acA1300-200um.

Code performs an entropy measurement of every other acquired image and finds difference. Trigger condition is met when entropy difference is larger than user-defined threshold. The trigger frame and the previous four are saved.

LabVIEW Driver:
http://www.ni.com/download/ni-vision-acquisition-software-17.5/7270/en/
