# Randpass

> Generate a random password and copy it to your clipboard.


## Install

```
$ curl https://raw.githubusercontent.com/kjbrum/randpass/master/randpass > ~/bin/randpass
$ chmod +x ~/bin/randpass
```


## Usage

```
Randpass

Generate a random password and copy it to your clipboard.

Usage:
    $ randpass <options>

Options:
    -h    Display help prompt
    -l    Password length (15)
    -t    Password Type (alpha|num|sym|alphanum|alphasym|numsym)

Example:
    $ randpass -l 10
    $ randpass -t num
    $ randpass -l 20 -t alphanum
```


## License

Copyright © [Kyle Brumm](http://kylebrumm.com). Free to use on whatever and may be redistributed under the terms specified in the [license](LICENSE.md).
