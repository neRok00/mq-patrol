+++
title = "EDIS Electronic Ignition How-To"
date = "2016-08-01T01:01:01+08:00"
tags = ["Engine - P40"]
+++

All credit to David_S for creating this how-to in the following thread: [http://www.patrol4x4.com/forum/nissan-patrol-mq-mk-12/fitting-edis-electronic-ignition-p40-l28-engine-38169/](http://www.patrol4x4.com/forum/nissan-patrol-mq-mk-12/fitting-edis-electronic-ignition-p40-l28-engine-38169/)

You should also read this page in conjunction with [Megasquirt How-To][Wiki: megasquirt] and [EFI Conversion][Wiki: efi convert] wiki pages.


## Guide

Recently I completed my P40 fuel injection project by doing away with the distributor entirely (well not quite entirely as I have left the old dizzy in place to plug the hole!) and fitting a Ford EDIS (Electronic Distributorless Ignition System) such as can be found on a Falcon EF, though I got my parts from a firm in the UK.

The result has been impressive. The engine is much much smoother and pulls better at the higher revs even though I have not yet tuned the advance table, just basing the advance on Nissan specs for the distributor vacuum and rpm (centrifugal) advance. And it is waterproof - I tested it in a bonnet-deep swift water river crossing over the weekend and it did not miss a beat.

The system is quite simple. A timing signal from a trigger wheel/VR sensor mounted on the crankshaft goes to an EDIS module, which in turn sends the data to a controller which also receives an engine MAP (manifold absolute pressure) reading. The controller looks up the advance from a MAP/RPM table and sends the info back to the EDIS module which then fires the appropriate coils in a coilpack. It is a 'waste spark' system which fires pairs of plugs simultaneously on both the compression and exhaust strokes (wasting the exhaust stroke spark) so only 3 coils are required. I used the Megasquirt ECU as the controller as it was already controlling my fuel injection and was easy to set up for EDIS, just requiring a couple of jumpers to be soldered in place. You can use other controllers such as megajolt etc but I have not researched these.

 Info | Image |
------|:-----:|
Here is a diagram of the system. | [![][Image: 1]][Image: 1]
The trigger wheel has 36-1 teeth i.e. has one tooth missing. The changing magnetic field is picked up by a sensor with the 'missing'' tooth giving the position of the crankshaft. I mounted the trigger wheel on the back of the crankshaft pulley where it sits quite neatly. | [![][Image: 2]][Image: 2]
Or from the rear... | [![][Image: 3]][Image: 3]
And these are the components... | [![][Image: 4]][Image: 4]
And the completed installation in my LHD truck. | [![][Image: 5]][Image: 5]

Total cost was about $150 (late 2009) excluding the Megasquirt ecu but would be cheaper if you could track down a donor car.

This installation was on a P40 engine but there is no reason why it could not fit the L28. There is a lot more information on the Megasquirt site if you are interested.

## Questions and Answers

How water resistent is the EDIS module and relay board, would the EDIS module be better behind the flywall?
: EDIS module is a sealed unit with waterproof connector so no need to mount behind flywall. Sensor unit/trigger wheel is unaffected by water. I have tested the setup in very deep water (over bonnet) and it did not miss a beat even though trigger and sensor were under water. But I have the module mounted as high as possible.<br>Relay board is mounted in an alloy box ex Dick Smith and is pretty well sealed with mastic. There is a vent pipe leading back into the cockpit to prevent pressure buildup due to sudden temperature changes. Putting the board in the cockpit would really defeat the object of the board which is to act as a collector point for all sensor cables and a power distribution centre with just a single pigtail passing through the firewall to the ECU.

[Image: 1]: /wiki/engine-p40/edis-electronic-ignition-how-to/edis-system.jpg
[Image: 2]: /wiki/engine-p40/edis-electronic-ignition-how-to/edis-trigger-front.jpg
[Image: 3]: /wiki/engine-p40/edis-electronic-ignition-how-to/edis-trigger-rear.jpg
[Image: 4]: /wiki/engine-p40/edis-electronic-ignition-how-to/edis-components.jpg
[Image: 5]: /wiki/engine-p40/edis-electronic-ignition-how-to/edis-installation.jpg

[Wiki: megasquirt]: /wiki/engine-p40/megasquirt-how-to
[Wiki: efi convert]: /wiki/engine-p40/efi-conversion
