<h1>Entry 3</h1>
<h4>Recap of the week</h4>
<p>So this week I have been experimenting in a sandbox while following along with the guide provided by the Earsketch team. The guide has been very informative and it has given me ideas to open other scripts and experiment with different types of music.</p>
<h5>What I have learned this week</h5>
<ul>
<li>You can create functions to save more time and make the code less messy<b>(See example)</b></li>
<li>I also learned that you can create your own Music or take an existing audio file and upload it to use it in the music. I still have yet to try it, I will include the results in my next blog entry</li>

</ul>
<h5>example</h5>

``` python 

# python code
#
# script_name: Custom Functions
#
# author: The EarSketch Team
#
# description: Defining our own function that makes a section of music
#
#
#

#Setup
from earsketch import *
init()
setTempo(100)

#Music

# Defining our new function with two parameters
def myFunction(startMeasure, endMeasure):
 fitMedia(ELECTRO_DRUM_MAIN_BEAT_003, 1, startMeasure, endMeasure)
 fitMedia(ELECTRO_ANALOGUE_PHASERBASS_003, 2, startMeasure, endMeasure)

# Calling our function, passing it two arguments: 1 and 17.
myFunction(1, 17)

#Finish
finish()
```
<h5>Thoughts</h5>
Some thoughts that I had was regarding my final project. I have already decided to work on EarSketch, but I can't <b>REALLY</b> just make songs and call it a project. So next week im going to be asking my classmates if they want custom music for their app/game. That way my project has a purpose and I can help my friends out.
<h3>Takeaways</h3>
Some takeaways I had were:
<li>I have learned so much more independently than when we were working as a class</li>
<li>Sometimes it is ok to ask for help from your friends, regardless of what project they are working on. I had a friend of mine listen to my test music in my sandbox and give me feedback. </li>