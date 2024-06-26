# talon_umbrella

Umbrella repo for the collection of talon repos in my user directory.

Using this as a test of git submodules, to learn why everyone hates them. :)

## Cloning this repo

Remember when cloning this repo:

```
git clone --recursive https://github.com/brollin/talon_umbrella.git
```

Or if you forgot to do that, use this command:

```
git submodule update --init --recursive
```

Finally, if you do not have read access to the private repositories:

```
git clone https://github.com/brollin/talon_umbrella.git
cd talon_umbrella
git submodule update --init screen-spots mouse_guide community talon_ui_helper chess_grid brollin_talon_public
```

## Adding a submodule

Clone the repository as normal inside of this repository:

```
git clone https://github.com/brollin/new_repo_example.git
```

Then add it:

```
git submodule add ./new_repo_example
```

## More software

A number of tools that I use:

- [Talon Voice](https://talonvoice.com/) - voice command framework
- [Cursorless](https://www.cursorless.org/) - Talon plugin + VSCode extension
- [Rango](https://rango.click/#/) - voice command browser extension
- [Homerow](https://www.homerow.app/) - keyboard shortcut accessibility tool
- [Rectangle](https://rectangleapp.com/) - window manager
- [iTerm 2](https://iterm2.com/) - terminal app
