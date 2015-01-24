master
======

Master repository for ENGR3199 includes C and Python source code and supporting files


Steps to make the blink file run.

CD to the directory in which the blink code is locateed.

Run the command scons in the linux terminal

CD out of the Blink folder to to the site_scons folder

In the site_scons folder, run the command: python bootloadergui.py

A graphical interface will open. With the board plugged in, first push the large black button near the red button and then the red button, while holding the black button. This puts the board into programming mode

Click File, import hex. Navigate to the blink folder and select the blink.hex file. Write it to the board, and then press the reset button. The board should then run the code.