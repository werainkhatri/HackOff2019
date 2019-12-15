# HackOff2019

## Problem

In this day and time, many college students face strenous and overwhelming tasks of reading a lot of material, books, novels, research papers,
and other things. We intend to make this process a little easier by making a sophisticated text-summarizer for our targeted audience!

## Solution

We used the **gensim** library in python that has prebuilt **NLP** ranking models to create our summaries. But this is not enough.
All users do not want the same amount of summary from a given amount of text. So we added two sumamry lengths for now, 20% and 40%.
But even that is not enough. If a student still has to read a couple of hundred lines, its not really a big relief.

This is where our app comes in. Our team used **flutter** to make the frontend of an app that has a given amount of (user defined) cards.
These cards hold a snippet of the summary for the user to read in their own time and pace. Considering the user splits the summary into 
multiple cards, this double reduction system makes sure that the user will be able to read and *assimilate* a given snippet, and therefore
the entire summary after reading them all.




