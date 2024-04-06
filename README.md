# PodcastArchiver
Do you want to save a podcast to your local machine? Maybe you are canceling your podcast service subscription but you don't want to permanently lose all your episodes. Maybe a podcast is getting canceled and you want to save the content. Or maybe you just want to archive a show for the future!

This program will download the RSS feed, cover art, and all the episode audio files. It will then make a simple website from the titles and descriptions of the show itself and the episodes. The website has simple relative links to it can be used on a machine with no web server. Just open an .html file in the browser. The program also compresses everything in a nice tar ball.

##  Requirements

 - Git
 - Linux, MacOS or Windows 10 with WSL
 - Python 3+

## Install

    git clone https://github.com/eskimohunter/PodcastCatcher.git
    cd PodcastArchiver
    python -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt

## Usage

    positional arguments:
      url            Podcast RSS URL
    
    optional arguments:
      -h, --help     show this help message and exit
      -v, --verbose  increase output verbosity

## Credit

 - [Jason Rigden](https://twitter.com/mr_rigden)