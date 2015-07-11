# whenchanged
A shell script to execute commands when something is changed.

## Example
Let's suppose we have a script to run the tests called `runtests.sh`. 

We can use it to watch for changes in the current directory and run the tests when that happen: 

`./whenchanged . ./runtests.sh`
