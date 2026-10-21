# 555-chaser

My Mountain LED Chaser
Welcome to my Hack Club Forge project! I’ve wanted to build a cool circuit for a while—something that doesn’t just blink, but sends light smoothly running through a sequence. The result is this LED chaser board, powered by a classic timer chip for the clock signal and a counter chip that lights up each LED one after another.

Why this specific shape?
I consciously chose not to go with a boring, rectangular standard PCB shape. Since I absolutely love nature and especially mountains, I decided to design the board's outline like a mountain range! The LEDs are spread across the "peaks" so that the chasing light feels like a sparkling path across the mountains, combining my hobby for electronics with my love for the outdoors.

The biggest challenges (and how I solved them)
Getting the board to work and look right came with a few hurdles:

Routing inside a mountain shape: Because the PCB isn't a simple rectangle, squeezing all the traces onto the board was quite a puzzle.

Staying within the bounds: I couldn't let any traces or components cross over the edges of the custom mountain outline. It took a lot of patience to route all the tracks cleanly around the corners and peaks without causing short circuits or running out of space.

In the end, everything came together, and I'm super proud of how this mountain PCB turned out!
#translated with google-translator#

# Bill of Materials (BOM) - Mountain LED Chaser

Item | Name / Component | Quantity | Where to Buy | Part Search Term / Notes | Unit Price (EUR) | Total Price (EUR) | Link
--- | --- | --- | --- | --- | --- | ---
1 | NE555 Precision Timer IC (DIP-8) | 1 | Reichelt Elektronik | NE 555 DIP | 0.25 | 0.25 | https://www.reichelt.de/de/de/shop/produkt/praezisionstimer-ic_typ_555_4_5_16_v_dip-8-13396?search=ne%2520555%2520dip&
2 | HEF4017 / CD4017 Decade Counter (DIP-16) | 1 | Reichelt Elektronik | HEF 4017BP | 0.35 | 0.35 | https://www.reichelt.de/de/de/shop/produkt/counter_5-stage_4_5_15_5_v_so-16-219252#closemodal
3 | 3mm LEDs (Red / Standard) | 10 | Reichelt Elektronik | LED 3MM RT | 0.10 | 1.00 | https://www.reichelt.de/de/de/shop/produkt/led_3_mm_bedrahtet_rot_191_mcd_50_-10228 | https://www.reichelt.de/de/de/shop/produkt/led_3_mm_bedrahtet_gelb_210_mcd_53_-10226 | https://www.reichelt.de/de/de/shop/produkt/led_3_mm_bedrahtet_blau_1200_mcd_90_-61104
4 | Resistors (330 Ohm & 10k Ohm THT) | 2 | Reichelt Elektronik | 330 Ohm/ 1kOhm Resistors | 0.07 | 0.14 | https://www.reichelt.de/de/de/shop/produkt/widerstand_metallschicht_1_00_kohm_0207_0_6_w_1_-11403 | https://www.reichelt.de/de/de/shop/produkt/widerstand_metallschicht_330_ohm_0207_0_6_w_1_-11733
5 | Potentiometer / Trimmer (100k Ohm) | 1 | Reichelt Elektronik | RK09K113 | 0.99 | 0.99 | https://www.reichelt.de/de/de/shop/produkt/drehpotentiometer_mono_100_kohm_linear_6_mm-73818
6 | Capacitors (10uF Elko & 100nF Ceramic) | 2 | Reichelt Elektronik | 10uF/100nF Capacitors | 0.26/0.10 | 0.36 | https://www.reichelt.de/de/de/shop/produkt/elko_radial_10_f_400_v_105_10x16_mm_rm_5_0_mm-124698 | https://www.reichelt.de/de/de/shop/produkt/vielschicht-kerko_100_nf_50_v_x7r_10_rm_2_5_ammo-22853
7 | IC Sockets (1x 8-pin, 1x 16-pin) | 2 | Reichelt Elektronik | GS 8 & GS 16 | 0.04/0.07 | 0.11 | https://www.reichelt.de/de/de/shop/produkt/ic-sockel_8-polig_doppelter_federkontakt-8230 | https://www.reichelt.de/de/de/shop/produkt/ic-sockel_16-polig_doppelter_federkontakt-8208
8 | Pin Header (2-pin 2.54mm Power Input) | 1 | Reichelt Elektronik | SL 1X40G 2,54 | 0.30 | 0.30 | https://www.reichelt.de/de/de/shop/produkt/40pol_stiftleiste_gerade_rm_2_54-19506
9 |USB 2.0 cable, A plug to Micro B plug, 1.0 m | 1 | Reichelt | USB 2.0 cable, A plug to Micro B plug, 1.0 m | 1.40 | 1.40 | https://www.reichelt.de/de/de/shop/produkt/usb_2_0_kabel_a_stecker_auf_micro_b_stecker_1_0_m-202263 | I WILL CUT OFF THE MICRO B PORTr
10 | Custom Mountain PCBs (5 pcs minimum) | 5 | JLCPCB | Upload Gerber on jlcpcb.com | 1.25 | 4
- | Shipping Fee (Reichelt Elektronik) | 1 | Reichelt Elektronik | Standard Shipping (Germany) | 5.95 | 5.95
- | Shipping Fee (JLCPCB to Germany) | 1 | JLCPCB | Global Mail / Standard Shipping | 6.64 | 6.64
TOTAL | Complete Project Cost (incl. all shipping) | - | - | - | - | 21,49€ (+ 3€) == $24.12 - $27,48

<img width="801" height="520" alt="image" src="https://github.com/user-attachments/assets/ee8087f5-dcf6-4cee-bf85-efd9a91f6322" />
<img width="1007" height="677" alt="image" src="https://github.com/user-attachments/assets/c8fd978e-6797-4306-a95a-30962cf80cb7" />
<img width="890" height="191" alt="image" src="https://github.com/user-attachments/assets/d50befb0-a2d8-4de9-9d62-25eb1aa7393c" />
<img width="813" height="459" alt="Screenshot 2026-10-16 160448" src="https://github.com/user-attachments/assets/5a2f0a5d-0e3b-4120-b58e-1962952dda4c" />



