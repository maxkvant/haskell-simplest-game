### A very simple game in haskell

The goal of this game is to get to `x`.
But one loses if he/she goes to `o`. 



### Prepare

This lines should install install dendencies

```bash
curl -sSL https://get.haskellstack.org/ | sh
sudo apt install ncurses-dev libncurses5-dev libncursesw5-dev

stack install mtl
stack install vector
stack install ncurses
stack install exceptions
```

### Run

```bash
stack repl --package mtl --package ncurses --package vector --package exceptions
```
