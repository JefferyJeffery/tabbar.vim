# Tabbar #

This is a mirror of [http://www.vim.org/scripts/script.php?script_id=1338]()

Recommend use [pathogen](https://github.com/tpope/vim-pathogen/) to manage your plugins

## Changlog ##

* default set `g:Tb_MoreThanOne=0` to avoid open more than one tabbar window
* do not execute when using vimdiff

How to Use:
1. Switch tab
~~~
<leader>1 switch to tab 1
<leader>2 switch to tab 2
<leader>3 switch to tab 3
<leader>4 switch to tab 4
<leader>5 switch to tab 5
<leader>6 switch to tab 6
<leader>7 switch to tab 7
<leader>8 switch to tab 8
<leader>9 switch to tab 9
<leader>0 switch to tab 0
~~~
2. Switch to next tab cycled

~~~
<leader>te
~~~

3.
Open TabBar
~~~<leader>ts~~~

Close TabBar
~~~<leader>te~~~

Open/Close TabBar
~~~<leader>tt~~~

###TabBar commands
:TbStart      //Open TabBar
:TbStop       //Close TabBar
:TbAup
:TbToggle     //Open/Close TabBar
:Tbbn         //Switch to next tab cycled
