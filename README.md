# Randpass

> Bash script to generate a random password and copy it to your clipboard.

## Install

```
$ curl https://raw.githubusercontent.com/kjbrum/randpass/master/randpass > ~/bin/randpass
$ chmod +x ~/bin/randpass
```

## Usage

```
Generate a random password and copy it to your clipboard.

You can choose the length of the password, as well as the type.
The default password is 16 characters long and will be a mix of all the types.

Usage:
    randpass -l 10
    randpass -t num
    randpass -l 12 -t alphanum

Options:
    -h    Display help prompt
    -l    Password length
    -t    Password Type: alphanum, alpha, num, sym
```

## License

Copyright © [Kyle Brumm](http://kylebrumm.com). Free to use on whatever and may be redistributed under the terms specified in the [license](LICENSE.md).
