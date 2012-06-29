## Install

### [TextMate Version 2.0 Alpha](http://blog.macromates.com/2011/locating-bundles/)

    mkdir -p ~/Library/Application\ Support/Avian/Bundles
    cd !$
    git clone git://github.com/b00y0h/Bobby.tmbundle.git

### TextMate Version 1.x

    cd ~/"Library/Application Support/TextMate/Bundles/"
    git clone git://github.com/b00y0h/Bobby.tmbundle.git
    osascript -e 'tell app "TextMate" to reload bundles'
  
### Set Project-wide variable

The way to do this is currently a little secret but if you deselect everything in the project drawer, then click the info (circled I) button, a panel will appear where you can set variables.

Create a variable called `MY_LOCALIZE` and set it to whatever you need.

(Original instructions stolen from the [GitHub Bundle](http://github.com/drnic/github-tmbundle/tree/master).)