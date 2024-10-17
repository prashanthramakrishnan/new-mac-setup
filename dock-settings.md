# Dock and Launchpad

> I like the dock to be at the bottom of the screen, always displayed (I'm not the one who likes it on the side). The programs on my dock usually are Finder, 
> Safari (Browser of choice for browsing) - I use Choosy to appropriately launch the browser of choice and can recommend this tool.  
> [Chrome (Browser of choice for development)  ](https://www.google.com/intl/en_pk/chrome/)
> [Android Studio](https://developer.android.com/studio)  
> [Xcode](https://developer.apple.com/xcode/) I use xcodes to switch between multiple versions  
> IntelliJ (my development IDE of choice)  
> [Zoom](https://zoom.us/download?os=mac)
> [Sourcetree (I switch between using git on terminal and the UI, but sourcetree is my GUI of choice)](https://blog.sourcetreeapp.com/2014/09/25/sourcetree-for-mac-2-0-released/)
> [Sublime Text](https://www.sublimetext.com/3)  

System Preferences -> Dock

## Size
> I prefer the dock to be small with Magnification off  
> Position on screen - Bottom  
> Minimise windows using - Genie effect  
> Turn off Automatically hide and show the Dock  
> Turn off Stage Manager (not a big fan of it)  
> Turn off Hot Corners (this annoys the hell out of me if it is on)  
> Turn off Show suggested and recent apps in Dock

Make the animations faster - copy/paste and run the below command on your terminal

```text
defaults write com.apple.dock autohide-time-modifier -float 0.3 && killall Dock
defaults write com.apple.dock autohide-delay -int 0 && killall Dock
```
By default, launchpad icons are big and take up a lot of screen space with 7 rows and 5 columns. I change this to 12 and 8.  
Run the following command in the terminal to set it.

```text
defaults write com.apple.dock springboard-columns -int 12
defaults write com.apple.dock springboard-rows -int 8
killall Dock
```

[My wallpaper of choice - Cosmic Cliffs in the Carina Nebula](https://webbtelescope.org/contents/media/images/2022/031/01G77PKB8NKR7S8Z6HBXMYATGJ?news=true)