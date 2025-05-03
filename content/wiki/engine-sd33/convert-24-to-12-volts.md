+++
title = "Convert 24 to 12 Volts"
date = "2016-08-01"
tags = ["Engine - SD33", "Electrical"]
+++

The SD33 MQ's were all released as 24 volt (standard voltage for trucks). When the MK was released, Nissan changed to 12 volt (standard for passenger vehicles). It is possible to convert a 24 volt vehicle to 12 volt, which allows the use of standard electronics such as spot-lights, amplifiers, alarms etc.

Here is a walk-through (for further reading): [http://www.george4wd.taskled.com/mq2412.html](http://www.george4wd.taskled.com/mq2412.html). This page has also been archived as a PDF and can be [downloaded][File: 1].

Also refer to the wiki page [How to use 12 volt parts with 24 volt vehicle][Wiki: how to use 12v]

## Engine Parts

The following engine parts will require attention during this conversion.

### Edic Motor

This is the electric motor on the engine that changes the mode that the injector pump is in (ie stop, run or start). It will need replacing with a 12 volt unit, second-hand being the only option. It may be possible to re-wind this motor, to work with 12 volt. Alternatively, it can be completely removed and replaced with a cabin-operated cable.

### Engine Controller

This unit controls the edic motor and safety features such as stopping the motor upon no oil pressure. If you cannot source a 12 volt edic motor, chances are you will not be able to source a 12 volt version of this either (second-hand is the only option). If you replace the edic motor with a cable, you can probably remove this controller. Before doing this, check if it effects (or is crucial for) the glow plug, starting or charging circuits.

### Glow Plugs

Will need replacing with 12 volt units, which can be sourced new for a decent price. Refer to the wiki page on [Glow Plugs][Wiki: glow plugs].

### Glow Plug Relay

The glow plugs draw over 30 amps of power, making a relay necessary if you want to keep them operated from extended periods of time (refer to the page on [Manual Glowing][Wiki: manual glow]). Either source a suitable relay, or hard-wire the glow plugs to the batteries, with a heavy-duty switch installed in the cabin. This would make the glow plug timer below not required.

### Glow Plug Timer

The timer controls the relay, and runs the glow plugs for set periods of time, depending if the engine is cold etc. To keep the glow plugs 'automatically' controlled, a 12 volt relay and timer will need to be sourced. These could possibly be adapted from other 12v diesel engines, such as the TD42 in the GQ.

### Alternator

A special alternator is required for the SD33, as the alternator has an output shaft which drives a vacuum pump. This means a generic/petrol-engine 12v alternator cannot be used, unless an alternative vacuum pump is also used (belt and electric motor driven pumps do exist on the after-market). A genuine MK alternator could be used, or it may be possible to have the 24v alternator re-wound as 12v. It may also be possible to adapt an alternator from another 12v diesel vehicle, as they most likely also have a vacuum pump (you can use GQ TD42!).

### Alternator Voltage Regulator

This would only be required if using an MK SD33 12 volt alternator.

If using an alternator from a different vehicle, these may have inbuilt or different regulation systems. This would also require a small amount of re-wiring to the existing loom, see the wiki page [Alternator with Internal Regulator Conversion][Wiki: internal reg alternator]

### Starter Motor

A 12 volt starter will need to be sourced, or it may be possible to have the 24 volt starter re-wound.

## Vehicle/Body Parts

The following vehicle/body parts will require attention during this conversion.

### Instrument Cluster

The majority of the instrument cluster within an 24 volt vehicle is already 12 volt. This includes the fuel gauge (and in-tank float), oil pressure gauge and water temp gauge.

The only part that requires attention is the voltage gauge. This will still detect 12v, however the dial is not accurate at that level (it shows the region of 16 to 32v). It can either be left as-is, or replaced with a 12 volt version. To do this, you could replace just the voltage section of the cluster (a petrol voltage gauge could also probably be inserted) or the whole instrument cluster could be replaced with a MK SD33 item (some feature a tacho!).

### Globes/Lights

Most of the globes will need replacing. These include;

*   Head lights
*   Front park lights
*   Front and side indicators
*   Tail lights
*   Rear number plate light
*   Internal roof light
*   Dash notification lights (handbrake, 4wd etc).
*   Heater dial illumination globe.

As mentioned above, the instrument cluster is already 12 volt, and the globes are too. They will not need replacing.

### Window Wipers

The 24 volt wiper motor still works when supplied with 12 volt, although it is too slow to be useful (ultra fast setting will be slower than normal speed). This is unsafe for road use and should be replaced with a 12 volt motor. There are 3 possible methods to achieving this;

*   Obtain a 12 volt wiper motor from another MQ Patrol. Units from petrol engines will also work. This is the common solution.
*   It may be possible to have the motor re-wound, to suit 12 volt.
*   A 12 volt motor from a different vehicle (or after-market) may be adaptable.

### Window Washer

The window washer pump will need to be replaced with a 12 volt pump. Similar to the wiper motor solutions, you could obtain a pump from a 12 volt MQ Patrol (including from petrol vehicles) or purchase an after-market pump. After-market pumps can be purchased with or without new washer bottles.

### Heater Blower

Needs changing. Either obtain a 12v MQ unit, have the motor re-wound, or adapt one from a different vehicle.

## Wiring Loom

All MK have a different wiring loom than MQ, as electronics such as rear window wipers were added. There are even greater differences when comparing a 24 volt SD33 loom with a 12 volt version, due to the different battery/charging circuits. There are 2 options to consider.

### Modify Existing Loom

In short, in an Australian MQ, the RH battery will need 'removing', and the LH battery joined to the body (earth). The charging system may require a few minor adjustments. Any 24 volt relays will need replacing (think head light relay etc). There is a 12 volt accessory circuit on the RH battery, the relay operating this will need removing and the circuit joined back into the main loom.

### Swap in New Loom

This would be an easier option for someone not competent with car electrics. Simply unplug all engine bay connections and pull the loom through the firewall and into the cab. Then unplug all the dash plugs and the connection to the rear wiring loom (located under the drivers seat), and the old loom can be removed from the vehicle.

To aid in installation, you can tag each connector whilst removing the loom and keep a list of the component it connects too. This is not essential, as most components have different plugs, so it is simple to work out what plug connects where.

Any extra circuits with the new loom can be 'ignored', they should not effect the functioning of the vehicle.



[File: 1]: /wiki/engine-sd33/convert-24-to-12-volts/george4wd-mq-24v-12v-retrofit.pdf

[Wiki: how to use 12v]: /wiki/engine-sd33/how-to-use-12-volt-parts-with-24-volt
[Wiki: glow plugs]: /wiki/engine-sd33/glow-plugs
[Wiki: manual glow]: /wiki/engine-sd33/manual-glowing
[Wiki: internal reg alternator]: /wiki/electrical/alternator-with-internal-regulator
