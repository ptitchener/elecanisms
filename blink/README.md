Elecanisms 2016
Jacob Kingery and Paul Titchener

These instructions detail how to run the blink program on an elecanisms pic xc16 board. 

1) Install the development environment. Referenece: http://elecanisms.olin.edu/handouts/20160121_BuildTools.pdf

2) Clone the git repository from https://github.com/ptitchener/elecanisms

3) Navigate to the elecanisms/blink folder. Compile the code using the command `scons`

4) Hold down switch SW1 while plugging in the board to put it into programming mode. The board can also be put into programming mode by holding down SW1 while pressing the RST button.

5) Navigate to the elecanisms/site_scons folder. Run the bootloader gui with the command `python bootloadergui.py`.

6) The board should connect automatically. If it does not, try pushing the connect button. If it still does not, retry putting the board into programming mode. 

7) Import the elecanisms/blink/blink.hex to the bootloader using the import command (alt-i) 

8) Upload the code to the board using the write command. Click the disconnect and run button to run the code. 

9) The red and green LEDs should alternate blinking on a 1 second period. Pushing SW3 will turn on the blue LED. 
