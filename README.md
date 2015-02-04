# Di55ect-GitHub

Presentation materials for Di55ect: GitHub for Designers

### About Di55ect
Di55ect is a series of events that explore the art and technology behind the [25x52](http://25x52.com) initiative. Check out [http://25x52.com/di55ect](http://25x52.com/di55ect) to learn more and to sign up for upcoming events.

### Pre-work Setup
* If you don’t yet have one, [create a GitHub account](https://github.com)
* If you don’t already have a text editor or IDE installed, [install GitHub's Atom editor](https://atom.io) (optional: Preferences > Install autocomplete plus, autoclose html)
* Download & install (or upgrade) [Xcode command line tools](https://developer.apple.com/downloads/index.action). For Yosemite (OS X 10.10+), [follow these instructions](http://railsapps.github.io/xcode-command-line-tools.html) (Scroll down a bit to the section "MacOS Yosemite.” You'll need to create a Mac Developer account if you don't already have one.)
* Install Git using [Homebrew](http://brew.sh). Watch this brief video for installation instructions: http://vimeo.com/14649488
* Set up GitHub SSH key: https://help.github.com/articles/generating-ssh-keys/
* Cache GitHub password https://help.github.com/articles/caching-your-github-password-in-git/ (optional)

### Questions/Tips

**I'm in a weird window that says "Please enter the commit message for your changes." - HELP!**
This probably happened because you typed "git commit" and return. Start by typing "i" to insert. Type in a message describing your commit. When you're done:

* press Esc
* type :x and press ENTER.

This should get you back to the terminal where you should see the message you just typed in along with some other information about your commit.

**How can I open a file to edit from Terminal?**
If you're using Atom as your text editor just type: atom < filename >
For Sublime Text users, follow along this [guide](https://gist.github.com/artero/1236170).
