Sierra
------

###### Day 
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19173399/ff373be8-8bdb-11e6-9ef0-0ec46c7f0d5b.png)
```VimL
"light gray background 
colorscheme sierra
```



###### Sunset 
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19173790/cc3d6430-8bde-11e6-8845-b6d2e74254f1.png)
```VimL
"medium gray background
let g:sierra_Sunset = 1
colorscheme sierra
```



###### Twilight 
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19173836/2e76d5d2-8bdf-11e6-9435-12e4fec91e97.png)
```VimL
"dark gray background
let g:sierra_Twilight = 1
colorscheme sierra
```



###### Midnight 
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19173897/aba88f8c-8bdf-11e6-82d6-a25e8a7b87df.png)
```VimL
"Almost black background
let g:sierra_Midnight = 1
colorscheme sierra
```



###### Pitch 
![Screenshot](https://cloud.githubusercontent.com/assets/11221489/19173933/fa7fa960-8bdf-11e6-932a-05f9a29b6705.png)
```VimL
"Black background
let g:sierra_Pitch = 1
colorscheme sierra
```



Installation
---------------
There are a few ways to install sierra. The first option is by using your favorite vim package manager and the second is by manual download.

###### Package Manager Option
| Manager          |                 |                                                                           |
|------------------|-----------------|---------------------------------------------------------------------------|
| Vundle           | add to .vimrc:  | `Plugin 'alessandroyorba/sierra'`                                         |
| NeoBundle        | add to .vimrc:  | `NeoBundle 'alessandroyorba/sierra'`                                      |
| VimPlug          | add to .vimrc:  | `Plug 'alessandroyorba/sierra'`                                           |
| Pathogen         | from terminal:  | `cd ~/.vim/bundle && \ git clone git://github.com/alessandroyorba/sierra` |

###### Download Option
Download the .zip and copy `sierra.vim` to `~/.vim/colors` (on Windows `<your-vim-dir>\vimfiles\colors`). Or for global accessibility, `/usr/share/vim/vimfiles/colors`.

Sierra Settings
---------------
There are several options that you can enable for sierra. You can activate them by adding each of the following variables to your .vimrc. Remember to place the variables before declaring `colorscheme sierra`.

| Description                        | Add to .vimrc                            | Screenshot                                                                |
|------------------------------------|------------------------------------------|---------------------------------------------------------------------------|
| light gray background              | `colorscheme sierra`                     | [Screenshot](http://bit.ly/1OcsXoW)|
| medium gray background             | `let g:sierra_Sunset = 1`                | [Screenshot](http://bit.ly/28Vckeo)|
| dark  gray background              | `let g:sierra_Twilight = 1`              | [Screenshot](http://bit.ly/28iLTc7)|
| almost black background            | `let g:sierra_Midnight = 1`              | [Screenshot](http://bit.ly/1YdvFN4)|
| black as pitch                     | `let g:sierra_Pitch = 1`                 | [Screenshot](http://bit.ly/1Ydv2Do)|
| Cycles thru modes after 5pm        | `let g:sierra_Campfire = 1`              | [Screenshot](http://bit.ly/1Ydv2Do)|
| Underline Matching Parens          | `let g:sierra_Nevada = 1`                | [Screenshot](http://bit.ly/1TY28XX)|
| Removes CursorLine background      | `let g:sierra_Clear_Skies = 1`           | | 

Moar Screenshots
----------------
[Screenshots](https://github.com/AlessandroYorba/Sierra/issues/1)

The screenshots of Sierra were made and tested using a default Vi IMproved 7.4 in [iTerm 3](https://www.iterm2.com) and the Vi IMproved 7.4 in the GUI MacVim app. Extended syntax for JavaScript provided by Jose Elera Campana's Plug-in [vim-javascript-syntax](https://github.com/jelera/vim-javascript-syntax). Enjoy!!

Related 
-------
Sierra is a derivative of Hans Fugal's [Desert](https://github.com/fugalh/desert.vim). 'Statements', 'Functions', and 'Variables' are colored in cooler hues while 'Constants', 'String', and 'Booleans' are set to warmer reds. 

Please note that sierra is still brand new and I'm certain it will evolve over time. I'd love to hear from you guys if you have any feedback, suggestions or issues that you encounter. Just open an Issue ticket for any bugs or suggestions; and if sierra made your day, please leave a star! Also, if you like Sierra you might want to check out my other Vim theme [Alduin](https://github.com/AlessandroYorba/Alduin)
