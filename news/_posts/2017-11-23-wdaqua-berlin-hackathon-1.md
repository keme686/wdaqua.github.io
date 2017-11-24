---
title: It's a bird... It's a plane... It's gender bias in Marvel comics
summary: |
  As part of the WDAqua R&D Week in Berlin, students were asked to participate in a hackathon which used open data to generate interesting insights.
---

_In this blog, Lucie Kaffee, Emilia Kacprzak and Kemele Endris talk about their project analysing diversity in Marvel comic characters, which won them the prize for 'most fun' project_

Everyone loves superhero comics. They give us a portal to an easier world: The heroes, the goodies, on the one side, the baddies on the other side. 
Though is it that easy really? 

Marvel and DC offer a new world, where everything is possible. A hero can fly, mutants rescue the world, or try to destroy it. Anything is possible. 
Though is really anything possible? How much is left to one's imagination?

To understand in detail to what extent superhero comics reproduce the bias of the real world, we looked at the sexuality and gender of Marvel and DC characters, taking the whole world of the comics in consideration, not only the main characters.

The dataset, we based our analysis on was released by [here](http://www.FiveThirtyEight.com), who extract pages of fan wikis about comic characters. Those include not only hero and villains, but anyone who appears in the comics. With 16,000 marvel and 6,500 DC characters we were able to get a comprehensive understanding of the whole comic universe.

## How to be special in a world of superheros

To get an understanding of the data at hand, we started looking at the features of people who appeared often in the Marvel universe. We normalised appearance over time, so that a new character, who appeared often but only over the last two years, would have the same importance as a character who'd existed in the universe for a longer time. 
We found that the ideal features for a often appearing character would be:
Being good, having a secret identity, blue eyes, and black hair. Additionally, the characters who appear the most are male. Though these features give the best scoring each individually, none of the characters at hand combines all these features at once. As the gender indicates, female characters would not gain the same scores when it comes to appearance.

![Our version of the ideal superhero, not so ideal](/assets/images/news/2017-11-23/ideal-superhero.jpg "Our version of the ideal superhero, not so ideal")

To see what we're missing out on in the Marvel world, we used the same scoring system to find the least appealing (read: least frequent to appear) character features.
Unsurprisingly, neutral characters are boring, and appear the least. Also, being known to the authorities is really not a feature you want to have as a Marvel character. Due to the rarity of magenta eyes and light brown hair, these don't really make for a frequently featured character either.

![This version of the least appealing character wouldn't have a chance to appear in Marvel anyway](/assets/images/news/2017-11-23/least-appealing-character.jpg "This version of the least appealing character wouldn't have a chance to appear in Marvel anyway")

Unsurprisingly, the same goes for being genderfluid. Although, it should be said beforehand that we were happily surprised by the variety Marvel offers when it comes to gender. But let's look into that in detail a bit later.

## Women in a world of supermen

Overall, there's a strong bias towards male characters. In our whole dataset, the overwhelming majority of characters are male, with 71.2% of the characters being male and only 23.27% female.
 
Of the hundred most frequently shown characters, 72 are male, 27 female and one genderfluid. When we normalised the data of appearance over time, we already discovered that the distribution changed drastically: The 100 most appearing characters are 62 male, 36 female and two agender. 

This hints us, how much the time changed the Marvel universe: It appears that earlier introduced characters are more likely to be male. 

![](/assets/images/news/2017-11-23/num-of-characters.png)

In fact, while the number of newly introduced characters is higher in recent years in general, it is also evident that the number of female characters increased. 

## Everyone can be a villain

This tells us a lot about gender in the Marvel universe. But how are women actually portrayed? 

To find out, we wanted to see whether women are primarily the classically'boring' good characters. (Because, let's be honest, nothing's better than a maniacal, evil nemesis. What would Batman be without the joker?)

To get an overview on the comic world, we added the DC universe as a comparison.

![](/assets/images/news/2017-11-23/heatmap-1.png)

While Marvel from the start introduced bad female and male characters, DC showed an interesting difference: They have a visible increase of female villains over time. 

## Love in the times of kryptonite

Who loves whom in the comic universe? Well, we don't know either, but we can tell you a lot more about sexuality of characters in Marvel and DC.

![](/assets/images/news/2017-11-23/bubble-plot.png){:height="400px"}

The vast majority of the characters in Marvel are heterosexual, so many in fact, that we have Null, meaning no value, for their sexuality in our dataset. There are a few homosexual and bisexual characters however.

![](/assets/images/news/2017-11-23/heatmap-2.png){:height="400px"}

In Marvel, female homosexual characters were introduced to the Marvel universe much later than their male counterparts. Bisexual characters are more frequent in female characters. 

This not only teaches us a lot not only about the comic world, but also about the real world and how we perceive characters, what is an "acceptable" trait, what we as readers are used to.

## Happy ever after

It's getting better though. All our statistics show, that there has been an improvement in diversity in recent years- be it the ratio of female and male characters or their sexuality. However, there is still a lot to be done. 

With these comics being the source material for the multi-million dollar franchises which make up the Marvel Cinematic Universe, it's important that we continue to champion representations of diverse characters in all forms of media. After all, pop culture is merely a reflection of what a society currently considers important or interesting – a more diverse range of people reflected in it, the most inclusive we become.

