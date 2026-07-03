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

# May 5 : Me back

Alright i couldn't do anything for 2 days as i had to go to a family event, so i had leave the project midway, anyways i have started pcb routing and how i want the board to look like so i want it like small processor, and i made pin header all around, the issue is i don't think i can all the parts in that small box i might have to incerease the box area so everything can fit properly and get routed, i have already changed schem of 1 pin header 3 times becuase it wasn't fitting the box, i broke it in 3 pieces and made adjustements. I'll ask the doubt in the channel and see what they suggest... 

anyways i also have live journal which i did before i went to the trip and then i'll add images...
- Alright so i have started with the design, the changes here is i will be breaking one 1x10 header in 2 nope actually 3 parts, first two parts will be near type c (completing the chip look i want), and the remaining will at the same place just cenetred, that is the plan right now!!!!
- alright i did 4-3-3 but then type won't fit how i won't it, i will change it to 6-2-2. which should still look how i want it to and would fit the port too, or i can move the port forward nah that won't look good, lol i'm just thinking of looks rn i don't if routing would be possibe in that space lol, i also have to know the good practices for routing a dev board... 
- Me go got some work, i'll continue after i comeback, byrree.

images

<img width="874" height="710" alt="screenshot_20260430_021505" src="https://github.com/user-attachments/assets/daf340ac-c935-45f5-a5d8-6328737a51a9" />
<img width="1119" height="796" alt="screenshot_20260430_085151" src="https://github.com/user-attachments/assets/e9c5a8e9-d2ef-4564-bd62-e96dd4850146" />
<img width="464" height="491" alt="screenshot_20260430_085444" src="https://github.com/user-attachments/assets/0cc36049-0d62-437b-bd31-84003effdde8" />
<img width="555" height="441" alt="screenshot_20260430_105549" src="https://github.com/user-attachments/assets/8b5d90c4-afc6-42f2-b090-cc7bc729e7e6" />
<img width="814" height="633" alt="screenshot_20260505_140357" src="https://github.com/user-attachments/assets/08eec663-c90e-497d-9cbc-983d08a62164" />
<img width="611" height="519" alt="screenshot_20260505_141309" src="https://github.com/user-attachments/assets/5e55f4eb-0fc9-499d-bc96-c65bfd4b9ce8" />
<img width="659" height="492" alt="screenshot_20260505_141322" src="https://github.com/user-attachments/assets/cb364126-1fbb-46c5-87b2-9aaccd7f0cb7" />
<img width="941" height="549" alt="screenshot_20260505_142358" src="https://github.com/user-attachments/assets/f4e0ff91-7a4e-4ce1-8538-9c312bbcce8a" />

**Total time spent: 3.5hours**

# May 7 : Changing shape :/

I wanted to make a square shape board, but now i have to change it to rectangle, bcz it is my first time using no modules, i'm getting confused.. I'll use pi pico type shape, and try to copy that. so it can be easier for me.. anyways here is my live journal.. during the session.. 


Live Journal 
- placed Crystal with it's resistor and caps, i'll first organize all the resis and caps with all the components, so i don't have to check everytime....
- Again changing flash memory footprint....
- Also almost completed positioning LDO, with it's caps...
- Now FLash memory fp is more smaller yayyy
- NOw me feeling sleepy i'll get some rest, then continueee. BYEEE
- Me getting confused now :sob with the routing, this resistance is WHAT LEARNING ISSSSS!!!!!
- Need a coke or something first......
- THe issue is the caps and resistors thats all also i think my kicad might be glitching or having issues... 
- Alright progress progresss, added more caps and resistors, though i'm currently just triyng to complete the rough positioning, so i get an idea on how i can improve it....
- Placed more Caps and Resistors, i swear i'm hating rn doing this. I should eat something :sob 
- completted routing Flash memoryyyy
- Me changing the shape gng :/ have to, i can't this is my first no module project and it is better if i just copy pi pico type shape... SAD. i'll make another one after this... 
- Alright changing... 
- First have to change schematics, for pin headers
- also lemme make a journal before that, so i make another journal with the new shape...

Here are the images.. 

<img width="659" height="492" alt="screenshot_20260505_141322" src="https://github.com/user-attachments/assets/309e7ec5-c052-4e5d-a408-c03566cd3cf1" />
<img width="941" height="549" alt="screenshot_20260505_142358" src="https://github.com/user-attachments/assets/b804d410-96ee-467f-b25d-f408578092fc" />
<img width="924" height="660" alt="screenshot_20260505_150800" src="https://github.com/user-attachments/assets/016e23ff-d6d1-441a-8e65-77cb2db68ecc" />
<img width="779" height="451" alt="screenshot_20260505_150808" src="https://github.com/user-attachments/assets/4ce69d5e-f1be-412d-9e0c-e609a482c46c" />
<img width="641" height="368" alt="screenshot_20260505_174101" src="https://github.com/user-attachments/assets/1031f90d-88bb-4a06-b1a8-fe9e8fc727c6" />
<img width="1474" height="632" alt="screenshot_20260505_174106" src="https://github.com/user-attachments/assets/62abd82e-48bc-4e6a-9abc-8531b17db53d" />
<img width="988" height="679" alt="screenshot_20260506_185420" src="https://github.com/user-attachments/assets/5b8ed226-24c1-4e8e-a016-4b6d9fe4f5d3" />
<img width="1920" height="1080" alt="screenshot_20260506_200607" src="https://github.com/user-attachments/assets/62318d04-e513-4664-9268-6760c2e36fef" />
<img width="1668" height="696" alt="screenshot_20260506_200738" src="https://github.com/user-attachments/assets/3eb2e924-3138-47c9-a261-80abd24cd9ff" />

**Total time spent : 2.5hours** Probably more but this one is in so many chunks that it is better to just give the confident minimum..

# July 3 : Finally Done!!

It has been a really long break but i'm finally done, i had to go through some exams and stuff and today i finally completed the routing, i was doing one-two routes or whenever i got time (i'm talking about this week only..) but it is done, i had to move some components and stuff to route some GPIOs also didn't knew what to do with gnd pins which are not connected to the ground plane.. then i got to know that i have to use vias for that too, so did that and yeah that's all :)

i also made the production file and now i will complete the git page and prepare to submit!! byeee

Here are the images --

<img width="456" height="694" alt="screenshot_20260703_175827" src="https://github.com/user-attachments/assets/7a86ca74-a207-4df7-b9f3-8cd17fbd7983" />
<img width="981" height="180" alt="screenshot_20260703_175843" src="https://github.com/user-attachments/assets/f329f2c6-5e03-4cfe-a149-72d10da97d67" />

**Total time spent : 2hours**
