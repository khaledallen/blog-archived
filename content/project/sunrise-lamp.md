---
title: "Sunrise Lamp"
date: 2021-02-16T21:44:04-07:00
draft: false
---

[Project Notebook](https://www.notion.so/misjifmaker/Sunrise-Lamp-8e684bea1ca04073b2b56d4762c15349)
[Github includes STL](https://www.github.com/khaledallen/sunrise)

## Goal

The goal of this project was to build a sunrise simulation lamp using an Arduino and a Neopixel ring. This is essentially a proof of concept, since I would probably want to use a much bigger Neopixel ring for a real lamp. This one also has a real-time clock board (RTC) that enables the device to keep time even when the Arduino is not drawing power.

It also combined elements of coding, 3D printing/mechanical design, and electrical, since I had to write the code, wire all the bits, and then design and print an enclosure for the device.

## Results

So far everything seems good. I have demonstrated that the Neopixel can simulate the gradual increase in brightness along with a reaonsable approximation of the hues of a sunrise, and I have been able to get and set the time on the clock, as well as download the time for the following day's sunrise.

- [ ] Make sure that we can trigger the sunrise with the clock settings
- [ ] Connect all the wires and install the Neopixel in its bulb

## Lessons Learned

- There is a reason that Phillips charges $200 for their sunrise lamps.
- Just because I prototyped in PLA doesn't mean that the PETG will print well, or at all.
- C++ is finicky about strings, but I think we knew that.
- I have learned a lot about handling data type conversions in C++, and digging into the libraries I'm using to leverage their provided methods and classes rather than just relying on the API.



