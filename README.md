# pixelate
Code to pixalate an image, also returning two collections with information like each pixel position and potential lego brick 1x1 design ID (please i know this doesn't make any sense just read the README im sorry) 

_I haven't started this but i will eventually. all images created in microsoft paint >:)_

[//]: # (what)

What is this?
-------------

<table>
  <tr>
    <td>Prompt</td>
    <td>Before</td>
    <td>After</td>
  </tr>
  <tr>
    <td><img height="200" alt="Pixelate Prompt" src="https://github.com/bigoa-gach/useless_images/blob/main/pixelate_prompt_ui_design.png"></td>
    <td><img height="200" alt="Unpixelated" src="https://github.com/bigoa-gach/useless_images/blob/main/blonde.jpeg"></td>
    <td><img height="200" alt="Pixelated" src="https://github.com/bigoa-gach/useless_images/blob/main/blonde_pixel.png"></td>
  </tr>
</table>

As shown above, the idea is to take an image file & scale value, input it into this bad boy, and have the program return a simplified, pixelated version of the inputed image file, as well as a dictionary that contains the following information about each pixel:
- pixel position
- hexadecimal colour (irrelavent, i just like looking at the hex)
- "colour group" the pixel will fall under (i.e. `#ffffff` and `#f0f0f0` would both fall under "white")
- z for the "lego brick 1x1 Design ID z/3005"

The collection above is actually unnecessary lmaooo, it's just imformation i like to look at (i think i might be neurodivergent, irrelavent mb). The program will also return a dictionary containing the following info:
- key: z for the "lego brick 1x1 Design ID z/3005"
- value: list for each block:
  - the number of brick of this particular colour
  - the cost of this lego brick
  - the total cost of the sum of these bricks

This dictionary will also include plates/baseplates for the base layer of the LEGO art.

And also return the pixel dimensions, total sum of bricks as well as total cost of all bricks.

All this information will be displayed all pretty on a UI and availiable to download as a file.

<img width="950" alt="Pixelate Result" src="https://github.com/bigoa-gach/useless_images/blob/main/pixelate_result_ui_design.png">

The PDF file will contain all of the information above, as well as an additional pixelated image with a number for each pixel that correlates with a lego block, as shown below. Many pixels will have the same number according to their colour group, even if the colours are slightly different, since there isn't a very wide range of colourful 1x1 lego bricks.

[insert image that i havent drawn yet (ms paint again)]

[//]: # (end what)


[//]: # (why)

Why did you make this?
----------------------
I'm doing this because i want to make lego art of my favourite music albums (like "Blonde" above) (my motives are simple, i'm a simple person leave me alone lmao)

Could I have just searched up a website to pixalate my images for me? Yes i could have.
Does making this program make my job harder? Yes it does. This project is literally a waste of everyone's time.

But what other program/website gives and a pixalated image AND each lego brick you would need to make it into physical art?

You are all welcome >:)

[//]: # (end why)

>prolly gonna use C# windows forms because i like the UI :)

## Licenses
????????

----
I make no money from this, im just bored but im not smart enough to create something that positively contributes to my job and society as a whole. I code cuz i like to see colours and games lmaooo.
I'm well aware that this all could have been worded better. English is indeed my first and only speaking langauge, i'm just stupid >:)
