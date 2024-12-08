Advent of Code 2024
===================

Better seen at UnisonShare:  
https://share.unison-lang.org/@agjacome/advent-of-code-2024/code/main/latest

### How to

```
$ nix develop

$ ucm
> clone @agjacome/advent-of-code-2024/main
> run day01.part1.print
> run day01.part1.submit
```

From Unison's [Advent of Code
template](https://share.unison-lang.org/@unison/advent-of-code):

>  The only required configuration is an Advent of Code API token. It is used to
>  fetch user-specific input for a problem and to submit answers for a problem.
>
> You can get your API token by logging into [Advent of
> Code](https://adventofcode.com/) in your browser, finding the cookie named
> session , and copying its value.
> 
> By default, the Advent of Code client will look for an API token in the
> following locations (in this order):
> 
> * The `ADVENT_OF_CODE_TOKEN` environment variable * A file located at
>   `$XDG_DATA_HOME/unison-advent-of-code/.token.txt` * A file located at
>   `$HOME/.local/share/unison-advent-of-code/.token.txt`
