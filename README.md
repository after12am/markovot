BoobyTrap
=========

## Demo

<a href="https://twitter.com/dev_12am">@dev_12am</a>

## Usage

A bot tweets a trap message that is artificially created using a second-order Markov chain. To setup BoobyBot, run the following commands in a new terminal.

    cd /path/to/bin
    ./bot setup

To gather tweets, run the following commands. If you want to set limit, set `pick up num` after `./bot pick`.

    ./bot pick [pick up num]

To tweet, run the following commands.

    ./bot post

## Notes

* You can't tweet When you post a tweet without picking up tweets. At first, you run `./bot pick`.