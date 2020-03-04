# Pyhelpers

I write a lot of quick scripts - most of the time they end up in my private homedir repository. Since I'm randomly cleaning things up, I'm going to be adding scripts to this public repository over time.  Unfortunately, due to age (some of these are from 2008) you'll need both python3 and python2 - sorry about that.

## Using

The easing thing to do is clone this repository somewhere add add the *scripts* directory to your $PATH.

## Scripts

**get_current_song** - Yanks the current song from spotify so that you can access it from other scripts. I use it with [i3](https://i3wm.org).

**mailserver** - The python STL has a built in SMTP server. I can just never remember how to run it - this is a wrapper.

**webserver** - The python STL has a built in HTTP server. I can just never remember how to run it - this is a wrapper.

**diffmissing** - Something quick, to tell me what lines are missing from each file.

**terrarist** - One of my favourite patterns for terraform is reading variables from an ansible-vault. Unfortunately the two don't integrate sanely. This script solves that.

**passgen** - Painlessly creating linux password hashes since 2013!

There are others - but these are the most useful.
