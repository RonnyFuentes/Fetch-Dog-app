# CIS422Proj2

# Fetch: The Tinder for Doggy Playdates


The purpose of this app is to act as the Tinder for doggy playdates. Owners will download Fetch, make a profile, and from there, go through various doggy profiles to find the perfect match for their own beloved pup to play with, whenever and wherever.

Owners will fill out mandatory fields, such as name, and breed, and optional fields such as age, and personality (more to come). A user will swipe through a deck to confirm or reject a dog to receive a matches. After a match has been confirmed by both sides, the owner(s) can contact the other to set up a playdate. 

Note: The camera functionality within the profile view works. However, in order to view and the test it, you must run the app from a device rather than a simulator within Xcode. 


## Technologies


* Swift/SwiftUI

* Firebase

* UIKit 



## Requirements


* Xcode 12.4

* iOS 14.4+

* CocoaPods

## Installation


#### Xcode 12.4 (mac)


This environment must be installed in order to run Fetch. The download can be found at [Xcode 12](https://developer.apple.com/xcode/)


#### iOS 14.4+


This application has not yet been deployed, but devices must be on version 14.4+ at the minimum in order to run this app.


#### CocoaPods


The Fetch project relies on dependencies through a Podfile. Therefore, CocoaPods must be installed on your local machine, which can be found at [CocoaPods](https://cocoapods.org). 


Pull the repo:
```
"git pull "https://github.com/RonnyFuentes/Fetch-Dog-app.git"
```

After the Fetch project is pulled, and CocoaPods is installed, open `terminal` and navigate to where the `Fetch` folder is located. Go into the Fetch folder and run:
```
pod deintegrate
pod install 
``` 

A list of Firebase dependacies should begin to install. 


While still in the Fetch folder (in terminal) run:
`open Fetch.xcworkspace`

This should open the workspace file in Xcode.

Note: A warning on the left panel will appear
```
click "update to recommended settings"
click "Perform Changes"
close Xcode
run: open Fetch.xcworkspace
```

#### Running The Simulator  
`Xcode > Product > Run`

