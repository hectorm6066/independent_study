# Entry 4
##### Updates
So, since my last entry, I have been experimenting a lot more in the sandbox. I have started to experiment with Volume control and how the set effects work. I think I have gotten better and I am going to continue experimenting into spring break and the week after. After those 2 weeks, I am going to start working on 1 song and center it around a genre. I still have yet to choose my favorite genre, so I am going to be debating it over the next 2 weeks.
### Example
#### Part of my sandbox
```python
from earsketch import *

init()
#Setup
setTempo(125)
#music
# fitMedia()
# fitMedia(Y46_ELECTRO_2,1,1,4.9)
# fitMedia(Y46_ELECTRO_1,1,4.9,10)
# def myFunction(startMeasure, endMeasure): Functions work the same way like before
#Main
# fitMedia(Y56_SYNTHHARP_1,1,1,5)
# fitMedia(YG_ELECTRO_SYNTH_BRASS_2,1,5,10)
fitMedia(EIGHT_BIT_ANALOG_DRUM_LOOP_009,1,1,2)
# fitMedia(RD_POP_SYNTHBASS_7,2,6,14)
# fitMedia(Y15_ELECTRO_1,1,14,34)
fitMedia(RD_POP_SYNTHBASS_6, 1, 2, 21)
fitMedia(YG_NEW_FUNK_SYNTH_1,2,20.8,33)
#end
for measure in range(1, 21):
  setEffect(1,VOLUME, GAIN,-60,measure,6,measure)
for measure in range(21,33):
  setEffect(2, VOLUME, GAIN, -40, measure, 10, measure)
# fitMedia(EIGHT_BIT_ATARI_SFX_004,3,6.5,7)
#Finish
finish()
```
### Thoughts
I have several thoughts about this week. So, I've decided I will just make music instead of making music for someone else. Although if someone DOES need music for their game, I could help them. I think I will debate about the genre of music I wish to pursue into week 5.
### Takeaways
- Always **experiment**, follow along with the guides if there are any, but copy and paste the code and try something different out.
- Don't be afraid to ask your friends for their opinions. I always ask my friends on how it sounds so I can see how the music should flow.