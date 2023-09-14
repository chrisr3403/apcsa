# java

## Instructions
1. In your terminal, do `git clone git@github.com:hstatsep/apcsa.git` to clone this repository
2. In your terminal, do `cd apcsa` to get into the `apcsa` folder
3. In your terminal, do `rm -rf .git` to "turn off" git in this folder.

## Template

* Open `Template.java`
* Do NOT edit the file. Just look at it!

_Note: your filename MUST match the class name._
_Naming convention: FirstLetterOfEveryWordCapitalized.java_

## Hello World
```
cd u00-other
mkdir HelloWorld
cd HelloWorld
touch Hello.java
```
* Open `Hello.java` and paste in the same code from your template (but update the class name to `Hello`). Then run the following commands:
* `javac Hello.java`
* `java Hello`
* You should see `Hello World` in your terminal

* As a general rule of thumb, use this same format when making new programs (`cd` into the correct directory, make a folder with the appropriate name, `cd` into it, then name your file `WhateverYouWant.java` which will then get compiled to `WhateverYouWant.class`). We make an entire folder because sometimes we will have multiple Java files that relate to each other, so this helps keep them organized.
  * As a shortcut, you can copy with the `cp source destination` command. I.e. once you make your `HelloWorld` directory and `cd` into it, you could do `cp /workspaces/apcsa/Template.java ./WhateverYouWant.java`

## Java compile and run
#### Setting this up allows you to compile and run in the same command
`nano ~/.bash_profile`  
Paste the following:  
`jcar() { javac $1.java && java $1 ; }`  
Do <kbd>control</kbd>+<kbd>X</kbd> to quit, <kbd>Y</kbd> to save, then press <kbd>ENTER</kbd>

To see the command take effect, you must **reload your IDE**.
#### To use, type `jcar Program` (using your own Java program file, but with no `.java`)
* Try this out by adding `!` to your **Hello World** program so that it outputs `Hello World!`
* Run the shortcut by doing `jcar Hello`

## Git alias commands
* Copy/paste the following into the terminal.
```
echo "" >> ~/.bash_profile
echo "alias gp=\"git add ." >> ~/.bash_profile
echo "git commit -m 'update repo'" >> ~/.bash_profile
echo "git push\"" >> ~/.bash_profile
echo

```
* If you still see the last command in your terminal, press <kbd>ENTER</kbd>
* Close the terminal and open a new one
* In the future, you can simply type `gp` to automatically add/commit/push all updated files in a repo
* You can continue to use `git add filename` if you would like to be more selective, and/or `git commit -m "message"` if you would like to be more specific
