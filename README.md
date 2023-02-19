# insultr

Who doesnt want to have a command that insults you when it fails.
insultr is the solution to that problem.

## Usage

`insultr <any command> <arguments for any command>`

## Examples

### Successful command

``` bash
insultr cat Setup.hs
import Distribution.Simple
main = defaultMain
```

### Unsuccessful command

``` bash
insultr cat Setu
cat: Setu: No such file or directory
I would slap you but sh*t splatters, and that would be too much of a mess.
```

## Installation

To install make sure you have stack installed and then run
`stack install`

## Tips and tricks

Also works with alias ;)
