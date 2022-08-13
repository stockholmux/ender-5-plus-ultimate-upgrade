# Mounting the Dragonfly BMS

Moving from a stock Creality PTFE-lined hotend to an all metal hotend has been a larger challenge than expected.

I decided to get a [Phætus Dragonfly BMS](https://www.phaetus.com/dragonflybms/). There are a lot of hotened options, but this one is marketed as a drop-in replacement for the stock Creality hotend and it ticked the rest of the boxes.

Visually, the drop-in nature seems to make sense. Mounting holes line up and it's exactly the same height as the stock hotened. I didn't even have to change my z-offset!

However, where this gets iffy is the thermistor. Creality hotends use a glass bulb type of thermistor and the Dragonfly has a hole bored for a brass tube. Included in the package is an "adapter" and a packet of thermal grease. The adapter is a brass tube open on one end. The instructions included in the package are poorly translated (or just poorly written).

<img width="199" alt="Instructions from Phætus" src="https://user-images.githubusercontent.com/1152927/184501870-cdac4266-4bb5-44d4-a5ab-d5057e761999.png">

It clearly mentions "adhesive" and "(attached)". Is "(attached)" supposed to mean "(included)" or is that a reference to sealing in? 

Included in the box is GD900 thermal _grease_. Nowhere in the installation guide is grease ever mentioned. Asking in one of my 3d printing communities, people assumed it was a [hardening paste like Slice sells](https://www.sliceengineering.com/products/boron-nitride-paste). However, googling around about GD900 all the product descriptions are explict that it's a grease, not an adhesive (["As opposed to thermal adhesive, thermal grease does not add mechanical strength to the bond between a heat source and the heatsink."](https://www.pcboard.ca/gd900-thermal-grease-5g-bag)). 

I'm not the only one that is confused by this. Clearly some people installing this just kind of packed the brass tube with GD900 and let the glass ball just rest inside the tube, leading to the thermistor inevitably slipping out during printing (thankfully, yielding an over-heat error instead of a meltdown). Some people did mention crimping the brass tube around the delicate glass ball but more seemed to have given up and just got a new brass tube thermistor.

In my case, I decided to crimp the glass ball in the GD900 packed tube as I was not interested in rerouting a thermistor cable to a mainboard that will be ripped out shortly. I have plans for cable management but just not yet and it's a job I don't want to do twice.

I'm including these instructions to show how *I* did it - your experience may not match mine. This is an important part of your printer so exercise caution.

## Crimping-in the thermistor

1. Clean the glass ball with isopropyl alcohol to remove any oils that your fingers might have transfered.
2. Pack the brass tube with GD900 and coat the glass ball. I used a toothpick to get it into the tube and on the thermistor. 
3. Slide the glass ball into the tube. I went a little further than the Creality mounting, noting where the glass ball will end up in the tube.
4. Use a pair of needle nose pliers to slightly squish the open end of the brass tube. Make sure that you're only crimping the very edge of the tube and it's far from the glass ball.
5. Test the connection. Some play is okay but the glass ball shouldn't be able to come out. Be gentle when doing this - the glass ball and wires are pretty delicate.
6. Take the remaining GD900 and apply it to the outside of the brass tube and then insert it into the heat block. The crimped edge may not slide back into the heat block fully but as long as there is good contact between the tube and block, it should be fine.
7. Finish mounting the hotend.
8. Turn on your printer - the nozzle temp should be accurate to your ambient temperature. 
9. Test heating the nozzle, carefully working up the temperatures and length of time holding temperatures.

I hope this helps someone in the future.

