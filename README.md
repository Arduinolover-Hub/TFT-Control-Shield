# TFT-Control-Shield

We can build amazing project with the display TFT 2.2" 240x320, or another bigger, 
in this case We are going to focus in this display. For that the reason of this pcb, 
to be able to have a ready to use pcb to test and program and play with our TFT display. 
Let's get started

1. Main features:
  The PCB will be a shield for Arduino UNO or other board who respect the same distribution of pins 
  like the Arduino UNO. Our Shield consist on 4 main push buttons (Yellow Color   12x12 dimension), 
  2 push buttons (6x6 dimensions) and a Joystick.
  
2. Schematic Diagram

In this oportunity We are going to use the Software EasyEDA
( which offer a desktop and online PCB design software). https://easyeda.com/
Schematic Diagrama: https://oshwlab.com/Ardlover/tft_shiel  
 
As we mentioned before this board is a shield so first important step is to place the Arduino Uno pinout Footprint, 
this is very easy because EasyEda offer this Footprint (From their ouw system and from user contributors)

The following step is to connect the TFT display with our Arduino and for that We have to consider one important aspect, 
this TFT display works with +3.3V level of voltage so We can not connect directly to the board, it will not work. 
For that We make some extra circuit a voltage divisor with 2 resistors (470 ohms and 1Kohms) so with that We will not have
any problem and we will not need to buy an extra board.

After that We have the Inputs section, Joystick and Pushbuttons, so with them we will be able to manipulate 
the TFT, of course first We really need to program it correctly.

3. PCB Layout
Project Files: https://oshwlab.com/Ardlover/tft_shield

We are working with EasyEda so you can access to the projects files inmediately, clone it and make changes. 
This is not a huge pcb, have a normal quantity of componentes so there will not be so many difficulties to rout the pcb.

4. 3D VIEW
EasyEda also offers the 3d View feature, which is very very good, maybe the only thing to consider is that 
we should add the 3d model in the extention that the software allows.

5. How to Order on JLCPCB
We are going to order from EasyEDA to JLCPCB, they are co-companies and We just jump from our desing to the orders, lets check it out.
JLCPCB: https://jlcpcb.com/IAT

5.1.Click on File -> Generate PCB Fabrication
After we select this options We can see a brief resume about our order and we have to continue in JLCPCB
5.2.IndicatetheFeatures
5.3.Addyourshippingaddress
5.4.Make the payment and finish the order
5.5.Receive your PCB

6. Why JCLPCB?
JLCPCB has been at the forefront of the PCB industry. With over 14-year continuous innovation and improvement based on customers' need, we have been growing fast, and becoming a leading global PCB manufacturer, who provides the rapid production of high-reliability and cost-effective PCBs and creates the best customer experience in the industry.

-Most Efficient, Economic, Innovative PCB Solutions
-Higher Quality
-Lower Cost
-Faster Delivery

7. Building the PCB
Attached you will find the BOM (bill of materials) needed to build the PCB, as you can see in the list 
you can the designator that You can check also with the schematic circuit.

8. Thanks
Thank to:
JLCPCB: https://jlcpcb.com/IAT
EasyEDA: https://easyeda.com/
