# insultr

Did you ever think that it would be great if your computer insulted you when you
execute a command and it fails.

This is the solution!

## Usage

`insultr <any command> <arguments for any command>`

## Examples

### Successful command

``` bash
$ insultr cat Setup.hs
import Distribution.Simple
main = defaultMain
```

### Unsuccessful command

``` bash
$ insultr cat Setu
cat: Setu: No such file or directory
I would slap you but sh*t splatters, and that would be too much of a mess.
```

## Installation

To install make sure you have stack installed and then run
`stack install`

## Tips and tricks

Works great with alias ;)
