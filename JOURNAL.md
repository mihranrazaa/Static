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

# April 29-30 : Completed Schematics

I have completed the full schematics, the dev board is very basic but this is my first time, anyways i have written a live journal too which i will paste below, also i thought of adding battery but for now i think i will first build this, then make a new version of this, with more features and improvements!! I'll also add random images i took during the sessions. Also i have added a draft design of pcb like using the footprints in the pcb window of kicad you will know... 

here is more journal..

- I'm using W25Q128JVS chip for flash memory
- i have connected all the pins i will add button in CS pin, also have to add decoupling capacitor to filter noise.. 
- Yay almost completed the schematics of flash memory!!!
- Now i want to make the IO headerss
- I have connected mcu pins with all the global labels now first i need to think of how i want the design to be before adding the headers, as i said i was thinking of making it a square but how big of a square? also have to add the port so i have to keep that in front see i have ot decide that first.... 
- I still have no clue :sob aaahhh what i havedone is that a pico style has 20 pins on the opposite sides, i have to make 10 pin by 10 pin square and make it like a Processor chip but RP2040 hehe that is my idea f it i'm sticking to this only... 
- I made a rough drawing i'll make another a bit more detailed one>..
- Alright DOneee with headersss, i have 4, 10 pin headers now i will clear up and and prepare the schematics...
- DONEEEEE SCHEMATICS.
- now i will add footprints, then pcbbbbbb routing let's goo 
- i'll journal once i complete the footprint stuff.
- ah i'll do the footprints after sleep, i need sleep now to function properly... 
- ALright now finding parts for footprints, we already have 
- Added all the footprints!!! now i will journal 
- of 2 days i think jdlkjsflkjdf
- i spent the whole night on this but i also did random shit so i'll reduce the time accordingly..


Images: 

<img width="464" height="491" alt="image" src="https://github.com/user-attachments/assets/82200d1f-0f37-4580-801a-0277ad8c6e5a" />
<img width="1119" height="796" alt="image" src="https://github.com/user-attachments/assets/410f6756-4c52-4953-9270-be0babb2dc37" />

<img width="840" height="654" alt="screenshot_20260429_121410" src="https://github.com/user-attachments/assets/91f6848e-ec0c-472b-8b79-de2cc84ca18a" />
<img width="1501" height="868" alt="screenshot_20260429_131104" src="https://github.com/user-attachments/assets/de0ac79b-5289-4d5c-9813-cfa71bf43e2a" />
<img width="1111" height="764" alt="screenshot_20260429_131205" src="https://github.com/user-attachments/assets/841d1015-07e6-408c-b41f-932e266f5d10" />
<img width="731" height="819" alt="screenshot_20260429_133249" src="https://github.com/user-attachments/assets/ad0ac316-21f6-47ec-9c5d-2d322ca1c304" />
<img width="190" height="185" alt="screenshot_20260429_133847" src="https://github.com/user-attachments/assets/948cf332-e254-4aaa-89bb-6253eb5efad3" />
<img width="874" height="710" alt="screenshot_20260430_021505" src="https://github.com/user-attachments/assets/02a96eb2-b414-41ad-9fa7-bedfb718026f" />

**Total time spent: 5.5hours**
