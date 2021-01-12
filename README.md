# redyt-portable
## Scrape Reddit images to a folder.

<br>

**(Removed <ins>_dmenu_</ins> and <ins>_sxiv_</ins> dependency)**

***

Add your favourite subreddits to ```subreddit.txt```

If the user does not modify this file, it will contain, by default, subreddit `linuxmemes`.
However, this default subreddit can be changed by modifying the variable `defaultsub`.

## Usage:
***
 - You can pass a subreddit and no of posts as an argument (`./redyt [your-subreddit] [no of posts]` ) or just execute ```./redyt``` to use subreddits in ```subreddit.txt``` and default limit as 20
 - `./redyt clean` to clean downloads directory


(Images will be downloaded to corresponding folders.)

Here's an example of a custom `subreddit.txt`: http://0x0.st/-rbq.txt

***

Please note: you will need to install the following programs:
  - jq (JSON parsing)
  - xdg-utils
  - ~~dmenu (User Input)~~
  - ~~sxiv (Image Viewing)~~

`notify-send` is also recommended but, if not present, `echo` will be used as a notifier.
