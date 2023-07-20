# Foolishness
Bughunt

Thanks for taking a look at this for me. I apologise in advance if I have uploaded the project wrongly or something and it doesnt work. 

Assuming it works:

THE PROBLEM:

I am part way through a game making tutorial, and what I am trying to do right now is to add apples to the trees as is demonstrated in the tutorial, see:
https://youtu.be/T4IX36sP_0c?t=9838 (I am actually a little further along, but I dont think the extra code affects the bug)

What happens is that the apples layer displays randomly: If I run the game several times, maybe 30% of the time the apples show, 70% they dont.

I dont understand where the random behaviour comes from: I only use two functions imported from random (see sprites.py) and I'm pretty sure neither of them affects the display of the apple layer (its actually called the 'fruit' layer, see settings.py). The number of apples PER TREE is random, but as far as I can tell this has no impact on the display of the apples layer itself.

It feels like the bug should be somewhere in sprite.py or level.py. My best guess is that maybe its got something to do with the timers that are setup for different purposes. 

I guess the worst case is that its not a problem with the code at all, and I have somehow screwed up the environment its running in. Seems unlikely though...

NOTE: Code in code folder is incomplete, it only contains the code I have completed in the tutorial so far. All other folders have complete content.
