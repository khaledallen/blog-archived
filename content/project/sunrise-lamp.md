---
title: "Sunrise Lamp"
date: 2021-02-16T21:44:04-07:00
draft: false
---

[Project Notebook](https://www.notion.so/misjifmaker/Sunrise-Lamp-8e684bea1ca04073b2b56d4762c15349)
[Github, includes STL](https://www.github.com/khaledallen/sunrise)

## Final Demo

<iframe width="560" height="315" src="https://www.youtube.com/embed/Pjb0wGINeB0" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Goal

The goal of this project was to build a sunrise simulation lamp using an Arduino and a Neopixel ring. This is essentially a proof of concept, since I would probably want to use a much bigger Neopixel ring for a real lamp. This one also has a real-time clock board (RTC) that enables the device to keep time even when the Arduino is not drawing power.

It also combined elements of coding, 3D printing/mechanical design, and electrical, since I had to write the code, wire all the bits, and then design and print an enclosure for the device.

## Results

So far everything seems good. I have demonstrated that the Neopixel can simulate the gradual increase in brightness along with a reaonsable approximation of the hues of a sunrise, and I have been able to get and set the time on the clock, as well as download the time for the following day's sunrise.

With everything connected, the lamp turns on at the appropriate time and runs through the sequence as expected. You can set how long you want the sequence to take, and it will automatically adjust the length of each phase. You can also add more steps and colors, and set the max brightness, which is scaled down for the start of the sunrise.

Overall, I'm really happy with the entire setup. It is easy to use and much cleaner than previous IoT projects.

## Lessons Learned

- There is a reason that Phillips charges $200 for their sunrise lamps.
- Just because I prototyped in PLA doesn't mean that the PETG will print well, or at all.
- C++ is finicky about strings, but I think we knew that.
- I have learned a lot about handling data type conversions in C++, and digging into the libraries I'm using to leverage their provided methods and classes rather than just relying on the API.
- Always use solid core wires if breadboards are involved.

## Review

I got it working to the extent that I wanted. Right now, it's still hooked up to a breadboard because my MKR1000 is the model with embedded headers, which I can't remove. So at some point, I will need to think about getting a headless board so I can build an enclosure for the clock and the board and get everything into a small package. But at the moment, the proof of concept is complete and I accomplished what I set out to do, which was build a project that incorporated 3D printing into an IoT project.



