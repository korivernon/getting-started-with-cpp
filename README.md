# Getting Started With C++

This is going to be an installation guide for getting started with C++!

**Topics Covered**

1. [Installation](#install)
2. [Running Your Code](#runcode)

There are so many ways to C++ on your machine. C++ is different than Python in the sense that there may not always be a built in compiler inside of your code editor.

If you choose to use XCode or VSCode, you can run your code inside of your code editor. Or, you could use an external terminal to do so. C++ is compiled differently than a higher level programming language such as Python. This is a little difficult to grasp if your first language is Python, however, once you are comfortable with how to test your code, everything else comes very naturally *(that's pretty much the case with every programming language)*!

<a name="install"></a>

## Installation

Install the C++ compiler, gpp. 

First, I would install `brew`

Open your terminal, and copy and paste this. 

```out
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

After brew is installed, copy and past this into your terminal

```out
brew info gpp
brew install gpp
```
### Vim (unpopular but my favorite)

Vim is probably the least popular option, but it is my favorite. It's completely personalized and once you get over the learning curve, it's faster (in industry... probably not in class).

Open your terminal and copy and paste this line below:

```brew install vim```

***I would also install Ultimate vimrc because it makes vim more palatable.***

(Optional but recommended) If git is not installed, then use brew to install git. 

```brew install git```

Clone the vimrc files. 

```git clone https://github.com/amix/vimrc.git ~/.vim_runtime```

For more information on how to update the file and install other versions, visit [this](https://sourabhbajaj.com/mac-setup/Vim/README.html) website. 

### XCode (Mac OS)

If you are on Mac OS, you **have** to install XCode. 

If you want to use XCode (must be on Mac OS), click [here](https://apps.apple.com/us/app/xcode/id497799835?mt=12).

### VSCode

If you want to use VSCode (and you are on Mac), you first have to download XCode. Download XCode, and then Donwload VSCode. Otherwise, click [here](https://code.visualstudio.com/) to download VSCode and select your operating system.

<a name="runcode"></a>

## Running Your Code