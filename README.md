twitter.app hidden features
===========================

List of commands to enable hidden features in **Twitter App for Mac**.

Close `Twitter.app` and Open `Terminal` to enter commands.

##Commands

- Prevent repeating avatars on a user profile timeline:

        defaults write com.twitter.twitter-mac UserTimelineDerepeater -bool true
- Scroll over window will bring to front:
        
        defaults write com.twitter.twitter-mac ScrollingMakesKeyAndOrdersFront -bool true