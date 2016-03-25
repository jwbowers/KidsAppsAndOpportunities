---
title: Thoughts on the Internet of KIDS Things
author: Jake Bowers and Cara Wong
---

This is a memo that we wrote after spending a great morning with Bruce Sterling and Jasmina Tesanovic at [Casa Jasmina](http://casajasmina.arduino.cc/). Jasmina taught us about the [Internet of Women Things](http://boingboing.net/2015/12/16/ada-lovelace-what-would-go-in.html). And we built open-source furniture with Bruce. And, we left that visit mulling over the question about the Internet of Kids Things. We are putting it on github in public form to encourage commentary and collaboration.

# Open source kids furniture

We already have a few great models for baby and kid furniture from [Stokke](https://www.stokke.com/). We can imagine either partnering with them or hacking/improving their designs. Their [high chair](https://www.stokke.com/USA/en-us/highchairs/tripp-trapp/1444.html) is especially genius (we own two and both were in current use by our 4 and 8 year olds as more comfortable chairs at the common dining / project table. We have avoided kid size tables and highchairs away from the common space. The kids want to work at the same table where we are working. Basically we drank the Stokke cool-aid about kids and eating and tables.

The [crib](https://www.stokke.com/USA/en-us/nursery/stokke-sleepi/1043.html) is also great. It was very sturdy, rolled around and through doorways, and thus allowed flexible use of space. It also lasted longer than an ordinary crib  --- we could take half the wall off so that kids could climb in and out on their own, make it into a toddler bed, and ultimately it could become 2 small chairs. (It’s the only crib narrow enough to go through doorways, or at least it was when we were looking
for one.)

Both designs are truly high quality but also seem very printable (with modifications for the crib — I’m imagining cutting arcs rather than bending wood). I wonder if Stokke would do a Creative Commons license so that people in developing markets could print their own while Stokke could sell their own fancy versions to first worlders.  

# The Internet of family things and monitoring

When kids are very young we want to monitor them. Cara and I coded a lot of data from the kids to help us figure out whether this cry was hunger or diaper or tired or something else. Now folks use old iPhones on wifi as two way video and audio baby monitors. (Happy to send screen shots of the sleep data from our kids or share for an art project. It basically looks like a plan to make a prisoner insane — randomly chosen moments of sleep of more or less random length.)

You can see some of this in these products <http://mimobaby.com/> or <https://www.owletcare.com/>. They look new enough that I wonder about open-source discussions, common standards for parental surveillance  and indoctrination programs, etc..

For toddlers we might want to not only close sockets, and make opening the knife drawer difficult, and put cleaning chemicals up high, but we also might want to know when they are near the stove. Proximity monitors or warnings ("Cosmo, you are too near the hot stove. Please take a step back.") might be a feature of this home. That is, rather than put monitors on kids, you might prefer a few gait recognition/face recognition (?smell recognition?) sensors in key locations.

Roomba is definitely a feature of such a home. (As are other labor saving devices.) We are still waiting on a drone that cleans toilets and sinks and a clothes folding machine and a robot to put away the dishes from the dish washer.

# Kids and the connected home

Kids love feedback and interactivity. They are much more likely to play with and explore the possibilities in a connected home than adults.  We had a few thoughts about toys or activities for kids there.  

## Dream Toy / Enhanced MagnaTiles

[MagnaTiles](http://magnatiles.com/) tend to be the most intensively played with item in any home we've visited — even more so than Legos. We can image a hack in which each tile lights up , or even eventually becomes a controller for sound or displays, depending on the relations between the tiles. For now, imagine hot gluing rfid and LEDs plus small watch batteries to the center of each tile. When a red square connects with a red triangle red lights turn on. When a red square and a blue square connect, the blue and red lights alternate. (Etc...Basicallly imagine allowing kids to explore a very simple cellular automata in physical form.). Version 2 might involve more elaborate connectivity enabling MagnaTiles to be like reconfigurable control surfaces for other parts of the home.

A search for “magnatiles hack” suggests that you can do a very easy Magnatiles and color hack
using [Tangeez ](http://www.tangeez.us/)(<https://www.youtube.com/watch?v=y0qDoDFny38>)

My dream toy might be like a combination of [LittleBits](http://littlebits.cc/) and Magnatiles. I am imagining something like a way for kids to discover [cellular automata](http://mathworld.wolfram.com/CellularAutomaton.html) in a physical form. 


## Easy 3D printing

[Tinkerplay](http://www.123dapp.com/tinkerplay) is one step. As is [123D Sculpt](http://www.123dapp.com/sculptplus). However, it is still not seamless to hit "print" and to have a toy or sculpture successfully emerge from a 3D printer (especially in multiple colors or in easily and non-toxically colorable form). For example, some forms need the printer to add supports and this is usually relegated to a secondary piece of software (say, that converts .stl files into another language and perhaps adds supports). A truly dead-simple tablet to printer sculpture creator and printer system would empower kids. Basically, you’d just need an app to go from Tinkerplay to a printer via Wifi/Bluetooth via a processing step, say, with some scripts and a nice person.

## The Kitchen

Kids love to cook. Beyond [raising the kids to the right height,](http://www.littlepartners.com/the-original-learning-tower) I wonder about how kids can control their own food prep.

## Don't forget cardboard and duct tape (colored if possible)

Kids love to build forts. They love to build. So, if you had old boxes (big ones better). Or even some interesting set of lightweight plywood reconfigurable building boards, they will be happy. You can encourage them to take pictures of their creations and publish them on some kids-only website (no photos, no names, just cool creations). Mari has really liked the [Hopscotch](https://www.gethopscotch.com/) iPad coding environment in part because of the publish/fork/like system that they have put in place. The fact that they have videos explaining cool coding projects with female coders involved also helps.

## Don’t forget clay

… or slime or an easy way to make it (we like the Borax and Water version).

## Don’t forget paper for drawing and painting and cutting.

## Kids iPad Games and Educational Stuff

I suspect that if you had a few tablets around, kids would play very happily with them. Here are some apps on our iPads that are educational but also fun (in addition to the 3d printing apps).

# Programing

Our daughter really likes [Hopscotch](https://www.gethopscotch.com/).  I just downloaded it and handed it to her and she taught herself. It is particularly useful if you are online because then you can see what other apps people are making.

She also likes <http://www.scratchjr.org/> because it allows her to draw and modify the characters.
  
Both Scratch and Hopscotch do programing by dragging and dropping code blocks (like Scratch itself <https://scratch.mit.edu/> , or the Lego Robot coding language).

# Music

For learning Guitar, we like <https://guitarbots.com/> . We are using the free version so far (it limits the lessons to like 10 minutes, which is just about perfect for her because chords can be frustrating for little hands).

# Math

For math: My favorite math books are these ones <https://www.beastacademy.com/>   They are not easy — but pose fulfilling and interesting challenges. These are just pen and paper books, but are really innovative.

Our favorite math ipad apps are by this group: <http://www.dragonboxapp.com/> Even our kindergartener is able to play them. I recommend the Dragon Box apps themselves.

# Picture Books

I would also just get some good books in there. We love [Mo Willems ](https://en.wikipedia.org/wiki/Mo_Willems),  [Oliver Jeffers](http://www.oliverjeffers.com/), [JC Phillipps](http://www.jcphillipps.com/) (on ninjas) among others.

