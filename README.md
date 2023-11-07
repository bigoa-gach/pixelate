# pixelate
Code to pixalate an image, also returning a dictionary of each pixel position and potential lego brick 1x1 design ID (please i know this doesn't make any sense just read bear with me lol).

I haven't started this but i will eventually.

[//]: # (what)

What is this?
-------------
The idea is to take an image file & scale value, input it into this bad boy, and have the program return a simplified, pixelated version of the inputed image file, as well as a dictionary that contains the following information about each pixel:
- pixel position
- hexadecimal colour (irrelavent, i just like looking at the hex)
- "colour group" the pixel will fall under (i.e. #ffffff and #f0f0f0 would both fall under "white")
- z for the "lego brick 1x1 Design ID z/3005"
  
The list above is actually unnecessary lmaooo, it's just imformation i like to look at (i think i might be neurodivergent, irrelavent mb). The program will also return a dictionary containing the following info:
- key:   z for the "lego brick 1x1 Design ID z/3005"
- value: list for each block:
  - the number of brick of this particular colour
  - the cost of this lego brick
  - the total cost of the sum of these bricks

Also return the total sum of bricks as well as total cost of all bricks.

All this information will be displayed all pretty on a UI and availiable to download as a file (as shown below [when i eventually learn how to insert images in this README file).
  
[//]: # (end what)


[//]: # (why)

Why did you make this?
----------------------
I'm doing this because i want to make lego art of my favourite music albums (my motives are simple, i'm a simple person leave me alone lmao)

Could I have just searched up a website to pixalate my images for me? Yes i could have.
Does making this program make my job harder? Yes it does. This project is literally a waste of everyone's time.

But what other program/website gives and a pixalated image AND each lego brick you would need to make it into physical art?

You are all welcome >:)

[//]: # (end why)

## Licenses
????????

----
I make no money from this, im just bored but im not smart enough to create something that positively contributes to my job and society as a whole. I code cuz i like to see colours and games lmaooo.
