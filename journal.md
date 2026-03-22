<img width="2193" height="2102" alt="ChubYAxis Main" src="https://github.com/user-attachments/assets/d1292404-8f31-409b-92c4-56f6989aab27" /># This is the journal of the design and eventual build process of my ender 3 Y axis mod, ChubY.

# Total Time Spent:

## Journal Entry 1 2/21/2026
Time Spent: 4 Hours, roughly 6pm-10pm 

Alright. Rework submission deadline is technically passed, but I was told that if I could get it submitted before the form closes, it will be ok. 
So here it is. One night, one turtle, and one ender 3. 

First things first I downloaded the Kevender cad as reference, as it is very well designed by a friend of mine. From there I got the ender 3 bed assembly and frame measurements. 

<img width="1148" height="1019" alt="image" src="https://github.com/user-attachments/assets/e32e35a4-26f4-4f4f-a584-d2d0167c8ed5" />

This is the slightly modified Kevender cad I have (added a bltouch lol). However, I am taking a fairly different approach. 

<img width="1528" height="885" alt="image" src="https://github.com/user-attachments/assets/2a5ecfdb-260a-4771-bad1-4377bb3d355b" />

I started off with the printer base. The above photo is my base. The below photo is the stock base. 

<img width="1214" height="663" alt="image" src="https://github.com/user-attachments/assets/58d5f849-c0e5-4655-80fc-26773b6906fb" />

I took the middle 4040 extrusion and moved it to the back of the frame. I will then be purchasing a second 4040 to go on the front of the frame. I know in my model the rear one doesn't have any cutouts, but this is just because I wanted to keep the cad clean.
Now for the big one. Stock, the printer uses a 2040 extrusion for the Y extrusion. Kevender uses a 4040, like the ender 3 Pro did. 
But, the cooler option, is a 3090 extrusion. 

<img width="1195" height="805" alt="image" src="https://github.com/user-attachments/assets/0e90ede6-bc97-472a-9011-a200baa60790" />

I got this idea from [LH Stinger](https://github.com/lhndo/LH-Stinger), as it uses the same 3090 extrusion for the y. However, he does not mount it to a full box base like mine is. 
This base also allows me to eventually put the electronics down there, but that will not be for a long time as I am not fully decided on my electronics, so I won't be designing for them currently. 

<img width="1385" height="700" alt="image" src="https://github.com/user-attachments/assets/39ef53b9-4fd0-42be-8e2c-0fb8fae38f68" />

Onto this is mounted two MGN12H rails. I was looking into doing MGW12H or something but those are stupidly expensive ($50-$60 per rail). This is the main structure of the mod. 
Note, the reason the y extrusion extends out the front and not the back is because bedslingers typically need more travel in the front of the printer due to the toolhead/nozzle being offset towards the front. A perfectly central toolhead would be cool to attempt eventually. 

<img width="1619" height="750" alt="image" src="https://github.com/user-attachments/assets/c93a5e08-7ff9-449f-87e1-6ce0b0240351" />

I then imported the ender 3 bed assembly and aligned it to the rails. This allows me to create the bracket/carriage. 

<img width="917" height="446" alt="image" src="https://github.com/user-attachments/assets/0e9b05ab-8079-4cba-9841-263828838363" />

That looks like this. It bolts to the bed carrier plate with 14 screws (wow) and the two big holes on the top are for locating the carriage onto the carrier plate - as I have to drill holes into the plate. 

And that is 3 hours of progress ! About an hour of the time was spent looking at existing y axis mods and checking prices on various component options (extrusion sizes, rail sizes, motors). I will only have to purchase one motor for this as I already own one, and two are needed for awd. 


## Journal Entry 2 2/22/2026
Time Spent: 2.5 Hours, roughly 1am to 3:30am

Had to take a couple hours break to shower, eat, bring in groceries, etc. my mom is hospitalized currently so I have to pitch in around the house a lot more. 

Anywho, I made a belt tensioner/belt mounting. Yes, it did take an hour and a half. I had to adjust a lot of the bed mounting so that I could tension before installing the bed carrier and still have a rigid assembly.

<img width="1226" height="848" alt="image" src="https://github.com/user-attachments/assets/9a1658c4-32c0-4fc7-9aec-13b4fd901238" />

The two center blocks are belt mounting. The one on the left is rigid mounting, and the one on the right is tensioning. These are quite cool wedge style clips that I used on my DoNotDelta project. 

<img width="455" height="461" alt="image" src="https://github.com/user-attachments/assets/3838bb28-5a55-4622-8b5c-1cc3d30d5327" />

Basically a wedge with teeth slots into the main body, which has another wedge. The belt interfaces with those teeth and is "pinched" by the wedges. This is a really, really elegant belt clip in my opinion. Since the grip on the belt gets tighter with increased tension, the belt will tear before it slips. 
I used insert nuts instead of my typical heat set inserts for two reasons. One, I didn't want to worry about alignment. Two, I need the ability for the screws to extend past whatever fastener they are threading into, otherwise there isn't enough travel for tensioning. That is really difficult with inserts because molten plastic bulges.
Oh, and I am less scared of nuts being pulled out by the tension. 

I also changed a bit of how the bed carrier mounts. 

<img width="1344" height="627" alt="image" src="https://github.com/user-attachments/assets/aeca7ba7-3332-44ba-bbd1-2ef58849528a" />

So we have these 3 screws on either side that thread directly into the plate.

<img width="1488" height="1086" alt="image" src="https://github.com/user-attachments/assets/c7b5f81a-7c23-44d4-8db4-68ff784e0a0c" />

And then the middle 4 thread into the part from the opposite direction, into heated inserts. This is great because it allows me to print the bed carriage laying flat on the big flat side and not worry about layer lines - the 3 screws on either end will compress the layers together. I should probably add washers under the screws aswell. 

That's all for this entry. I am trying to split it up really well to prove I am not inflating hours. 

## Journal Entry 3 2/22/2026
Time Spent: 4 Hours, roughly 3am to 7am

The past two hours were motor mounting and belt routing. Honestly went a lot smoother and took less time than I expected, this is going quite well. 

<img width="1271" height="988" alt="image" src="https://github.com/user-attachments/assets/3925afa4-79e1-46c6-adb0-2af063c486c8" />

<img width="1385" height="1060" alt="image" src="https://github.com/user-attachments/assets/5ac0a5f7-9212-4f04-8ce3-1aeb4098adf4" />

This is the front assembly. The modules are splti in to two sides, with one having the motor mounted to it and one having the bearing stuck in it. 
They're pretty simple. One motor, one pulley, one idler. Because I did tensioners on the bed carriage I can make this way more rigid than if it had to do tensioning. Following the theme of Chub, these are super thick. Most walls are over 10mm thick. 

<img width="892" height="568" alt="image" src="https://github.com/user-attachments/assets/eba3f881-40de-4b07-9998-20b929f23645" />

It started super simply with me putting the motor, pulley, and idler where I need them, and then I just built up material wihtout blocking the belt or access to the pulley grub screws. The pulley is in line with the bottom t slot so that the belt can pass through that, while the idler is in line with the tensioner, so the belt can attach to the bed. 

Here is a couple photos to show the progression from super generic basic shapes to the final assembly. 

<img width="810" height="515" alt="image" src="https://github.com/user-attachments/assets/040ec64b-1af6-49e9-bbce-0688c824fa1f" />

<img width="848" height="570" alt="image" src="https://github.com/user-attachments/assets/d7e3ea7e-0a3c-4d88-b2f3-f357784a4315" />

<img width="1009" height="852" alt="image" src="https://github.com/user-attachments/assets/0e7a011c-9c5e-4666-9452-91fb0651b9b8" />

<img width="943" height="766" alt="image" src="https://github.com/user-attachments/assets/b4b615f5-d399-497a-b4fd-170ed5a32984" />

<img width="1065" height="821" alt="image" src="https://github.com/user-attachments/assets/d85d6730-1fb9-42d6-9d0d-12e3d997f00c" />

And then the next photo would be the final version. Fairly straight forward. Oh, the top groove thing is for installing the idler 5mm pin. 

<img width="1261" height="756" alt="image" src="https://github.com/user-attachments/assets/c5d5fed1-3943-46a5-862e-24501c5ed099" />

The rear one is literally just the front one with the bottom mounting holes chopped off, because there is frame in the way. I did not add more mounting holes as it should be able to brace against the frame fine without it. 

<img width="1003" height="852" alt="image" src="https://github.com/user-attachments/assets/8755734a-cf84-48d4-91fb-07693d600d5c" />

That leaves the current state of the mod like... this! 

<img width="1666" height="859" alt="image" src="https://github.com/user-attachments/assets/18b92c51-4f61-4ca4-a876-cb5e5463bc5b" />

I really just have some bracing/brackets to model real quick and then I can do all the logistics for submitting. I think this project will run at a bit more than $5/hour, but not by much. 

## Journal Entry 4 2/22/2026
Time Spent: 1 Hour, roughly 7am-8am

I made the brackets and did the final additions of screws and whatnot. I need to do BOM and logistics for submission ASAP, but. 

<img width="1296" height="880" alt="image" src="https://github.com/user-attachments/assets/e1b8c14e-90c2-4ee7-9a2f-750c852535e8" />

7 brackets total, 4 being on the base 4040 and 3 connecting the 3090 to that base 4040. 

<img width="1059" height="621" alt="image" src="https://github.com/user-attachments/assets/3363a041-e855-4a7f-9766-777ffd3cab5d" />

These are the corner 4040 ones, which are quite fancy. 

<img width="923" height="722" alt="image" src="https://github.com/user-attachments/assets/2d53bdba-bdd2-4cd2-bdf7-bf1cf920f284" />

And these are the 3090 -> 4040 ones, which are not nearly as fancy but are easier to print. 
Both brackets started as simple L's with holes and then I just messed around adding ribbing/bulk material until it worked out. 

<img width="792" height="514" alt="image" src="https://github.com/user-attachments/assets/f8b8fd37-f7bb-4c22-9e93-c4f6926ba1bc" />

This is an early version of the 4040 corner ones. After this I just did tons of fillets and added 4 more holes. 

<img width="775" height="518" alt="image" src="https://github.com/user-attachments/assets/ff6eb75d-894a-46d3-a477-28d1b394e471" />

That type of thing. The other bracket is just a triangle, so I don't think I really need to show the creation? I made an L, sketched holes, and then made the L a triangle. 

Anyways, I am sleep deprived and cutting it really close to the form closing. So, logistics time. 

## Journal Entry 5 2/22/2025
Time Spent: 1.75 Hours, 8am to 9:45pm

God I am so tired I just wanna sleep. I spent an hour cost optimizing the bom and trying to find things that fit. Amazon actually ended up being cheaper for some stuff. And then I made renders and fixed my readme. I am done. Bed time. 

<img width="2193" height="2102" alt="ChubYAxis Main" src="https://github.com/user-attachments/assets/5ecbe04e-494f-4acf-a69c-421ee3a8b0a3" />

<img width="3871" height="1649" alt="ChubYAxis Topdown" src="https://github.com/user-attachments/assets/3d00f42b-bc70-42d6-b253-96869c62982b" />
![Uploading ChubYAxis Topdown.png…]()
