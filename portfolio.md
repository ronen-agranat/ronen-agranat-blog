---
layout: page
title: Portfolio
permalink: /portfolio/
---

A list and short description of some of my own projects that I have worked on over the years.

## UI for flatbed industrial knitting machines

*2002*

I developed the GUI front-end for converted an flatbed industrial knitting machines, which were previously programmed using an electro-mechanical punch-card mechanism, into a fully digtal, computerised system.
It was created with Visual Basic 6 and used a custom communications protocol that we developed.
It communicates via RS-232 to the hardware interface.
It included the ability save and export designs.
A major improvement over the previous system is that the 'translation' step of transforming from the desired instructions into an intermediate language which is the transcribed onto punch cards was no longer needed, because it was automatically done by the user interface software.
This project was contracted by Inpulse Electronic Controls CC and was done for the Silvaknit textiles factory, and so was a paid project.
The system is still in use at the Silvaknit.

## Flying model simulator (FMS) radio handset adapter

*2002*

I manufactured electronic adapter interfaces for connecting most model aeroplane radio controller sets to a PC via the serial port.
This was in order to use a free model aeroplane flight simulator called Flying Model Simulator (FMS).
This was frequently used for training and practice by model aeroplane enthusiasts.
The kits were produced according to a provided circuit diagram and proprietary circuit board layout.
It would typically take me about 30 minutes to an hour to assemble one (soldering).
These devices were sold at the Cape Radio Flyers club, and so this was a paid project.
Each device also included an installation disk with instructions and a copy of the free flight simulator.

## UpPhoto

*July 2007 -- June 2008*

I created software for uploading images and photo's for display on custom websites.
The project had two major components:
a Java- and Swing-based client-side user interface which was used to manage and upload the images,
and the server-side component which was written in PHP and JavaScript which rendered the images on the custom website,
presenting them as a photo album with navigation.
MySQL was used as the database.
This project was used by two customers and so was paid.


## Cloudscape

*July 2008 -- November 2008*

A partner and I developed a 3D ‘cloud painting’ program with a peer.
It allows the user to artistically create sky textures, for use, for example, in 3D video games.
The program presents a 3D environment in which the user can generate sky-like textures and use a variety of manipulation tools to draw or erase cloud-like patterns.
It also enables the placing and positioning of 2D sprites, for example, to represent the moon or sun, or objects in the sky.
It presents a number of options, themes and colour schemes for the generation of the sky texture.
It then allows the finished texture to be exported as a 2D image file for import into the video game as a texture.
Developed with C++ and OpenGL for Linux.
Also features a simple user interface, which was created with GLUI, a simple user-interface framework for OpenGL applications.
Perlin noise is used to generate natural-looking ‘plasma’ which is tweaked to look like clouds and merged into a sky texture.
That image is projected onto a ‘sky dome’ hemisphere in 3D.
The camera sits near the middle of the hemisphere.
This was our annual project for second-year computer science (C++).

## LastCritic: iGoogle music review app

*June 2009*

I designed and implemented an app on Google's "iGoogle" platform.
This was a national contest hosted by Google.
The app that I created was a mash-up of Metacritic and Last.fm:
the latest releases on Metacritic would be displayed, along with cover art and ratings, and listener numbers from Last.fm.
This provided a unique view onto the new releases, making it easy to see, for example, critically-acclaimed releases with relatively few listeners;
similarly, it was easy to see widely popular releases that did not receive critical acclaim.
As winner of the South African Google gadget competition, I was invited to work alongside the iGoogle team at the Google offices in Zürich, Switzerland, for four days.
The gadget locates and plays relevant YouTube music videos, and has a ratings system which is built with open social and Google AppEngine.
It was created using JavaScript, the iGoogle APIs, the YouTube and OpenSocial APIs, and with Python running on Google App Engine, for the server-side component that managed user reviews.
iGoogle is now defunct.

## MIDI audio device

*July 2009 -- November 2009*

Created a simple music synthesiser using UCT’s GT16 kit.
The device connects to a MIDI port of a PC to receive musical note information, which it uses to generate the corresponding sounds.
The device plays one note at a time and is capable of ‘sliding’ from note to note at various speeds.
It has four different tones.
This was a third-year university project.

## South African Sign Language Tutor

*November 2009*

South African Sign Language Tutor was a computer-aided education application for teaching South African Sign Language with the aid of a webcam. It was developed using C++ and Qt4, and was cross-platform (Windows and Linux).
It supported pluggable lessons, video playback of lessons, recording of the user's gestures and simultaneous playback with the original gesture, different quiz modes and gesture recognition in order to navigate through the lesson structure.
Subversion and Google code were used for source control.
I led a team of 3 second-year computer science students studying C++ at the University of Cape Town to develop their chosen annual project "Sign Language Tutor" into a real-world application.
These 3 students had created the top two projects during the year.
I was their C++ tutor.
The goal was to merge the best conceptual ideas from both into a real-world applciation that could be used.
The project had to be completed in three weeks.
The project was for the Sign Language Education and Development organisation of South Africa (SLED).
The project was ultimately completed and presented to stakeholders at the organisation.
This was a paid project.
The project was available as open source.

## Eighty20 fact-of-the-day Facebook app

*March 2010*

Eighty20 is a South African consumer-knowledge database company.
They released a daily consumer fact via their website.
I designed and implemented a Facebook app that displayed the fact-of-the-day on Facebook.
The app was written in PHP and used the Facebook API.
My business partner and I proposed this project to Eighty20. This was a paid project.
Facebook no longer offers support for such apps.

## VAD: VHDL audio device

*2010*

My undegraduate thesis describes how to create a general-purpose audio device using VHDL and a Xilinx FPGA.
It's a great introduction to VHDL and the Xilinx tool chain.
Features include multi-channel audio input/output, MIDI file synthesis and audio recording and playback.
This project is an ideal audio prototyping framework for the Digilent Nexys2 FPGA evaluation board.

Abstract: This fourth-year electrical and computer engineering thesis project details the design and implementation of a general purpose audio device on a Digilent Nexys2 evaluation board, supporting 44.1 KHz 12-bit audio monitoring and playback with 53 seconds of recording time.
The emphasis of the project is on digital logic, VHDL and FPGA’s.
Five track MIDI files can be played, with two polyphonic tracks and a drum track.
The musical notes are synthesised by waveform generators implemented in the hardware domain.
These oscillators are controlled by a software application running on the Microblaze soft core.
The device makes use of external ADC and DAC chips to interact with analogue audio signals.
The project is implemented using Xilinx Embedded Development Kit (EDK) 12.2.
The functional and performance characteristics of the device are investigated with a series of experiments which verify the prototype’s functionality.

