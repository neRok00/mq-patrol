+++
title = "How to use 12 volt parts with 24 volt vehicle"
date = "2016-08-01"
tags = ["Engine - SD33", "Electrical"]
+++

All MQ's with the SD33 engine were released as 24 volt. This poses many problems, as almost all after-market electronics for vehicles are 12 volt. This page discusses how to safely run 12 volt parts on a 24 volt vehicle.

When the MK was released, Nissan changed the SD33 to 12 volt. It is possible to convert a 24 volt vehicle to 12 volt. Please refer to [this wiki page][Wiki: convert 24 to 12].

## The MQ 24 Volt Circuit

The MQ uses 2 standard 12 volt batteries wired in series to create 24 volt. On an Australian MQ, the following connections exist;

*   The negative of the RH (low) battery is the earth for the vehicle, this connects to the chassis and engine etc.

*   The positive of the RH battery is connected to the negative of the LH side battery, to create the series connection.

*   The positive of the LH (high) battery supplies 24 volt power to the vehicle.

It is possible to 'tap' 12 volt power from the positive terminal of the 'low' (RH) side battery. The standard 24 volt MQ wiring loom uses this connection to power the radio, cigarette lighter and dash.

## Problems With The Standard System

Taking 12 volt from the low battery, as described above, causes the low battery to drain faster than the high battery. This is because it is supplying power to both the 12 and 24 circuits.

This shows a flaw with the charging system, as the batteries require different charge rates. However, the alternator only 'sees' 1 battery (ie the 2*12 volt batteries appear as 1*24 volt) and supplies charge to suit. This will cause the low battery to remain under-charged and eventually become flat.

The factory 12 volt circuit runs very few components, which draw very little power. Their effect on the batteries charge is minimal and acceptable. However, if extra 12 volt equipment (stereos, spot lights etc) are run from this circuit, this will become a very real problem.

## Solutions

Apart from converting the entire vehicle to 12 volt (refer link at start), there are 3 viable solutions. They are shown in increasing order of power supply (ie small to large supply). The cost of a solution will also increase as your power requirements increase.

### 24 to 12 volt Converter

These units have 24 volt inputs, so they draw power from both batteries equally. They then convert the power down and output 12 volts. Any 12 volt parts are then run directly from the converter. They require a 'closed loop' circuit, which means the earth/negative must return from the part to the converter through a wire (similar to wiring a speaker).

There are many options available on the after-market. Dick Smith sell a few smaller units and Red-Arc make many sizes (including rather large ones).

This solution is best suited for running only a few small parts, such as a CD player and a CB radio. Running too many or too large appliances will often cause a safety switch to trip within these units.

These units are best run from a switch-able circuit, such as the accessory circuit. If they are run directly from the batteries and left on, they will continue to drain power even when the car is not in use, resulting in 2 flat batteries.

One down-side to consider, turning the unit off will cause parts such as CD players to loose their memory. A workaround is to hook the 'memory' wire of the unit directly to the low battery 'tap' circuit. Whilst this will technically cause the batteries to become unevenly charged, it will only be by a minute amount.

### Charge Equaliser

These units address the problem of the low battery being undercharged when tapping power from it. Similar to the converter, they take 24 volt power and convert it down to 12 volt. This power is then used to charge the low battery. They are in essence an alternator for the low battery only.

Charge equalisers are available from companies such as Red-Arc.

Higher current draw parts can be used with this system, compared to the converter system. Unlike the converter, any 12 volt parts do not need to have 'closed-loop' wiring, the earth can return through the chassis. This allows simpler wiring circuit(s).

### New 12 volt Circuit

This solution will provide the most power for your 12 volt parts, but is the most complex. It requires a second alternator (12 volt) to be added to the motor and a third battery added to the vehicle.

This system has to be wired in a 'closed loop', which means that all 12 volt earth/negatives need to run through wires back to the battery. You cannot earth to the body/chassis, as this is part of the 24v system. If an ignition or accessory circuit is required for the new 12 volt system, this can be achieved through the use of relays that are connected to the relevant 24 volt circuit.

The third battery would also provide additional benefits;

*   Fridges etc could drain the 12v battery flat and would not effect the 24v system, so you could still start the vehicle.

*   The third battery could be temporarily hooked up to a winch to provide additional power.

*   If damage occurred to one of the 24v batteries, or even to a friends vehicle, you have a 'spare' available.


[Wiki: convert 24 to 12]: /wiki/engine-sd33/convert-24-to-12-volts
