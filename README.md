# CS207 - Audio Visualizer Shelf 
Interactive Gadgets Final Project 

# Contents 

- /src- 
- /hardware- 
- /build- 
- /libraries- 
- /examples- 
- /img-
- /LICENSE- 
- /README.md- 
# Requirements and Materials

Dependancies:

Bill of Materials:

- Shelf or 
- Arduino Uno Microcontroller Board 
- Adafruit Bicolor LED Square Pixel Matrix with I2C Backpack, Adafruit Industries #902 
- Electret microphone with amplifier, Adafruit #1063
- LEDs, red (64) and blue (64) (128 in total)
- Acrylic sheet, translucent or frosted, 16"×16" 
- Hardboard or strong cardboard 
- USB cable
- Hookup wire: black, red, and green
- Jumper wire, male-male
- Breadboard

# Build Instructions 

Start with a shelf that matches the dimensions of 16"1/8" x 16"1/8" and 4" deep. The inside of the shelf needs to be 16"X16" in order to fit the grid and matrix inside the shelf. Draw a grid on the hardboard to create an 8x8 grid with 2" squares across the board (64 boxes in total). Mark two dots on each square, one in the upper left corner and one in the lower right corner of each square. A template can be used to make the marking easier. Poke a hole all the way through the board on each mark and push the top of the LEDs through the board alternating red and blue for each line of lights (line of red, line of blue, etc). Cut up Cut 14 strips of hardboard into strips 15" 1/2" inches long and 1" 1/8" wide. Cut a slot every 2" to half the depth of the strips. Connect the strips at the end to make the matrix and seperate the boxes of lights. 

Wiring:
Cut 56 red, 56 black, and 56 green wires all to a length of 3". Strip the ends of the wires long enough to solder them together later. Twist the wires into chains of 7 wires in order to make them easier to solder. Solder each chain of wires together so they dont fall apart after moving them. This should result in 8 strands of each colour. Place the board on upsidedown so the legs of the LEDs are up. Bend the legs down so the cathodes are crossing each other but the anodes are seperate. From here, sodder the strings of black wires to the cathodes. Sodder the strings of red wires to the red LEDs and the green wires to the blue LEDs. Attach a black jumper wire to one end of each strand of ground wires so they hang off the end. Either solder these new wires to the strands or use electrical tape to attach them. Do the same to the green strands and red strands so they each have a jumper wire hanging off one side. Use the LED backpack to connect the extension jumper wires to the arduino. Each strand corresponds to each pin on the backpack. We suggest soldering the wires to the backpack to make the connection stable. Use the circuit diagram from Adafruit to connect the arduino to the backpack and microphone, but use different GND pins instead of the same one in order for the electronics to not interfere with eachother. 

Putting it together:
Glue the frosted glass or plastic cover to the front of the shelf and let it dry so it stays in place. Once it is secure, glue the matrix to the board on the same side that the LEDs show through. Once this is dry, insert the board witht he matrix into the shelf with the LEDs facing the frosted glass. Make sure all the wires, the arduino Uno, backpack, and amplifier fit in the shelf back. (Optional) attach the microphone to the underside of the shelf using small screws and poistioning it so the wires can hang out the back without being moved. We also suggest soldering the wires to the microphone carefully as to not cross sodder the pins and confuse the signal. 

Usage:
Upload the code and run the examples to test that all the lights work. Once the proper code has been loaded, the USB can be connected from the arduino to a wall socket through a USB cube or to a computer UBS port as a source of power. 
Play music to get the lights to dance across the board. The volume of the music will determine how many lights come on and how high they move up the board. The volume can also be adjusted on the microphone but a louder volume usually gives the best results. 

# Team 
The build team consists of:

- Emma Chuckry 
- James Hsieh
- Megan Pippus 

# Credits 
Turner, Charlie. “Transform an Ikea Side Table into a Music Visualizer | Make:” Make: DIY Projects and Ideas for Makers, Make: Projects, 3 May 2016, makezine.com/projects/ikea-music-table/?fbclid=IwAR3BYK5gKp24WP4_bTvdE4RgmYGt7BvV0hkUC2mkjERyQzj7BlW4QBgHPQo.
