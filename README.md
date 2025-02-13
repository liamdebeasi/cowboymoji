# Cowboymoji
They always say "yee haw" but they never ask "haw yee"... until now.

![sample](sample.png "sample")

This is a simple library that provides standard Unicode [emoji](https://en.wikipedia.org/wiki/Emoji) support for cowboy and pensive cowboy variants of popular emojis. It is built off of the [twemoji emoji set](https://github.com/twitter/twemoji).

This library supports 301 cowboy emojis and 37 pensive cowboy emojis.

- [Full set of cowboys](scripts/cowboy_full_set.png)
- [Full set of pensive cowboys](scripts/pensive_cowboy_full_set.png)

## Structure

All emojis are distributed using the source emoji code as the filename. To convert to your own naming conventions, use the [Unicode Emoji List](https://unicode.org/emoji/charts/full-emoji-list.html).

- `assets/cowboy/png` contains 200x200px `.png`s of cowboys.
- `assets/cowboy/svg` contains `.svg`s of cowboys.
- `assets/pensive_cowboy/png` contains 200x200px `.png`s of pensive cowboys.
- `assets/pensive_cowboy/svg` contains `.svg`s of pensive cowboys.
- `scripts` contains scripts to generate new cowboymojis and pensive cowboymojis programmatically.

## License

Copyright 2021

Code licensed under the MIT License: <http://opensource.org/licenses/MIT>

Graphics licensed under CC-BY 4.0: <https://creativecommons.org/licenses/by/4.0/>
