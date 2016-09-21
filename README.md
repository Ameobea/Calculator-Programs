# Graphing Calculator Applications
Through the end of grade school and all through high school (~2010-2014), I worked on creating various applications for my TI-84 graphing calculator.  This was one of my very first forays into programming and I attribute a lot of my current interest to the many hours spent during class programming my calculator.  I've uploaded what programs I wrote and still had access to here for archival purposes.

The language included on the calculators is called TI-BASIC and it has a simple yet effective syntax that allows for programatic access to all the calculator's functions including manually drawing pixels to the screen.  I created all of these programs directly on the calculator, mostly during classtime.

## BIRDCODE.8Xp
This is a flappy bird game that, when combined with a driver application (not included) and the AXE parser functioned as a sort of flappy bird clone where the player could click a key to propel the "bird" up in the air to avoid obstacles.

## CLASTRAK.8Xp
This application used the calculator's built-in chronograph to display various statistics about the schoolday for my high school including what percent of the day was left, what period it was and how long until it ended, and even took into account the altered Thursday schedule.

## DRAWPLUS.8Xp
This was a simple drawing application that allowed the user to create pixel images with the aid of a togglable pen of multiple sizes, an eraser, and some utilities like inverting all pixels on the screen.

## FIRST.8Xp
This is a sort of utility program called by the OGAME program.  It set some default values and reset the progress in the game as well as archiving a list that took up valuable bytes of RAM while not in use.

## GUESSGAM.8Xp
This is a simple higher-lower guessing game for numbers from 1 to 1000.  I got so good at writing this program that I could enter it in by memory into peoples' calculators in a few minutes.  I also came up with some other programs that I could enter onto others' calculators in only a few seconds, like those that printed a string to the screen forever and wouldn't quit easily.

## MATHUTIL.8Xp
This was a sort of math utility library that held a ton of useful programs to do all kinds of stuff from my math classes.  I extended to it as I needed new things for my classes and it eventually grew so long that it took almost a minute to scroll down to the end using the calculator's build-in IDE.

I gave copies out to some friends, but I was very worried that they would give it to others in turn and I'd get in trouble for helping them cheat.  To counter this, I added in some DRM by checking if a certain element of a certain array used to store the hiscores of a popular Snake game that most of my classmates had was set to the proper value.  I then obfuscated the code that did this checking as best I could, jumping around to labels at the beginning and end of the program and evaluating crazy strings like this: `Lbl ZX
If |LHS(|LHS(2)/4)!=thetatheta(|LHS(2)/2)(2)`

## MEMMATCH.8Xp
Pretty simple program that created a grid of "cards" with various values with the goal being to select two cards with the same symbol (the cards were hidden and could only be revealed by selecting them).

## MINECRFT.8Xp
A neat little 2D terrain generator that created land based on some user-defined-parameters, added trees with a defined rarity, and dug out a cave through the middle of the level.  Then, the user could navigate around with the arrow keys and build/dig the pixels to build and mine.  There was an extended version with a underground level including caves, but I don't think that's the one I've included here.

I actually made a Youtube video showing this off: https://www.youtube.com/watch?v=M-B6Qy_xBrk

## MINESWPR.8Xp
This was the first major program I ever made for the graphing calculator and it took me many months to get right.  I remember carrying my calculator around with me in the car, to my grandparents' house, trying to debug one issue or another.  I at several points resorted to writing out my `IF THEN`/`END` structure on paper to help figure out where I had an unclosed statement; imagine how hard it was to figure that out with a screen that showed less than 10 lines of code max, had no indentation or comments built in, and where all variable names consisted of a single letter!

I got pretty far in creating an alternate version in which the calculator plays the game itself, revealing squares in the best way it could to win the game.  However, I lost that when I dropped the calculator, causing the batteries to fall out and my RAM to reset.  That was my first experience with the importance of making backup; I never failed to make groups and archives of my programs after that!

## OGAME.8Xp
This was an attempt at a clone of [OGame](http://ogame.us/), a strategy game set in space where you have to wait long periods of time while your planets gather resources and your fleets fly around.  I used the calculator's internal clock to determine how long it had been since the actions were initiated.

However, this game wasn't very well suited to the Graphing calculator platform and I ran into a lot of issues with lack of memory and general limitations of the platform so gave up on making it any more extensive.

## SAND.8Xp
A falling particle simulator where the dropping particles stacked up into mountains and collided with each other.  The program worked with arbitrary images and I had a version at one point where the user could draw an image and then watch it get covered with sand.

## SCRNSAVR.8Xp
A neat little collection of cool visualizations that didn't do much but look cool.  If I remember correctly, there was one that built series of concentric circles and then alternated between them quickly, imitating the effect of a swirling hypnotization spiral.  I used amazing techniques like using `sin(sin(sin(sin(5` as a delay mechanism.  Some other visualizations included watching numbers increment with an exponential function, starting off increasing thousandths at a time until they increase by millions each tick before finally overflowing and a program that turned on a pixel in a random square until the entire screen was filled.

## TTTCLEAN.8Xp
A utility function that cleaned out some variables, reset the graph to default settings (other kids had a lot of troulble when they played a game and suddenly couldn't adjust see axis lines on their graphs).

## ZBOUNCE
A simluation of a ball bouncing around an image.  When it collided with a wall, it would bounce off at a 90 degree angle and continue bouncing.  Since it was only possible to draw images with straight lines since everything was made out of pixels, simulation was pretty easy :)

I remember drawing images like a maze and watching as the ball bounced closer and closer to the exit only to get stuck in an infinite bounce loop between 5 pixels.

# Conclusion
Well that about sums up everything I have left from my early days programming graphing calculators.  My TI-84 (which still lives in the desk I'm typing this on now) gave me a LOT of enjoyment and helped me gain the fundamental programming ideas I still use today.  I'd recommend any beginner programmer to check out TI-BASIC and try creating their own graphing calculator programs.
