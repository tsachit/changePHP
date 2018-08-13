# changePHP
changePHP is a simple bash script I built for myself to switch between php versions for old and new projects I work with.

If you have multiple PHP versions in your linux and if you are a type of person who don't want to remember and type the whole steps to switch between PHP versions in your console, this tutorial is for you. Follow the easy instructions.

# Steps

1. Clone/Download this project.
2. Go inside this project(in changePHP folder).
> cd changePHP
3. Copy paste this command.
> sudo ln -s $(readlink -f changePHP) /usr/bin/changePHP
4. Done.

P.S. Make sure you have the correct permissions to run the script. See example

#### Example: Changing PHP from x.y to 5.6 ####
> changePHP 5.6

#### Example: Changing PHP from x.y to 7.1 ####
> changePHP 7.1

#### Example: Changing PHP from x.y to 7.2 ####
> changePHP 7.2

