# Green Lightpads

Schematics and instructions for creating the green lightpads used for satiety assays with optogenetics in Miner et. al, 2024.

See below for how vials are positioned on the lightpad to achieve a ~ $8.12 µW/mm^2$ intensity.

Schematics and laser cutter settings can be found in GreenLightpad.pdf or GreenLightpad.ai

## Parts

Black acrylic for bottom and sides:  1/8" black acrylic McMaster-Carr #8505K755

Clear acrylic for top: 1/6" clear acyrlic McMaster-Carr #8589K12

LEDs (come with screws): 2ct of FXC 6 LED Clearance Truck Bus Trailer Side Marker Indicators 12V, Green https://www.amazon.com/Clearence-Trailer-Marker-Indicators-Taillight/dp/B01F8OFNL8?th=1

Diffuser paper: Diffusion Gels Filter Sheet Kit, #No.3 Light Frost, 54% transparency https://www.amazon.com/Diffusion-15-7x19-6inches-40x50cm-Photography-Diffuser/dp/B08PFXCSZL

22 AWG Wire: just a couple inches, we use DigiKey 2328-22UL1007STRRED-ND and 2328-22UL1007STRBLA-ND

12V/2A power supply (comes with a barrel jack adapter): such as https://www.amazon.com/Adapter-SANSUN-AC100-240V-Transformers-Switching/dp/B01AZLA9XQ?th=1

Wire connectors: ideally use six 5 port Wago brand https://www.amazon.com/Wago-Port-221-Splicing-Connector/dp/B07NKSHVF6?th=1

You will also need access to scissors, tape, a wire stripper, and a small phillips head screw driver.

## Assembly
1. Laser cut the black acrylic (bottom and sides), clear acrylic (top), and diffuser paper (top).
2. Screw the LEDs into the the bottom in the indicated positions (rastered on by the laser cutter), threating the wires through to the underside of the box.
3. Assemble the sides and top of the box, securing with tape. Affix the diffuser paper to the top of the box, affix with tape.
4. Now you need to connect all the LEDs together in series and to the power source. First strip the wires so you have more uncoated wire to insert into the connectors. Next cut six ~5 inch peices of wire (3 black and 3 red/green if you are color coding) and strip the ends of those too. Then do the following:
 
   a. Take the green wires for the first four LEDs (you can start on either end of the box) and connect them with a 5 port connector.
   
   b. Using a peice of green/red wire you cut, connect that 5 port connector to a new 5 port connector.
   
   c. Connect the green wires for the next three LEDs to the 5 port connector that now has 4 open slots (reducing it to 1 open slot).
   
   d. Using a peice of green/red wire you cut, connect that 5 port connector to a new 5 port connector.
   
   e. Connect the green wires for the next three LEDs to the 5 port connector that now has 4 open slots (reducing it to 1 open slot).
   
   f. Using a peice of green/red wire you cut, connect that 5 port connector to the barrel jack adaptor.
   
   g. Repeat a-f for all the black wires.
7. Secure all the wiring with tape.
8. Attach the power supply to the barrel jack adaptor.
   
## Photos of Completed Box

Top view:
![TopView](https://github.com/laurenminer/GreenLightPads/assets/56128045/25d81981-618b-4b56-8344-ae21c73eaf73)


Positioning of vials:
![TopView_withVials](https://github.com/laurenminer/GreenLightPads/assets/56128045/0709d904-7113-4cde-891a-07ff2336cf68)


Side view:
![SideView](https://github.com/laurenminer/GreenLightPads/assets/56128045/13b9bdce-1226-4e6d-a98c-60ce3f5fe089)


Bottom view:
![BottomView](https://github.com/laurenminer/GreenLightPads/assets/56128045/4fdead63-02f8-4bbc-8551-d13a33eac1ee)
