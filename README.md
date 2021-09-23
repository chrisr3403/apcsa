# java

## Instructions
1. In your terminal, do `git clone git@github.com:hstatsep/java.git` to clone this repository
2. In your terminal, do `cd java` to get into the `java` folder
3. In your terminal, do `rm -rf .git` to "turn off" git in this folder.


## Git alias commands
* Copy/paste the following into the terminal.
```
echo "" >> ~/.bash_profile
echo "alias gp=\"git add ." >> ~/.bash_profile
echo "git commit -m 'update repo'" >> ~/.bash_profile
echo "git push\"" >> ~/.bash_profile

```
* If you still see the last command in your terminal, press <kbd>ENTER</kbd>
* Close the terminal and open a new one
* In the future, you can simply type `gp` to automatically add/commit/push all updated files in a repo
* You can continue to use `git add filename` if you would like to be more selective, and/or `git commit -m "message"` if you would like to be more specific

