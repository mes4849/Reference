# Reference #
A repo to host all my programming

## Linux ##
**Vi / Vim**  
Making the backspace erase characters in insert mode and having the arrow keys not insert letters:  
- Add the following lines to `~/.vimrc`  
  ```
  set nocompatible
  set backspace=2
  ```  
Deleting lines:  
- Outside of insert mode, use one of the following commands  
  `dd`  
  or  
  `D`
