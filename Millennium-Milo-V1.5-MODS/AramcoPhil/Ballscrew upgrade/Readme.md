# This is a SFU1204 Ballscrew Upgrade for Milo V1.5

**This Upgrade is specifically tailored to Dold Mechatroniks "DM" Ballscrews, which have a simplified end profile, so you either need to stay with those or modify this design to fit your ballscrews.**

You'll need to print the provided STLs as well as buy the following parts:

## Y Axis:

Ball Screw: https://www.dold-mechatronik.de/Kugelumlaufspindel-SFU1204-DM-485mm

### Bearing side: 

https://www.dold-mechatronik.de/Rillenkugellager-608-2RS-8x22x7mm

https://www.dold-mechatronik.de/DIN-471-Form-A-Sicherungsring-fuer-Wellen-Stahl-blank-A8-2-Augen Size A8/2

### Motor Side:

https://www.dold-mechatronik.de/Schraegkugellager-zweireihig-30-8-2RS-8x22x11-mm

https://www.dold-mechatronik.de/Lagerhalteplatte-40x40mm-B18-Easy-Mechatronics-System-1216A-1216B

https://www.dold-mechatronik.de/DIN-988-Passscheibe-Stahl-blank-d8mm-D14mm-H05mm Size d8 D14 h0,5

https://www.dold-mechatronik.de/DIN-439-Sechskantmutter-niedrige-Form-verzinkt-M8x1-feingewinde

https://www.dold-mechatronik.de/Wellenkupplung-RB-flexibel-D18L25-500-635mm



## X Axis

Ballscrew: https://www.dold-mechatronik.de/Kugelumlaufspindel-SFU1204-DM-535mm

### Bearing side: 

https://www.dold-mechatronik.de/Rillenkugellager-608-2RS-8x22x7mm

https://www.dold-mechatronik.de/DIN-471-Form-A-Sicherungsring-fuer-Wellen-Stahl-blank-A8-2-Augen Size A8/2

### Motor Side:

https://www.dold-mechatronik.de/Schraegkugellager-zweireihig-30-8-2RS-8x22x11-mm

https://www.dold-mechatronik.de/Lagerhalteplatte-40x40mm-B18-Easy-Mechatronics-System-1216A-1216B

https://www.dold-mechatronik.de/DIN-988-Passscheibe-Stahl-blank-d8mm-D14mm-H05mm Size d8 D14 h0,5

https://www.dold-mechatronik.de/DIN-439-Sechskantmutter-niedrige-Form-verzinkt-M8x1-feingewinde

https://www.dold-mechatronik.de/Wellenkupplung-RB-flexibel-D18L25-500-635mm


# Needed Modifications to the ball screws

The ball screw nuts are a tad too wide to fit the 40mm inside the C-Channel Profiles of Milo. Therefore a slight "adjustment" with an anglegrinder is required. Shave down the curved sides of the nuts until you barely miss the outermost screw hole. (We are not using that screw hole, so this is fine.) **I reccomend taping everything up and inserting an M5 grubscrew into the lubrication port in order to keep the grit out from the ball screw and nut.**

Before: ![Before](https://media.discordapp.net/attachments/810620768609370158/1159416023817134100/IMG20231005105407.jpg)

After: ![After](https://media.discordapp.net/attachments/810620768609370158/1159418940687142922/IMG20231005110442.jpg)


# Known Issues

This Mod reduces the 8mm pitch from the leadscrews down to 4mm so your Motors will have to spin twice as fast for the same travel speed.
I had to reduce my rapid moves to 2000mm/min, i am planning on upgrading to 48V to alleviate that.
**You will need quite beefy motors to sustain this mod.**
