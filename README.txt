#############################################################################
#############################################################################
###########       ###       ####        ##        #######   BEAT    #########
###########  ###  ###  ###  ####  ####  ##  ####  ###########################
###########  ###  ###  ##############  ####  ################################
###########  ###  ###  ###########  #########  ##########  BADGE    #########
###########  ###  ###  ###  #####  ###########   ############################
###########       ###       ####        ###       ###########################
#############################################################################
#############################################################################

So its pretty simple. And there are options. Options are good.

The relevant code is just in dc22_badge_human_mod. 

Line 154: The 4 buttons above E,F,C,and O can be programmed to trigger different 
light animations. 

Copy the example light animation patterns that start in the code around line 311.
The lights trigger pins on the right side of the badge. 

LEDS => 7 6 5 4 3 2 1 0

Pins (Right side)
L/R
0
1
2
3
4
5
6
7 - Program change
8 - 0
9 - 1
A - 2
B - 3
C - 4
D - 5
E - 6
F - 7

Test with an LED. 
Connecting the anode to pin F(right) and cathode to E (left) will light the LED when the
animation is in position 7.
Switching polarity will trigger the LED at position 6.

Positions speakers along the pins and program animations in animations section.
Pretty straight forward.


