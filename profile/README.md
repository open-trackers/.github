Welcome to the _Open Trackers_ project!

At present, this project features two apps:

* [_Gym Routine Tracker_](https://open-trackers.github.io/grt/) - minimalist workout tracker

* [_Daily Calorie Tracker_](https://open-trackers.github.io/dct/) - minimalist calorie tracker

Both are available on the App Store as **free** downloads for the Apple Watch, iPhone, and iPad.

## Your Participation is Essential!

**The most important thing you can do now is to rate and review the apps in the App Store. Preferably favorably! :)**

(This will help to broaden the base of users, to find bugs, as well as developers to help maintain and improve the apps.)

Future tracker apps to add to the family are certainly possible, should good ideas emerge.

To report a bug or suggest a feature, add an Issue to the relevant Github project.

## Design Principles

The apps in the _Open Trackers_ family share a set of design principles:

* A watch-first focus, to encourage an active lifestyle with wearable apps independent of larger devices. (Leave your phone at home!)

* Convenient and quick interactions, minimizing screen time.

* Focus on the common needs of the basic user -- do not try to be everything to everyone. 

* Avoid cluttering the interface either through: (1) ‘hiding’ advanced features, or (2) omitting them altogether. (e.g., in GRT, long press the ‘Done’ button to advance intensity.)

* Offload ‘heavy’ features, such as long-term storage and visualization, to larger devices.
  
## Features Ahoy!

* Open-source with clear licensing terms (MPL-2.0) to encourage long-term community development and support.

* Free to download from the App Store. As this is expected to be a community effort, the apps are free of ads, IAPs, and subscriptions. 

* Respect for the user’s privacy (see the [policy](https://open-trackers.github.io/privacy/)). TL;DR: there is no data collection or remote tracking.

* Data mobility, where the user can conveniently export their data for
  review.

## Boring Implementation Details

* Leverages the Apple platform (SwiftUI, CloudKit, Core Data, Shortcuts, etc.) to provide sophisticated capabilities with minimal code.

* Each platform version uses native conventions where feasible. (e.g., iOS version uses group boxes)
  
* Use standard SwiftUI controls, where available.

* Refactor projects to share code, both to ease maintenance and facilitate the development of new tracker apps. (Don't repeat yourself.)

## Contributions

The code is licensed with MPL-2.0 and where the copyright is held by [@reedes](https://github.com/reedes)’s OpenAlloc LLC. 

Your contributions can be under the your name or organization, but must have a compatible license, preferably MPL-2.0.

(This should probably be expanded to a proper policy.)

