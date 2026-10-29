555 Mountain LED Chaser

Welcome to my Hack Club Forge project!

I wanted to build something a bit more interesting than a basic blinking LED—a circuit where light smoothly runs through a sequence. That’s how this LED chaser came to life! It’s powered by a classic NE555 timer chip to generate the clock signal and a 4017 counter chip that lights up each LED one after another.

Why a mountain shape?

I really didn't want to make just another standard rectangular board. I love nature and spend a lot of time outdoors, so I decided to draw the PCB outline in the shape of a mountain range. The LEDs are placed along the peaks, so when they light up in sequence, it looks like a trail of light moving across the mountains.

How it works

Clock Generator: The NE555 timer is wired in astable mode to create a pulse signal. You can adjust the speed of the chasing light using the potentiometer.

Decade Counter: The CD4017 chip takes those clock pulses and turns on the output pins one by one, lighting up each LED.

Power: The whole board runs on 5V, supplied through a simple 2-pin header (I'm using a modified USB cable for this).

The biggest challenges

Designing this board came with a few tricky parts:

Routing inside a mountain shape: Since the board isn't a simple square, routing all the copper traces without running out of room felt like a giant puzzle.

Staying within the board edge: I had to make sure no traces or components got too close to the edge cutouts of the mountain peaks to avoid any shorts or manufacturing issues.

It took quite a bit of patience to get all the tracks placed cleanly, but I'm really happy with how the final layout turned out!

Bill of Materials (BOM)

The complete list of components, prices, and purchasing links can be found in the BOM.csv file in this repository.

Gallery & PCB Preview

