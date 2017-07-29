# OSX Setup

## Applications

**Image processing**
- Adobe Photoshop CC 2017
- ImageOptim

**Messaging**
- LINE
- Messages
- Skype
- Slack
- Viber

**Office**
- Pages
- Keynote
- Numbers
- Mail
- OneDrive

**Media**
- iTunes
- Spotify
- VLC

**General tools**
- LastPass

**System apps and peripheral software**
- CCleaner
- Logitech Options
- Spectacle

**Web browsers**
- Chrome
- Firefox

**Developer tools**
- Dash
- Postman
- Visual Studio Code

## Ruby on Rails

### Ruby
```
Install Homebrew:
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Install Ruby 2.4.0:
brew install ruby
```

### Ruby Version Manager - RVM
```
Install GPG keys:
gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB

Installing stable release version:
\curl -sSL https://get.rvm.io | bash -s stable

Usage:
rvm reload
rvm list known

Install a version of Ruby (e.g.: 2.1): 
rvm install 2.1

Use newly installed version:
rvm use 2.1

Verify current version:
ruby -v
which ruby
```

### Rails
```
Install Rails:
gem install rails -v 5.1.1

Verify Rails installation:
rails -v
```

## Node
Download 'Current' version with latest features installer [here](https://nodejs.org/en/)
```
Update npm:
npm install npm@latest -g

Verify (should be later higher than 2.1.8):
npm -v

To update npm:
npm i -g npm
```

## OSX configuration

| Description   | Config        |
| ------------- | ------------- |
| col 3 is      | right-aligned |
| col 2 is      | centered      |
| zebra stripes | are neat      |

## Other tasks