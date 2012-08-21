twitter.app hidden features
===========================

List of commands to enable hidden features in **Twitter App for Mac**.

Close `Twitter.app` and open `Terminal` to enter commands.

##Commands

- Prevent repeating avatars on a user profile timeline:

        defaults write com.twitter.twitter-mac UserTimelineDerepeater -bool true
        
- Scroll over window will bring to front:
        
        defaults write com.twitter.twitter-mac ScrollingMakesKeyAndOrdersFront -bool true

- Type anywhere to automatically start a new tweet:

        defaults write com.twitter.twitter-mac TypeAnywhereToTweet -bool true
        
- Hide application in background:

        defaults write com.twitter.twitter-mac HideInBackground -bool true
        
- Compose window float over all windows:

        defaults write com.twitter.twitter-mac NormalComposeWindowLevel -bool false
        
- ESC closes compose window:

        defaults write com.twitter.twitter-mac ESCClosesComposeWindow -bool true