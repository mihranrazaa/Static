---
title: "Static"
author: "mihranrazaa"
description: "My very own RP2040 based devboard"
created_at: "2026-04-27"
---

# April 27: Started researching stuff:

I will be using a guide and other info available on internet to build my own dev board :)
Why i want to use rp2040 as what i have seen from my current research, RP2040 is very beginner friendly chip... so i will be using this. i have started downloading footprints and symbols for the parts.. 

**Total time spent: 20minutes** 

# April 27 : Schematics

I have done some basic stuff, this is my first time buiding anything with bare-bones chips, and reading datasheets and ts is lowkey fun, i currently have added decoupling capacitors 9 for IOVDD where 1 is 1uF and 8 are 0.1uF and 3 for VDD where 1 is 1uF and 2 are 0.1uF. Also have added type C receptacle and connected some internal pins now i will do some more after i eat, the data-sheet is of 646 pages :crazy do i have to go through all if i have to build something? that's all 
BYEE

<img width="984" height="739" alt="image" src="https://github.com/user-attachments/assets/7673d42f-a14e-4fac-bd64-c39e46318b84" />
<img width="1094" height="777" alt="image" src="https://github.com/user-attachments/assets/221b1312-4b84-486b-ad8d-9bc9220abbe1" />

**Total time spent: 2hour** 

# April 29 : More schematics

I have made schamtics for type c connector added voltage regulator , also added crystal connected it with all the needed pins, now i will Add Flash storage then most of the core stuff would be done, i also made live writings as the stuff was doing, anyways i'll add it in the end,. I'm thinking of making the pcb square and not rectangle like every other....

here is more journal..
- couldn't find 4 pin Crystal i dunno if it is a kicad thing but from what i have searched it is usually their in kicad...
- alright found out it is a issue with kicad itself.. it is a known issue which has been tracked that symbol has a missing forth pin smh, i'll download a third party symbol for it then or maybe switch to easyeda hehehehehe 
- i'll try updating kicad if that solves the issues, fyi i'm on fedora...
- Alright found the symbol and footprint of another crystal which i can use, downloaded it added it, saw it's datasheet 4 and 2 are gnd like others i thought it differs with every distributor but ok that's good. not i will connect it 2 and 4 to gnd and other to XIN and XOUT.. 
- Alright found out the symbol in kicad which is by-default, the one with 3 pins works, the gnd pin connects the both 2 and 4 pins so that's good i'll change it to that then i already downloaded another symbol but i will still replace it becuase it still looks more simpler... tbh i just want to change...
- I'll write a journal real quick it is better if i break the work in chunks so it doesn't look like inflated..


Random photos i took during work...
<img width="795" height="515" alt="image" src="https://github.com/user-attachments/assets/637ca8a3-ac34-405a-b8d2-b54e24e893d8" />
<img width="1316" height="695" alt="image" src="https://github.com/user-attachments/assets/4a4a741a-81ae-4d8c-bce9-23b3ac621a65" />
<img width="840" height="654" alt="image" src="https://github.com/user-attachments/assets/5124c444-81ea-4070-a8dc-5585f0f66548" />
<img width="1075" height="459" alt="image" src="https://github.com/user-attachments/assets/d9fe9b07-b6d9-4b04-9da1-deb072a73a55" />

Now my journal entry will be after i made the whole schematics... see ya then!

**Total time spent: 1.7hour** (i dunno how much time i spent it might be more then 2, bcz it was in multiple chunks :sob)

