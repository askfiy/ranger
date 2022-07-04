# README

## icons support

For image support, copy and paste the following code:

```
git clone https://github.com/alexanderjeurissen/ranger_devicons ~/.config/ranger/plugins/ranger_devicons
```

## image preview

requires download:

```
yay -S ueberzug
```


## custom keys

Here are some custom buttons:

```
map cw eval fm.execute_console("bulkrename") if fm.thisdir.marked_items else fm.open_console("rename ")
map DD shell gio trash %s
map M console mkdir%space
map T console touch%space
map C console compress%space
map X console extract_here%space
map gG shell lazygit
map gN cd ~/.config/nvim
map gP cd ~/project/
map gD cd ~/Documents/
map gO cd ~/Downloads/
map :  console shell%space
```
