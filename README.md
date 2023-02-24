# insultr

Did you ever think that it would be great if your computer insulted you when you
execute a command and it fails.

This is the solution!

## Usage

`insultr <any command> <arguments for any command>`

When a process exits with an error code an insult will arise otherwise not.

## Examples

### Successful command

``` text
$ insultr cat Setup.hs
import Distribution.Simple
main = defaultMain
```

### Unsuccessful command

``` text
$ insultr cat Setu
cat: Setu: No such file or directory
It’s okay if you disagree with me. I can’t force you to be right.
```

## Installation

To install make sure you have stack installed and then run
`stack install`

## Tips and tricks

Works great with alias ;)

## Credits

The insult list is from [insults](https://github.com/Itz-fork/Nexa-API/tree/main/api/data)
