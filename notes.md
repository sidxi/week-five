# Quick Links
* [New terms, alphabetical](#New-terms,-alphabetical)
* [Resources I found useful](#Resources-I-found-useful)
* [Errors I had](#Errors-I-had)
* [Questions I asked](#Questions-I-asked)
* [Other thoughts](#Other-thoughts)

# New terms, alphabetical
* 7z: a compressed archive file format that supports several different data compression, encryption and pre-processing algorithms.
* Decimal degrees (DD): express latitude and longitude geographic coordinates as decimal fractions and are used in many geographic information systems (GIS), web mapping applications such as OpenStreetMap, and GPS devices. Decimal degrees are an alternative to using degrees, minutes, and seconds (DMS). As with latitude and longitude, the values are bounded by ±90° and ±180° respectively.
* GPL: General Public License
* Graphic Information System (GIS):  allows analytical questions to be asked of, and derived from, different layers of spatial or spatialized data
* Information visualization: the mapping of abstract data to graphic variables in order to make a visual representation 
* Leaflet: a JavaScript library developed by Vladimir Agafonkin for use with tiled maps. Launched in 2008, Leaflet has become widely used in tile web mapping because the library’s low-barrier customization and interactivity with map elements, and because of its simplified setup when compared to a WMS served map.
* Map Warper: a service that allows us to upload images of maps, and then tie ‘control points’ to real-world geography such that we stretch and warp the image to overlay the physical world
* Sonification: an auditory technique that maps aspects of data against things like timbre, scale, instrumentation, rhythm, and beats-per-minute to highlight elements that a visual representation might not pick up
* Webmaps: literally, maps on the web. Used mostly for conveying the results of GIS analyses
* Web Map Service (WMS): an interface that enables us (the clients) to request specific maps i.e. visual representations of geographic information from a geospatial database

# Resources I found useful
* https://craftingdh.netlify.app/week/5/instructions/
* https://craftingdh.netlify.app/week/5/sound/
* https://craftingdh.netlify.app/week/5/mapping/
* https://craftingdh.netlify.app/week/5/posters/
* https://craftingdh.netlify.app/week/5/static-websites/
* https://electricarchaeology.ca/2019/12/20/making-nerdstep-music-as-archaeological-enchantment-or-how-do-you-connect-with-people-who-lived-3000-years-ago/
* http://www.themacroscope.org/?page_id=875
* https://www.gnu.org/licenses/gpl-faq.en.html#WhatDoesGPLStandFor
* https://en.wikipedia.org/wiki/7z
* https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site
* https://en.wikipedia.org/wiki/Decimal_degrees

# Errors I had
I actually only had one error this week, perhaps because I have a _little_ more familiarity with the tools we were working with. This week, Webmap initially wasn't working for me:

![webmap not working](https://github.com/sidxi/week-five/blob/master/Errors%20%26%20Fixes/Week5%20Error%20webmap%20hosting%20site%20can't%20be%20reached.PNG)

As I always do, I did a quick search in the class discord to see if anyone else had had the same issue. Luckily for me, some one had - and there was a fix! 

![webmap fix](https://github.com/sidxi/week-five/blob/master/Errors%20%26%20Fixes/Week5%20Fix%20webmap%20hosting%20site%20can't%20be%20reached.PNG)

Like was suggested, I used http://localhost:8000/ instead of http://0.0.0.0:8000/ and everything worked swimmingly.

![webmap fix proof](https://github.com/sidxi/week-five/blob/master/Errors%20%26%20Fixes/Week5%20Fix%20webmap%20hosting%20site%20can't%20be%20reached%202.PNG)

# Questions I asked
I actually didn’t ask any questions this week, which was surprising. I was, however, able to provide an answer to one of my classmates for an error I had also had in last week’s content:

![helping a classmate yay](https://github.com/sidxi/week-five/blob/master/Week5%20Michael%20Q%20Answered.PNG)

It’s truly joyful to be able to be able to help someone so they're less frustrated than you were!

# Other thoughts
* YES! I love playing with audio!!!
  * I recently took a sound studies class that left me a little bit in love with sound as a medium, so it was wonderful to see it emerge here too
* TwoTone Roman Data
  * I love that you can see the data on the side!
  *	For the coins, I wanted a sound that felt shimmery and clinky – a quick marimba was perfect!
  *	I also slowed down the entire piece by half because I wanted it to feel methodical – this is a count, not a race!
  *	I also changed the key to Eb major (well, D# but same diff) because C felt too upbeat for what I was picturing – which is dusty, methodical, rewarding work.
*	I had so much fun with TwoTone the first time around that I wanted to create something more complex! So, I found out that TwoTone gives you data options – I thought that Honey production (1998 is historical now right – right?) sounded interesting right off the bat. 
  *	I really enjoyed being able to see the different tracks – one thing I found interesting was the juxtaposition between honey production (went WAY) down and honey cost (went WAY up). What kinds of factors (beyond inflation) could have caused that to happen?
  *	I wanted to create a busy sound, like bees working, and the rapid ebb and flow of trade. I thought that this was an important part of telling the story
*	Tbh, the hardest part with mapify was coming up with a story that had a strong location motive. Also, the locating abilities weren’t quite as sensitive as I was hoping they would be! Alas...
*	Webmaps!
  * On a webmap, the z value (zoom level) has a range between 0 and 21, where 21 returns a tile with greatest detail (and smallest sized tile)
  *	I did look at other maps, but the one you chose is the most easily recognizeable spot and despite spending 4 years in Ottawa, I still don’t know the city as well as I would have lived to
    *	Also, adding in the control points felt like I was playing a strange game of where’s waldo/spot the difference – instead, it was “find the similarity”!
  *	What is metadata, _really_? I know that it’s “data about data,” and I know that it provides important information about what data is & the information it contains, but what does that actually mean?
  *	Dr. Graham didn’t specify whether we should take the first map out after we’d put the georectified map in, so I didn’t *shrugs*
  *	You should have SEEN my face when I made the 3rd marker move – I looked at it my mouth DROPPED. I couldn’t believe it, it felt like magic
  *	To me, a map has to have a zoom. Even though our map doesn’t _NEED_ a zoom, I’ve literally never seen a digital map without a zoom (and let’s be real, the only times I’ve really used non-digital maps is in textbooks or art projects). So I created a fourth index to put [this one](https://github.com/kartena/Leaflet.Pancontrol) in my map, pulled from [the list Dr. Graham gave us](https://leafletjs.com/plugins.html)
* This infoheap tutorial was set up for mac users, and didn’t work for windows users, which I found frustrating. [This tutorial](https://daviesmediadesign.com/how-to-import-palettes-into-inkscape/) ended up being helpful for me. Thank you to my fellow classmate Mychelle for sharing it with the class!
