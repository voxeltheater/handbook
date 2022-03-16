# Dante

## Overview
Traditionally, theatres required tons of audio cables, each of which connects one device to exactly one other device. These systems were centered around one centralized patch bay, where two things can be connected together with short patch cables. If you're plugging a microphone into a wall plug in the catwalks, you need to go to the patch bay to connect that wall plug into some channel on the console.

Dante is a digital replacement for all the infrastructure between the wall plug and the console. In a Dante system, the wall plug digitizes the signal from the microphone and sends it down an ethernet cable alongside dozens of other channels of audio. Ethernet switches connect these digitizing devices, referred to as `Stage Boxes`, together to form a network. When an audio mixing console is connected to the network, it can access all the inputs and outputs on all those stage boxes via a single ethernet cable.

## Transmitters and Receivers
In Dante speak, an input into the network is called a `Transmitter` something that can accept that input is called a `Receiver`.

## Dante Controller
Dante Controller is a computer app that presents all the devices on the Dante network as a series of crosspoints. 

The primary interface of Dante Controller is a large grid of Transmitters and Recievers. Receivers are presented as rows, and Transmitters are columns. Clicking on a cell will connect the Transmitter of that Column to the Reciever of that row.

For example, input #5 on a Stage Box would show up as a Transmitter column. Channel #20 on a mixer would show up as a Receiver row. In Dante Controller, input #5 can be connected to channel #20 by clicking on the cell where that column and row intersect. This, in effect, is the digital Dante equivalent to plugging in a patch cable.

Dante Controller can be run on multiple computers simutaneously. Any changes will automatically sync between them.

## Using a computer as a Transmitter
An application called [Dante Virtual Soundcard (DVS)](audio-dvs.md) can be used to take audio from a computer and send it out over the computer's Ethernet port as Dante. Once DVS is installed, navigate to `System Preferences`>`Sound`>`Output` and select Dante Virtual Soundcard from the list.

DVS is [available from Audiante and costs $50](https://www.audinate.com/products/software/dante-virtual-soundcard), though a trial and shorter rental are available.

Within Dante Controller, the DVS Transmitter can be routed to any Dante Receiver on the network.


## Using an iPhone as a Transmitter
For connecting an iPhone or other simple aux input to the sound system, we provide a [Radial DAN-TX2 Dante Interface](audio-dan-tx2.md). It has converts the analog signal from the device into Dante. It can be connected to any ethernet port in the building, just let the TD know which one you need!

The DAN-TX2 appears in Dante Controller. We prefer to leave it routed to DS100/61-62, which ensures it works in all our spaces.
