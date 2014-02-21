# Project Title
BookBars - Visual Interpretations of Classic Books

## Authors
- Jim bruges Github: chromebookbob

## Description
I wrote a python script with an algorithm that took letters and converted them into a given height and colour then displayed these letters as lines of different colours in a window with a background colour determined by the length of the string of text. An example of this can be seen above. There were a number of issues with my plan as the numbers which the letters were converted to were all fairly similar, there was no great distance between them, meaning that the colours and heights were fairly similar. 

By this time I had something vaguely resembling a program to convert the world of words to our visual world, via the world of computers. The results, though interesting and sometimes beautiful with obscure characters were not good enough. I suddenly had the idea to convert not just the world of words but the world of literature into one of these pictures. I searched on Project Gutenberg, a website where out of copyright books are converted to digital and distributed for free, for a text file of a favourite classic of mine, A Picture of Dorian Gray. Having found it, with the knowledge that quotation marks would break my code, I removed unnecessary whitespace and quotation marks from the text until I had just the words. I then inserted these into the message variable of my program. 

There are something like 400,000 letters in this book and I had no idea why my program was not putting the lines on the screen, but it turns out that the resolution of the window (how many pixels wide and hight it was) was too small and the width of each line was being set as 0. I tried to make the screen 400,000 pixels wide but my computer crashed. So I made a compromise by making the program sample only about a quarter of each of the books.
## Link to Prototype
http://www.raspberrypi.org/forum/viewtopic.php?f=32&t=67125&p=490911#p490911


## Links to External Libraries
 Github Project
[Example Link](https://github.com/chromebookbob/devart-template "Click Here")

## Images & Videos

![Image](https://dl.dropboxusercontent.com/u/21889761/Study%20In%20Scarlet.jpg")

