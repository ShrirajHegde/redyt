# redyt-portable
## Scrape Reddit images to a folder.

<br>

**(Removed <ins>_dmenu_</ins> and <ins>_sxiv_</ins> dependency)**

***

If no arguement is passed, by default, subreddit `r/linuxmemes` will be chosen.
However, this default subreddit can be changed by modifying the variable `defaultsub`.

## Usage:
***
 - You can pass a subreddit and no of posts as an argument (`./redyt [your-subreddit] [no of posts]` ) or just execute ```./redyt``` to use subreddits in ```subreddit.txt``` and default limit as 20
 - `./redyt clean` to clean downloads directory


(Images will be downloaded to corresponding folders.)

Here's an example of a custom `subreddit.txt`: http://0x0.st/-rbq.txt

***
## Requirements
Please note: you will need to install the following programs:
  - jq (JSON parsing)
  - ~~dmenu (User Input)~~
  - ~~sxiv (Image Viewing)~~

### `notify-send` and `xdg-utils `are also _recommended_.

***

If `notify-send` not present, `echo` will be used as a notifier.

If `xdg-utils` is absent, then find the downloaded images in "downloads" folder
