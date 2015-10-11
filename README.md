# OS X Guide for Power Users

## Command-line Interface

- OS X, being Unix-based, has a bash shell, accessible via the Terminal app
    - I recommend switching to the “Pro” theme (`Terminal > Preference > Profiles`)
    - You can even setup a `~/.bash_profile` (equivalent of `.bashrc`)
- The file system is also very similar to Ubuntu

## Package Manager

- OS X doesn't come with a package manager
- Install [Homebrew](http://brew.sh/) via the one-line Terminal command 🍺
    - OS X comes with Ruby (and Python btw), so don’t worry about the `ruby` command
    - However, you do need the “Command Line Tools for Xcode”:
        - On OS X 10.9 and up, you can do: `xcode-select --install`
    - If you’ve already installed another package manager (e.g. MacPorts) then do not mix them
- Example of usage:
```
brew update
brew upgrade
brew info git
brew install git
```
- Unlike Ubuntu's apt-get, **never use sudo** with Homebrew
- Refer to the [FAQ](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/FAQ.md) for more details
- For even more command line goodness, check out Homebrew [Cask](http://caskroom.io/) as well

## Installing Third-Party Apps

- By default, OS X only allows installation of apps from the official App Store
- There are two more options, under `System Preferences > Security & Privacy > General`
- I have mine set up to “Mac App Store and Identified Developers"
- If it still doesn’t let you install something, *temporarily* set it to “Anywhere”, finish installation, run the app once, and then set it back to a more conservative option.

## Recommended Apps (free)

- These are in addition to the obvious apps, like Skype, Dropbox, etc.
- [Sublime Text](http://www.sublimetext.com/3) or some other full-featured and hackable text editor.
    - [Atom](https://atom.io/) from Github is brand new, modern, and very popular.
    - Of course, you can also use [Vim](http://www.vim.org/) or [Emacs](http://emacsformacosx.com/), which you can install via Homebrew.
- [VLC Media Player](https://www.videolan.org/vlc/) because Quick Time doesn’t like some video codecs
- [XtraFinder](http://www.trankynam.com/xtrafinder/) adds a bunch of features that OS X’s Finder (directory browser) lacks
- [TheUnarchiver](https://itunes.apple.com/us/app/the-unarchiver/id425424353?mt=12) or [UnRarX](http://www.unrarx.com/) because there’s always that one person that sends you `.rar` or password-protected archives
- [SmartGit](http://www.syntevo.com/smartgit/) if you prefer to manage Git repos via a GUI as opposed to the command line
- [gfxCardStatus](https://gfx.io/) if you have a Macbook Pro with two GPUs (integrated and discrete)
- In my opinion “Preview”, which comes with OS X, is far superior to Adobe Reader and even has some Acrobat Pro features. So I don’t think you have to worry about getting a new PDF viewer.

### LaTeX

- LaTeX deserves its own subsection 😁
- Install the [MacTex](https://www.tug.org/mactex/) distribution (essentially TeX Live)
    - I think this comes with a bunch of handy utilities like BibDesk (bibliography editor)
- Then download an editor. I like [TeXShop](http://pages.uoregon.edu/koch/texshop/obtaining.html) (free).
    - There are fancier editors on the App Store 💰

## Keyboard Shortcuts

- Coming soon!
