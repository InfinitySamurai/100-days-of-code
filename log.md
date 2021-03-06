# 100 Days Of Code - Log

### Day 1: May 31, 2017
#####

**Today's Progress**: Signed up and used https://codefights.com/

**Thoughts:** I found this to be an interesting application for giving coding puzzles in a nice and easy to use environment with tests to make sure that your solution works properly. It get the problem solving ideas rolling, but it isn't much of a real world project

**Link to work:** [Code Fights](https://codefights.com/)


### Day 2: June 1, 2017
#####

**Today's Progress**: Started work on my fidget spinner web based incremental
game

**Thoughts:** I took a while getting started with this, running into small
problem with setting the project up. I haven't used html, css and javascript
for a while (since my last attempt at making an incremental game). Things will
be slow going while I work up my knowledge again. I got a thing to spin and
speed up as you click, which is pretty cool!

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 3: June 2, 2017
#####

**Today's Progress**: I moved some of my code around. Moved things to
functions and created classes for my spinners.

**Thoughts:** This wasn't too hard for today, and hopefully it will make things
easier in the future. This took longer than it probably needed to again because
I'm relearning javascript to some extent. I'm not looking forward to tomorrow
when I have to start writing some better html so I can include some more
buttons to upgrade my spinner.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 4: June 3, 2017
#####

**Today's Progress**: I started to migrate over to using the Pixi framework for
creating my game.

**Thoughts:** As usual this was slower than I thought it would be, I have
higher expectations of how much I can achieve versus how much is actually
feasable to achieve. Pixi allows me to move away from worrying about HTML and
css so I can focus on the stuff I actually like with coding, and will allow me
to make full use WebGL with a nice wrapper.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 5: June 4, 2017
#####

**Today's Progress**: I played around with some bash scripting today to sync my dekstop computer and my laptop configurations. I now have a setup script for my configs that will remove old config files and create sylinks to my config repo folder.

**Thoughts:** I hate bash. I already knew that I didn't like bash, but spending 2 hours trying to write a fairly simple script just ruined me. I hope I never have to touch the stuff again, but I inevitably will.

**Link to work:** git@github.com:InfinitySamurai/configs


### Day 6: June 5, 2017
#####

**Today's Progress**: Moved more code around in spin-to-win to make it easier going forward. Managed to implement clicking within PixiJS

**Thoughts:** I had to ask for help in the Pixi forum for this one. I couldn't figure out why an event wasn't working for an object, but of course I had to pass the object as an argument in the event. I'm not sure if the docs were just not clear on this or if I didn't look hard enough

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 7: June 7, 2017
#####

**Today's Progress**: I missed yesterday due to unforseen circumstances. Today
I made sure that all my rotation amounts were consistent so that I don't
confuse myself in the future. 

**Thoughts:** I still think things will take less time than they do. I expected
to get this resolved in 30 minutes and it took me 2 hours. Tomorrow I believe I
can move on to more interestng things, adding numbers to display speed and
decay etc. of my spinners.

I actually did a whole lot more work on this later in the night! I added a UI
element that tracks the speed of my spinner. A bit hacky to begin with, but I
can fix it up tomorrow to take a proper variable reference. Really pleased that
I managed to code this and only run into a few bugs that needed to be
addressed.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 8: June 8, 2017
#####

**Today's Progress**: Made my UI box reference an objects variable properly.
Also limited text box number outputs to 2 decimals.

**Thoughts:** This took AGES to get working. I spent a long time trying to
setup my UI to update appropiately with numbers from an external object. I
couldn't figure out how to give the text box a reference to an objects
variable, because you can't in javascript. I explored many methods but none of
them fit until I finally ran into a simple solution of giving the UI element a
reference of the object, and the name of the variable and simply calling
object[variable].

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 8: June 9, 2017
#####

**Today's Progress**: I moved some of my objects into containers so they would
be grouped together. I added in a rectangle graphics for my progress bar that
I'm going to use with the spinner. I also added some units for my UI number
display

**Thoughts:** Things are going well, I'm glad that I've added some objects into
containers together now, because if I need to move any of my elements around I
can just move the whole container now. I'm not sure how I'm going to get my
progress bar to work just yet, but I have a fairly good idea that I can add a
new graphics object inside my existing bar that will fill up and go down as it
updates.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 9: June 11, 2017
#####

**Today's Progress**: I missed yesterday due to a full day out. Today I managed
to get my progress bar working, including text that display the value you have
out of the maximum value AND the option for that to be a percentage. I added
currency that gets added for every rotation of the spinner. This is actually
not calculated correctly at the moment

**Thoughts:** I started to feel a bit forced today working on this project, I
kind of wanted to bum around all day but I'm glad that I made myself get
something done, and I actually managed to get a few things which I'm happy
about. UX is probably a big thing that will come up soon which I have no idea
how to approach but I'm sure it will be an interesting journey. I'm also
probably going to have to redesign my UI implementation in the not too far
future.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 10: June 12, 2017
#####

**Today's Progress**: I moved more of my code around to hopefully make it more
extensible, mostly to do with UI. I also started the basis of my upgrade
buttons

**Thoughts:** I think I'm going to need to actually design a bit better how my
UI is setup, I think I said this last week. I did a bit of re-factoring today
but I think it's not in great shape still and could do with a real re-think.
I'm looking forward to getting my upgrade buttons implemented but this will
either have to be a hacky solution, or I'll have to sort out my UI
implementation first.

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 11: June 14, 2017
#####

**Today's Progress**: I added my upgrade buttons and made them work, as well as
changing the way the UI worked again. I suspect this will happen every day for
the UI. 

**Thoughts:** I failed again yesterday at doing some work on this project, I
haven't got a lot of consecutive days working but I'm still going alright at
working on stuff. THe UI needs to be constantly changed with the way that it
works so that it is more extendible, I think I've got it into a form that will
hopefully work with a bit more prodding. The upgrade buttons weren't too much
of a hassle to implement which I'm happy about, there are still issues with
creating them when there are special cases but I can work that out tomorrow.
I'm thinking I might need to start creating external files for data for the
game to extract that information, or just create special classes or something. 

**Link to work:** git@github.com:InfinitySamurai/spin-to-win

### Day 12: June 16, 2017
#####

**Today's Progress**: Added a data file for upgrades so that it isn't in my
main code

**Thoughts:** This took me a while to format the data file correctly for
javascript. Hopefully this will make implementing new upgrade a lot easier in
the future. I need to make some data files for other object but it will be
much quicker next time because I know how to actually format them now. I need
to also use the data files in my actual code to generate upgrade buttons etc.

**Link to work:** [Code Fights](https://codefights.com/)


