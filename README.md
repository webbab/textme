textme
======

*Command-line texting service provided by 46elks*

This tool is still quite rough, and may behave in strange, un-accounted for
behaviors.

## Basic usage

`./textme.py "Wow, I'm sending this message from the terminal :)"`

## Configuration

The easiest way of configuring `textme` is by entering your API credentials from
[the 46elks dashboard](https://www.46elks.com/) into the command-line
application and adding `--saveconf` like 
`textme -u APIUSERNAME -p APIPASSWORD --saveconf`. You can also add a default
sender and receiver by adding the `--to` and `--sender` options.

The configuration file is colon-separated, and looks like:

````
username:REPLACE_ME
password:REPLACE_ME
from:textme
to:+46700000000
````

## ToDo

- [ ] Move configuration to "correct" location(s) depending on OS
- [x] Add quiet mode
