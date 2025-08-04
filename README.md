# cmake-repl

Fork of a repo just doucmenting this:

I don't understand cmake  
best way to learn is with a REPL  

Shamelessly stolen from [this guy](https://gist.github.com/DanielG/707163)

## additional notes 
### installation
The script seems to be meant for unixiod system. I got it running on a debian installation in wsl in win 11:

1. install wsl and a linux distro of your choice
2. install node (installed a 22 version)
3. install cmake (the error if not installed will be quite a bit unclear)
4. run node main.js (no npm action necessary for me)

### notes on usage
The repl hard only limited use for me however:  unlike a proper repl I could not see  any kind of context retention, i.e. every line is interpreted on its own. Since I found no quick and easy way to  put multiple commands into one line I could not really experiment with variables or anything.

Just creating a file with the features one wants to try and running them with `cmake -P` seems more useful to me.

### security warning

Be aware that if you try this you are running some basically undocumented, unchecked scripts. While I found nothing suspicious, I cannot and do nothing harmful.

