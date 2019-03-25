# Using Web Audio API to produce bird songs
{:toc}
This project is to make bird songs to be used in my model railway. 
There are two ways I approached this.
1. Use recorded bird songs and play these back with the Web Audio API play function.
I found this difficult as the browser had CORS errors.  I could have tried to understand and avoid these errors but instead tried -
2. Use the Web Audio API oscillator and nodes to make the sounds.  To use this approach I had to -
   * Find out the notes made by the birds.
   * Write code to reproduce these notes.
## Spectragraphs
Ornithologists use graphs of frequency (and volume) versus time to record bird songs.  These are available on the web, for example [Birdsongs of Tuscany](http://www.birdsongs.it/).
They can also be made using a smartphine app such as SpectrumView from OxfordWaveResearch for iOS.
I used this app to compare the sound from Web Audio API with the actual spectragraph.
## Web App
[run web app](https://htmlpreview.github.io/?https://github.com/bwedgar/BirdSongs/blob/master/index.html)

