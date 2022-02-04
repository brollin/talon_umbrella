# talon_umbrella
Umbrella repo for the collection of talon repos in my user directory.

Using this as a test of git submodules, to learn why everyone hates them. :)

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
git submodule update --init screen-spots mouse_guide knausj_talon talon_ui_helper chess_grid
```
