# CS207 - Audio Visualizer Shelf 
Interactive Gadgets Final Project 

The following instructions, code, and libraries will allow you to build a Audio Visualizer shelf at home with the help of an Arduino Uno. 

# Contents 
- /build
- /libraries 
- /examples
- /img

 # Requirements and Materials

- Shelf or sturdy container 16 1/8" x 16 1/8" 
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

- Wiring:
Cut 56 red, 56 black, and 56 green wires all to a length of 3". Strip the ends of the wires long enough to solder them together later. Twist the wires into chains of 7 wires in order to make them easier to solder. Solder each chain of wires together so they dont fall apart after moving them. This should result in 8 strands of each colour. Place the board on upsidedown so the legs of the LEDs are up. Bend the legs down so the cathodes are crossing each other but the anodes are seperate. From here, sodder the strings of black wires to the cathodes. Sodder the strings of red wires to the red LEDs and the green wires to the blue LEDs. Attach a black jumper wire to one end of each strand of ground wires so they hang off the end. Either solder these new wires to the strands or use electrical tape to attach them. Do the same to the green strands and red strands so they each have a jumper wire hanging off one side. Use the LED backpack to connect the extension jumper wires to the arduino. Each strand corresponds to each pin on the backpack. We suggest soldering the wires to the backpack to make the connection stable. Use the circuit diagram from Adafruit to connect the arduino to the backpack and microphone, but use different GND pins instead of the same one in order for the electronics to not interfere with eachother. 

- Putting it together:
Glue the frosted glass or plastic cover to the front of the shelf and let it dry so it stays in place. Once it is secure, glue the matrix to the board on the same side that the LEDs show through. Once this is dry, insert the board witht he matrix into the shelf with the LEDs facing the frosted glass. Make sure all the wires, the arduino Uno, backpack, and amplifier fit in the shelf back. (Optional) attach the microphone to the underside of the shelf using small screws and poistioning it so the wires can hang out the back without being moved. We also suggest soldering the wires to the microphone carefully as to not cross sodder the pins and confuse the signal. 

- Main Code: https://github.com/DysfunctionalTech/CS207/tree/master/Adafruit-GFX-Library-master 

# Usage:
Upload the code and run the examples to test that all the lights work. Once the proper code has been loaded, the USB can be connected from the arduino to a wall socket through a USB cube or to a computer UBS port as a source of power. 
Play music to get the lights to dance across the board. The volume of the music will determine how many lights come on and how high they move up the board. The volume can also be adjusted on the microphone but a louder volume usually gives the best results. 

- Library: https://github.com/DysfunctionalTech/CS207/tree/master/ffft
- Examples: 
   - https://github.com/DysfunctionalTech/CS207/tree/master/piccolo-master
   - https://github.com/DysfunctionalTech/CS207/tree/master/Adafruit_LED_Backpack-master

# Images 
![47575330_274210546572714_8746238064038248448_n](https://user-images.githubusercontent.com/43588286/49908026-60c8cd00-fe3e-11e8-8144-043184e128b5.jpg)
![47577935_2216511738393849_76291323690221568_n](https://user-images.githubusercontent.com/43588286/49908027-60c8cd00-fe3e-11e8-8219-6126c8ecac9d.jpg)
![47683393_351566135622501_573847410732695552_n](https://user-images.githubusercontent.com/43588286/49908028-60c8cd00-fe3e-11e8-804e-09b838e4479f.jpg)
![47683918_264797280873539_5015101473223081984_n](https://user-images.githubusercontent.com/43588286/49908029-61616380-fe3e-11e8-9c0b-555b6c8d98a3.jpg)
![47686729_308692586645386_4400117071887728640_n](https://user-images.githubusercontent.com/43588286/49908030-61616380-fe3e-11e8-9015-1bd4b1779ebc.jpg)
![47688509_751728308518610_4600780641196310528_n](https://user-images.githubusercontent.com/43588286/49908031-61616380-fe3e-11e8-8f88-96c7babae69a.jpg)
![48087613_209274626670030_7010143103956811776_n](https://user-images.githubusercontent.com/43588286/49908032-61616380-fe3e-11e8-9411-d4314aed51fb.jpg)
![48092381_208351440047400_4737722284700073984_n](https://user-images.githubusercontent.com/43588286/49908033-61616380-fe3e-11e8-96e0-0191ecc2547c.jpg)
![48181034_718229868576553_1407369261441089536_n](https://user-images.githubusercontent.com/43588286/49908034-61616380-fe3e-11e8-8d31-dede94efcd5e.jpg)
![48195674_2205045459525837_4075526365896507392_n](https://user-images.githubusercontent.com/43588286/49908036-61616380-fe3e-11e8-9238-e6584205f837.jpg)
![48216431_365511780922683_429112467465961472_n](https://user-images.githubusercontent.com/43588286/49908037-61f9fa00-fe3e-11e8-8b31-d656e46ad6af.jpg)
![48238121_2062273703793520_9117800460818841600_n](https://user-images.githubusercontent.com/43588286/49908038-61f9fa00-fe3e-11e8-8b0e-9e499bef37e7.jpg)
![48249876_123778718560196_4661121143543955456_n](https://user-images.githubusercontent.com/43588286/49908039-61f9fa00-fe3e-11e8-932d-7038601988bb.jpg)
![48274957_2764095033604230_2789987987859963904_n](https://user-images.githubusercontent.com/43588286/49908040-61f9fa00-fe3e-11e8-9e52-51b4df4278c6.jpg)
![48275223_1850472101728450_827954628199972864_n](https://user-images.githubusercontent.com/43588286/49908041-61f9fa00-fe3e-11e8-901f-f1894696cdbc.jpg)
![48275422_278707996323325_6074267767358357504_n](https://user-images.githubusercontent.com/43588286/49908042-61f9fa00-fe3e-11e8-9137-9512b8dc023a.jpg)
![48281532_2372926099401958_731123916201787392_n](https://user-images.githubusercontent.com/43588286/49908043-61f9fa00-fe3e-11e8-86c5-bc6d809c5f25.jpg)
![48343444_779962199012649_161970612665843712_n](https://user-images.githubusercontent.com/43588286/49908044-62929080-fe3e-11e8-9488-374d046ffe85.jpg)
![48360546_367994207288054_8698169481551151104_n](https://user-images.githubusercontent.com/43588286/49908045-62929080-fe3e-11e8-9d8e-3ea5f3bc514f.jpg)
![48361514_277369593124854_312516401870929920_n](https://user-images.githubusercontent.com/43588286/49908046-62929080-fe3e-11e8-9a83-8fa2bf95ed8e.jpg)
![48364102_206755610227555_5919964053567963136_n](https://user-images.githubusercontent.com/43588286/49908047-62929080-fe3e-11e8-9ef2-1d6650510580.jpg)
![48366370_338866696893347_6795801945006145536_n](https://user-images.githubusercontent.com/43588286/49908048-62929080-fe3e-11e8-8f91-7885188ce8e1.jpg)
![48367309_1622006138100944_5651576684021809152_n](https://user-images.githubusercontent.com/43588286/49908049-62929080-fe3e-11e8-9309-c8b571f5ab0e.jpg)
![48367876_2202260230093541_2863566429817405440_n](https://user-images.githubusercontent.com/43588286/49908050-62929080-fe3e-11e8-92c9-df707e76f18e.jpg)
![48390708_313691026151475_1957176060885860352_n](https://user-images.githubusercontent.com/43588286/49908051-62929080-fe3e-11e8-89ba-0852e95f86e4.jpg)


# Team 
The build team consists of:

- Emma Chuckry 
- James Hsieh
- Megan Pippus 

# Credits 
Turner, Charlie. “Transform an Ikea Side Table into a Music Visualizer | Make:” Make: DIY Projects and Ideas for Makers, Make: Projects, 3 May 2016, makezine.com/projects/ikea-music-table/?fbclid=IwAR3BYK5gKp24WP4_bTvdE4RgmYGt7BvV0hkUC2mkjERyQzj7BlW4QBgHPQo.
