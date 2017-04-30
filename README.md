# FanBot

A twitter bot to compliment people and make them feel happy.

## Features

 - Randomly tweets a random compliment from compliments.txt at your target
 - Can be asked for an immediate compliment

## Future Features

 - Posse mode?  Retweet with hype!
 - Learns from target's tweets?
 - Target can tell bot how frequently to post?
 - Console mode for debugging?

## Installation and Operation

Installation should go pretty quickly.

 1. Clone this repository - `git clone https://github.com/rpalo/fanbot.git && cd fanbot`
 2. Create your secrets file - `mv fanbot/secrets.sample.py fanbot/secrets.py`
 3. Create a twitter account for your bot.
 4. *While logged in as this bot,* create a [twitter app](https://apps.twitter.com) for your bot.
 5. From the "Keys and Access Tokens" tab of your new app, create a new key.
 6. Take note of your Consumer Key, Consumer Secret, Access Token, and Access Token Secret.
 7. Fill these values into your `secrets.py` file.  Also fill in the username of the account you wish to be a fan of.
 8. Fill out the `main.py` file with instructions of your own.  Take note of Twitter's [rate limiting policy.](https://dev.twitter.com/rest/public/rate-limiting)  See the [schedule module documentation](https://pypi.python.org/pypi/schedule) for more info.
 9. Let 'er rip!  `python3 main.py`

Currently, I'm working on setting up logging and other things, so you'll have to figure out how you want to keep your script running.  If you have ideas let me know.  I've got a [PythonAnywhere](https://pythonanywhere.com) instance that I just spun up and keep running in terminal mode.

## Customization

If you've gotten this far, hopefully you are comfortable editing files etc.  All of the randomized compliments are kept in [compliments.py](https://github.com/rpalo/fanbot/blob/master/fanbot/compliments.py).  You can modify the start-up/shut-down messages in [fanbot.py](https://github.com/rpalo/fanbot/blob/master/fanbot/fanbot.py).  Please please please don't check your actual [secrets.py](https://github.com/rpalo/fanbot/blob/master/fanbot/secrets.sample.py) into your repository without encryption.

## Contributions

I've never really had anybody contribute to any of my projects before, but I'm super open to it.  I would almost say it might be a good idea to lay out a rough skeleton of your changes and open the pull request up front so we can talk about it before you do a bunch of work.  

## Code of Conduct

I don't think I'll need this, but it can't hurt.  Obviously the code of conduct comes down to the "Don't Be a Fartknuckle" System™.  To get a good feel for what it means to Not Be a Fartknuckle, check out the [Ubuntu Code of Conduct](https://www.ubuntu.com/about/about-ubuntu/conduct).  If you have any problems, don't hesitate to let me know.  If I give you problems, ditto, but additionally make sure you call me a Fartknuckle.

