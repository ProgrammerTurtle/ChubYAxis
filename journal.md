# This is the journal of the design and eventual build process of my ender 3 Y axis mod, CHub.

# Total Time Spent:

## Journal Entry 1 2/21/2026
Time Spent: 3 Hours, roughly 6pm-9pm 

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
Time Spent: 1.75 Hours, roughly 3am to 4:45am

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
Time Spent: Hours, roughly 5am to
