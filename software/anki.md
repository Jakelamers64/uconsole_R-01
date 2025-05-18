# How to install anki on uconsole R-01 

## Useful links
- https://github.com/ankitects/anki/blob/ab20f215b14bf301aa523e9d031a7bc305848fe4/docs/linux.md
- 

## What I have done so far
- Install glibc
  - command: sudo apt install glibc-source -y
- Ensure all the following packages are installed
  - command: sudo apt install bash grep findutils curl gcc g++ git rsync
- Installing rust and N2
  - command: curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
  - command: sudo apt install ninja-build 
