# Mastoloader
A command line utility for uploading images, audio and videos to mastodon.

## Requirements

* Python3 
* Mastodon.py via pip3

## Usage

First, put the file in the /usr/bin/ and use chmod to give it executable permissions.

Secondly, add a directory called .mastoloader to your home directory. This is where the JSON file with your information will go. Attached is a template json file. Fill it in accordingly then put it in the directory.

Once this file is in the directory, running the command: 

``` mastoloader [instancename] [file] ```

Where `instancename` is the name of the JSON file in mastoloader that you want to use for uploading purposes.		