DOCUMENTATION


Jacob Shumard
Project 3



INTRO


Project 3 was an impeccable labyrinth that allowed me, and I assume 
the rest of my fellow coding comrades, an oppurtunity to explore the
possible challenges that we might face some time in the perhaps near
future. We were assigned a relatively short task to tackle, but there 
is no cadence of completion unless a puzzle was thrown out in our path.
The instructions we were provided prevented us from doing a copy paste
"follow along project." I myself enjoyed this intruiging for a change. Sometimes
during the labs it seems we are just copying out code from a JAVADOC. 
Here since we weren't accompanied by very much assistance in the write-
up, it was more of us being handed an end goal, and trying to figure out 
a way to get there with almost 0 guidence, and it seems like I got there.



MESO AVERAGE


The first quest on my journey was to slay the public class that is MesoAscii.
I don't neccesarily understand what Ascii means, nevertheless, the Abstarct class
gave me some pointers on what to do since the writeup did not. It was simply another
avergager which I have plenty of practice under my utility belt from previous labs and
personal works I have created. The MesoAscii class required a constructor of a MesoStation,
which thankfully was provided to us. I had a MesoStation as a private instance variable and
initilized it in the consructor. Next came the only method the class had to offer. I took
four characters and took the average of their values. 



THE HASHMAP


This next part, was a bit tricky. It was the second class out of third that we were required
to complete from scratch. MesoEquals. I found it weird to finish this, but I managed to do so without any
errors. The constructor was just a four letter String which I assumed meant it itself would be
compared to the other Stations in the Mesonet. The issue here was the only way to calculate the
average was in the MesoAscii class. It felt strange but I didnt see another way to do it: I 
created two objects from MesoAscii so I could calculate the average. I then imported a Buffer
Reader to read the Mesonet file. I created a for loop which creates a different MesoAscii each
time to be compared with the one of the class Meso. If the average was the same I would put it
into a HashMap. It wasnt too hard, just awkward.



SORT AND PASTE


The final class on my bucketlist was something that sounds similar to Mexico. Lexicographical. This class had
a constructor and a method which inherits from a parent class called MesoSortedAbstract. I spent a good 
portion of my duration on this part of the project doing something completley useless. I tried several different
unique ways to go about sorting a HashMap. None of them worked and I will not go into details about any of them,
but I ended up learning about TreeMaps which actually just sort the Map for you. I created a TreeMap in the sorted
method of this class and sorted my HashMap that I made in MesoEquals. Now that I had the sorted version of all of
the MesoStations with a certain Integer of average I called that method in the constructor, and printed it all out
using an enhanced For Loop. I really wish I knew more about TreeMaps.




CONCLUSION


I don't yet know the real reason behind MesoStations quite yet. As far as I know they are nothing more than a 
cluster of letters. If the reason behind these projects is to teach us about what the stuff we are seeing 
really means, then I don't know how close I am to understanding the intracacies behind every character on the
screen. If Mesostations have something to do with coding then I haven't yet learned that part about it either.
As far as techniques go I haven't really learned anything knew, I suppose that much of this course is to be 
displayed in the labs and not the projects. I can for know, the least I could say is that projects are helping
me tackle problems where the answer isn't necessarily right in front of me, and while I thought the writeup
was subpar at first, I'm pretty sure most of my future problems will be presented in a even worse manner. As 
long as I'm okay with completing these projects I guess I am on the right track. Now I just need to find a way
to get a good grade on the very difficult exams.




















