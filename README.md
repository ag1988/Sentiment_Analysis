# Sentiment_Analysis

### Author: Ankit Gupta

Description: A deep recurrent neural network (RNN) based classifier trained using the IMDb reviews dataset for detecting +ve/-ve sentiment in text. Text is encoded using trainable word embeddings and we get 90% test accuracy. Classifier can then be used to determine the sentiment score on Twitter data collected using the Twitter API.

Python code in form of a Jupyter Notebook can be viewed [here](https://github.com/ag1988/Sentiment_Analysis/blob/master/Sentiment_Analysis_using_RNN.ipynb).

pca_words.png : 2-D visualization of the embedding matrix using PCA

#### Sample Outputs : 

1) input: Although it wasn't exactly my thing, I kinda liked it.

scores: </br>
-ve 0.284856 </br>
+ve 0.715144 </br>

sentiment: positive

2) input: Underwoods goofy story about a young man(Arquette) who convinces his friends 
that they should kidnap Frank Sinatra Jr. (Nicholas). The film is written 
ridiculously, direction is odd, dialogues are out of place and scrambled, the 
actors didn't do it much justice either, Arquette is annoying throughout, Ian 
Nicholas was nonexistent, Macy was decent, but only because hes a pretty good 
actor and probably just tried his best not to come out of this project with a 
totally embarrassing performance, he was at least tolerable. This is a stupid 
film in my eyes, boring at times, not entertaining, just a film that i wouldn't 
recommend to anybody.

scores: </br>
-ve 0.981433 </br>
+ve 0.0185666 </br>

sentiment: negative

3) input: Why can't more directors these days create horror movies like "The Shining"? 
There's an easy answer to that: modern day directors are not Stanley Kubrick. 
Kubrick proved once-and-for-all with this movie that he is truly one of the 
greatest directors and auteurs of all time. So, the plot is fairly simple. A 
man named Jack Torrance (played brilliantly by Jack Nicholson)and his family 
move into a large, secluded hotel to watch over it for the off-season. The 
kicker is that the previous caretaker of the hotel savagely murdered his wife 
and two girls. What follows can most readily be summed by the title of the 
movie, but you have to watch it to see what I mean. This is the first 
movie in a very long time to strike me as "scary". It's some seriously messed up 
stuff, but in a good way. One of the things that adds to the scare factor is the 
amazing music. Music has been a major part of Kubrick's movies (2001: A Space 
Oddysey and A Clockwork Orange, just to name a couple) and he definitely 
doesn't disappoint with this one. The score completely sets the tone and this 
film would not be the same without it. Finally, I must comment on 
Nicholson's legendary performance. Jack is terrifyingly convincing as a crazy 
killer. In fact, just his stare steals a few scenes of this movie. This is 
top-notch acting that must be seen to believe. There will never be a 
horror movie that quite matches this one. R.I.P. Stanley.

scores: </br>
-ve 0.0127282 </br>
+ve 0.987272 </br>

sentiment: positive

4) input: Lets make a movie about a talk show that already exists and basically have 
everything that happens on the show! Well if that idea doesn't intrigue you, 
which it shouldn't, stay away from ringmaster. I had the displeasure of seeing 
this in the theater and actually being able to sit through this mess of a movie. 
I guess jerry springer doesn't play himself as it shows from the cheap props for 
his show (yes it looks even cheaper than the real jerry springer show) and he is 
only known as jerry in the film. The plot (if you can call it that) is about a 
daughter while living with her mother decides to start sleeping with the 
mother's live in boyfriend. So the mother's brilliant idea is to call the jerry 
springer show as well as getting it on with her daughter's boyfriend. (Is it any 
coincidence they live in a trailer park). Meanwhile somewhere else in america a 
woman finds her cheatin' man with her friend in bed together. So of course call 
america's therapist Jerry springer! I'd talk about the rest of the film but even 
thinking about the film now is giving me a headache. Jamie Pressly who plays the 
daughter looks totally unattractive in the movie. And remember Michael Dudikoff 
the kick ass karate master from the american ninja series? Well take a look at 
him now as a white trash drunk. The thing is he really looks too horrible and 
out of shape to call it "getting in touch with his charecter". But if your idea 
of fun is seeing Jerry Springer sing a country song about his own show or guys 
hooking up with transvestites...well...JUST WATCH THE SHOW INSTEAD! ... at least 
steve was smart enough to stay out of this flick. 

scores: </br>
-ve 0.984618 </br>
+ve 0.0153823 </br>

sentiment: negative
