# Resolution hardware week 6

A class that makes it easier to create and work with 7 segment displays and a short demo that uses it.

## Preview
<img width="800" height="558" alt="20260503-0118-36 4386159-ezgif com-optimize" src="https://github.com/user-attachments/assets/476084bc-d248-4134-ae0c-ab76dd84e162" />

## Docs
###  Class SevenSegment
A simple wrapper for 7 segment displays with LED matrixes.
The matrix has to have 9 rows and n*6-1 cols, where n is the amount of numbers.  
To create a new display use SevenSegment(n, pin, (color)), where n is again the amount of numbers, pin the pin it'S connected to and color is the color as a rgb tupel, which defaults to white.  
To use it use the write method, which writes a new number on the display, if the number is longer than the display it does nothing. It also accepts an optional rgb color tupel.  
To change the color use the set_color method, which takes an rgb tupel and redraws the screen in the new color.  

## Demo
https://wokwi.com/projects/462959394708344833
