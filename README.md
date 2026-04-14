# blinky-board
Blinky Board is a starter project for Hack Club's Stasis program. I designed this LED chaser in KiCad in 3.1 hours. I created a schematic, footprint, and PCB and learned how to connect parts using wires. My PCB is shaped like a lightbulb with LEDs lighting up in its outer arc. The other components are in the middle and bottom of the lightbulb shape.

<img width="1280" height="627" alt="image" src="https://github.com/user-attachments/assets/8df717a2-bd3e-4880-a767-cbe9b23dea13" />

# Journal #1: NE555P and 4017 Connections

***April 5, 2026: 1.3 hours***

<img width="1098" height="784" alt="1775344358382-qelx4r" src="https://github.com/user-attachments/assets/90f22f22-6346-4deb-b0c1-8223c733eb3f" />

<img width="575" height="565" alt="1775344364166-rln9r1" src="https://github.com/user-attachments/assets/0a9e927b-f8f4-4f58-a5dd-ad8225676580" />

<img width="550" height="599" alt="1775344369056-k9air8" src="https://github.com/user-attachments/assets/52e6ffd5-0f13-484a-8dca-7be20f211575" />

I'm almost done with the schematic for Blinky Board. First I laid out all the components listed. I connected the header to 5V and GND. Then, I connected the NE555P to capacitors, resistors, and a potentiometer. Finally I wired the 4017 IC to all 10 of my LEDs and the NE555P.

The hardest part was figuring out how KiCad functioned since it was my first time using it. It took longer than I'd like to admit to figure out how to connect something to 5V and GND (the power symbols were in the same place as the components) and where the labels were. However, everything else was pretty easy! Skimming the rest of the article, my next steps are adding a footprint and making a PCB.

# Journal #2: Footprints and PCB

***April 13, 2026: 1.75 hours***

I had trouble figuring out how to add footprints to my schematic. However, I noticed that on the top bar of the schematic, there is a Footprint Editor button. The Blinky Board tutorial seemed to have the intention of including a screenshot of the footprints but got cut out or removed. I searched through messages in the Hack Club Slack to find the right footprints that will match with the components mailed in the Blinky Board kit.

<img width="937" height="538" alt="1776135560156-tvyzhf" src="https://github.com/user-attachments/assets/5ae77e51-57ac-4975-8e05-f1d4b69c173e" />

Then, I updated the PCB based on the schematic and wired all the components together. I used vias for multiple connections to avoid colliding different colors. I noticed that for some connections, the ratlines did not go away even after the components had a wire between them, but I realized they were still connected regardless after using the Design Rules Checker. Finally, I personalized my board by making it into the shape of a light bulb using Edge.Cuts. I added a heart and star in the middle as well on the front and back of the silkscreen.

<img width="519" height="726" alt="1776135564230-dfncuv" src="https://github.com/user-attachments/assets/3e684e20-288d-444d-a99d-392cad978e60" />
