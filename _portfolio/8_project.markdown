---
layout: page
title: Mini Braille Telegraph
description: ECE 4180 Final Project, Georgia Tech
img: /project_pics/printer.JPG
---

The Bluetooth controlled Mini Braille Telegraph was designed as a final project submission for
ECE 4180 Embedded Systems Design course with Dr. Hamblen. Along with 3 teammates, I designed a printer that receives
characters/strings in English and prints out the corresponding Braille characters on a Braille tape.

The Adafruit BLE Bluetooth app is used to send characters that are displayed on the uLCD and read out loud through a speaker
using an EMIC2 text-to-audio chip. A linear actuator is used to position the stylus that is used to create the
embossed dots for Braille characters. Once the stylus is correctly oriented, a solenoid is used to push the Braille tape up
so as to create an indentation. Finally, a stepper motor is used to unwind the tape to facilitate the printing of the next
character.

<div class="img_row">
	<img class="col half" src="{{ site.baseurl }}/project_pics/printer_main.JPG" alt="" title="Mini-Braille Printer"/>
	<img class="col half" src="{{ site.baseurl }}/project_pics/printer_elec.JPG" alt="" title="Printer Electronics"/>
</div>
<div class="col three caption">
	Mini-Braille Printer and all the internal electronics.
</div>

Here is a <a href="https://www.youtube.com/watch?v=2WF3GfKMxMs" target="blank"> video </a>
showing the working printer. This <a href="https://os.mbed.com/users/XBraves/notebook/mini-braille-telegraph/" target="blank"> tutorial</a>
provides a detailed description of the project.
