+++
title = "EFI Conversion"
date = "2016-08-01"
tags = ["Engine - P40"]
+++

This information is further to the [Megasquirt How-To][Wiki: megasquirt] and [Edis Electronic Ignition How-To][Wiki: edis] wiki pages.

## Posts taken from rmp-o.com forum

### Post by **chimpboy** on Mon May 28, 2007 at 11:55 am

> I would say that if you get an EA falcon, which will cost almost nothing complete, it will come surprisingly close to just bolting on. You want the single-point injection model, which I think has a "3.9" badge.

> You'll just pull off the carby and put the ford throttle body injection on in the same place. You might be able to file some bolt holes oval, or you might have to make a small adaptor plate.

> The fiddliest bit will be running a a second fuel line. Since you have (I think) a spare 60, you will probably be able to put your spare fuel line in next to the original one and it will look pretty close to factory. I can't remember if there's a suitable hole or fitting in the tank to connect the return line to but at worst you could tap into the plate that the fuel level sender is attached to (rather than drilling into the tank itself).

> I definitely wouldn't bother with multipoint injection from an EF or whatever, it's far too complicated and just tapping the injectors into the inlet manifold is probably very far from optimal anyway.

> Throttle body injection is really just like an electronic carby. Very simple and reliable and more than adequate for this engine. I think you'll find it performs better and is more economical, and if you do take it off-road it will work much better on slopes than the carby does.

> In answer to someone's previous question, the distributor doesn't need to be connected at all, except maybe a signal wire to detect engine speed (can hook to the coil same as you'd connect a tacho).

> As you know I've just converted the Stag to EFI and it was very, very worth it. Funny thing was I got all the EFI gear for $200, then sold the old holley four-barrel for $220. I don't think you'll get $220 for your G60 carby though

> You could even find an EA on gas and go dual fuel at the same time

### Post by **David_S** on Mon May 28, 2007 at 10:35 pm

> Here's my basic system as I sent to Swerve

> TBI of Falcon EA (4L straight 6)
> Megasquirt ecu and relay box (see [MegaSquirt.info](https://megasquirt.info/))
> LC-1 wideband oxygen controller (wideband O2 is essential for tuning)
> Existing mechanical pump feeding a surge tank which in turn feeds a high pressure external pump to pressurise the injectors (2)
> CLT sensor (coolant temp)
> MAT sensor (manifold air temp)
> TPS throttle position sensor (Part of Falcon tbi)
> Fuel pressure regulator (Part of Falcon tbi)
> Air filter box modified from one off a GQ diesel
> RPM signal from coil

> At present the megasquirt is set up to control fuel only but once I have it fully sussed I will control spark too with the Megasquirt using input from my distributor (pertronix ignitor) with the vacuum and centrifugal advance locked down.

> And yes the first test runs are impressive. Rocketed up a steep fire break on Sunday on all-terrain tyres where previously I ran out of oomph with the carb and struggled. A petrol FJ40 on mudgrips couldn't manage it - he died just where I used to struggle. And the P40 idles happily on a 45 deg slope. No more plug fouling when the carb floods.

> Megasquirt is totally open source so you tune it to your engine with a laptop as you go down the road!

> Some additional comments relating to previous posts.

> 1) My surge tank arrangement with external Bosch fuel pump appears to work well. I was not keen to monkey around with an in-tank pump and high pressure lines running the length of my truck. (If you look at the underneath of my truck you will see why!!) With my system I connect the existing LP line 3/4 the way up a cylindrical 2 litre tank with an outlet at the top which connects to the existing return line to the main tank. The HP pump is located under the surge tank and is fed from the bottom of the surge tank. The return line from the TBI feeds into the top of the surge tank.

> 2) The Falcon EA tbi is not a simple bolt on to the existing inlet manifold plate as I believe is possible with the GQ engine (not the P40). I bought a Falcon manifold along with the tbi unit. I cut off the plates from both manifolds and welded the Falcon plate to the Nissan manifold. Needed a fair bit of filing to get a smooth transition. Subsequently I made a 1" spacer to raise the tbi unit. This apparently moves the torque curve to the lower rpm end (good) but I did it mainly to make the air filter and throttle cable fit easier. I also fabricated an adapter so I could bolt my carb back on if I had an ecu failure in the back of beyond.

> 3) I wouldn't bother with rail injection and not sure anyway if it would work with 4 runners instead of 6. The tbi unit comes with the fuel pressure regulator built in plus the throttle position sensor (TPS) and a fast idle dc motor which I have hooked up as a hand throttle. Also, and importantly the tbi fuel pressure is only 15 psi compared to the 45+ for rail injection.

> 4) I wouldn't transplant the ecu from a Falcon or other donor. It is old technology and you can't tune it readily for your own engine. I have the technician notes for the Falcon units and it don't look simple to tune. Requires special equipment. Half the fun of my efi installation is being able to tune it on the road. Additionally the Falcon unit requires a signal from the Ford TFI distributor so you have to get one of these and graft it on to the shaft of your Nissan dizzy.

> 5) The Megasquirt ecu is, in my opinion, by far the best unit for diy. 6 months ago I knew nothing at all about efi now I have a working system. There is a very active Megasquirt forum where most of your software and hardware queries can be answered. You can buy fully assembled units or a kit for $US200. I got a kit and my son assembled it for me without difficulty. The Megasquirt can control both fuel and spark. The software is free and open source so you can modify it as much as you like if you want to.

> 6) The two most difficult things I contended with were the air filter and the wiring.
> a) The Falcon air filter was too large and standard Nissan boxes have round holes whereas the Falcon Tbi is oval. In the end I cut the bottom out of a GQ filter box and replaced it with an oval hole.

> b) The wiring is not really difficult, but you have to be methodical, plan routes carefully and keep up to date drawings as you go. I used the Megasquirt relay board mounted in a weatherproof box on the firewall. All wires from sensors, injectors, ignition, 12V source terminate here. The relay board is then connected to the ecu which I have mounted in the glovebox. (I have had water round my feet and coming out the heater vents in river crossings but not yet in the glovebox!) There are around 20 wires connecting the relay board to the ecu which pass through the firewall. Also a vacuum tube (MAP) to connect to the inlet manifold. The Megasquirt incorporates a MAP sensor.

> 7) A wideband oxgen sensor and controller is expensive but an absolute MUST for tuning. I use the LC-1 controller ($US200) which so far has worked well. They too have an excellent forum to help with installation and other problems. The wideband controller gives the actual AFR (air fuel ratio) whereas a narrow band just tells you whether the mixture is rich or lean relative to stoichometric (AFR of 14.7). With the wideband you can set up an AFR table in Megatune for every combination of rpm and MAP.

> As for performance there has been a marked improvement. The engine revs very freely (would probably go to 6000rpm if I let it). There has been a definite power increase. The torque curve appears to have flattened so that it pulls hard between about 1200 and 3000 rpm. And best of all it does not flood on steep hills.

#### Pictures from post

   |   |   |
:---:|:---:|:---:|
[![][Image: 1]][Image: 1] | [![][Image: 2]][Image: 2] | [![][Image: 3]][Image: 3]
[![][Image: 4]][Image: 4] | [![][Image: 5]][Image: 5] | [![][Image: 6]][Image: 6]
[![][Image: 7]][Image: 7] | [![][Image: 8]][Image: 8] | [![][Image: 9]][Image: 9]
[![][Image: 10]][Image: 10] | [![][Image: 11]][Image: 11] |

[Image: 1]: /wiki/engine-p40/efi-conversion/bitspieces.jpg
[Image: 2]: /wiki/engine-p40/efi-conversion/extractors.jpg
[Image: 3]: /wiki/engine-p40/efi-conversion/relaybox.jpg
[Image: 4]: /wiki/engine-p40/efi-conversion/fuelschematic.jpg
[Image: 5]: /wiki/engine-p40/efi-conversion/mqcc_0009.jpg
[Image: 6]: /wiki/engine-p40/efi-conversion/finishedsetupwithoutairbox.jpg
[Image: 7]: /wiki/engine-p40/efi-conversion/Powerrelayboard.jpg
[Image: 8]: /wiki/engine-p40/efi-conversion/DSCF3062Medium.jpg
[Image: 9]: /wiki/engine-p40/efi-conversion/DSCF3063Medium.jpg
[Image: 10]: /wiki/engine-p40/efi-conversion/DSCF3064Medium.jpg
[Image: 11]: /wiki/engine-p40/efi-conversion/DSCF3066Medium.jpg

[Wiki: megasquirt]: /wiki/engine-p40/megasquirt-how-to
[Wiki: edis]: /wiki/engine-p40/edis-electronic-ignition-how-to
