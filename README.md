# PodcastCatcher

This program will download the RSS feed, cover art, and all the episode audio files. It will then make a simple website from the titles and descriptions of the show itself and the episodes. The website has simple relative links to it can be used on a machine with no web server. Just open an .html file in the browser.

##  Requirements

 - Git
 - Linux, MacOS or Windows 10 with WSL
 - Python 3+

## Install

'''bash
git clone https://github.com/eskimohunter/PodcastCatcher.git
cd PodcastCatcher
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
'''

## Usage

positional arguments:
url            Podcast RSS URL
path           Output Path

optional arguments:
-h, --help     show this help message and exit
-v, --verbose  increase output verbosity

### Example
'''bash
python podcast_catcher.py -v "https://linuxmatters.sh/episode/index.xml" "podcasts/Late Night Linux/Linux-Matters"
'''

## Credit

- Robert Bellchambers
 - [Jason Rigden](https://twitter.com/mr_rigden)