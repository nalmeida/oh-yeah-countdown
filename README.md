# Oh Yeah Countdown

Super [simple Countdown](https://www.bigtimer.net/?minutes=3&seconds=8&repeat=false) + [Oh Yeah theme song](https://www.youtube.com/watch?v=6jJkdRaa04g) + simple "edit in place" notes to engage your audience!

## Installation

Just download this repo and run it on a server. A quick and dirty solution is to run an instant Python server:

```
python -m http.server
```

## Using it

Just click the **Start** button and then quickly hit the **Play** on the audio.

## How to customize it

The timer is preset to 3 min and 8 seconds, the "duration" of the `oh-yeah.mp3` theme song.

If you need / want to change the duration or the theme song, just config it on [Big Timer website](https://www.bigtimer.net/), copy the URL and replace the `iframe src` in the index code.

To change the `mp3` file, save the file in the same folder as the `index.html` file and change the `audio src`.

If you only want the visual countdown, forget this project and go straight to [Big Timer website](https://www.bigtimer.net/)

The **Your local notes...** space is a "edit in place" `div` for you to add some notes. It saves the content in the browser `local storage`.

