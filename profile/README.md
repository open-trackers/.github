# Welcome to the _Open Trackers Project_!

The _Open Trackers Project_ is part of the [_OpenAlloc_](https://github.com/openalloc/) family of applications and re-useable libraries.

## Applications

At present, _Open Trackers_ offers three apps sharing a common code base.

* [_Gym Routine Tracker_](https://open-trackers.github.io/grt/) - minimalist workout tracker

* [_Daily Calorie Tracker_](https://open-trackers.github.io/dct/) - minimalist calorie tracker

* [_Task Routine Tracker_](https://open-trackers.github.io/trt/) - minimal & focused task runner

These are available on the App Store as **free** downloads for the Apple Watch, iPhone, and iPad.

## Your Participation is Essential

As an open source project, we depend on our community of users (and eventually developers) for support.

**The most important thing you can do now is to rate and review the apps in the App Store. Preferably favorably! :)**

(This will help to broaden the base of users, to find bugs and improve the apps.)

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

* Data mobility, where the user can conveniently export their data for review.

## Boring Implementation Details

* Leverages the Apple platform (SwiftUI, CloudKit, Core Data, Shortcuts, etc.) to provide sophisticated capabilities with minimal code.

* Each platform version uses native conventions where feasible. (e.g., iOS version uses group boxes)
  
* Use standard SwiftUI controls, where available.

* Refactor projects to share code, both to ease maintenance and facilitate the development of new tracker apps. (Don't repeat yourself.)

* Data and business logic should be backed by unit tests.

## XCode Setup

See the [Workspace](https://github.com/open-trackers/Workspace) repository for a handy Xcode workspace that contains most of the repositories.

## See also

* [_OpenAlloc_](https://openalloc.github.io/) - main product website

* [OpenAlloc Project](https://github.com/openalloc/) - re-useable Swift libraries
* [Open Portfolio Project](https://github.com/open-portfolio/) - investing apps for macOS
* [Open Trackers Project](https://github.com/open-trackers/) - fitness, nutrition, and productivity apps for iPhone, iPad, and Apple Watch

## License

Copyright 2021, 2022, 2023 OpenAlloc LLC

All application code is licensed under the [Mozilla Public License 2](https://www.mozilla.org/en-US/MPL/2.0/), except where noted in individual modules.

Copyright is held by [@reedes](https://github.com/reedes)’s OpenAlloc LLC, except where noted in individual modules.

## Contributing

Contributions are welcome. You are encouraged to submit pull requests to fix bugs, improve documentation, or offer new features. 

The pull request need not be a production-ready feature or fix. It can be a draft of proposed changes, or simply a test to show that expected behavior is buggy. Discussion on the pull request can proceed from there.

Contributions should ultimately have adequate test coverage. See tests for current entities to see what coverage is expected.

Your contributions can be under the your name or organization, but must have a compatible license, preferably MPL-2.0 (for app code) or Apache-2.0 (for re-usable library code).

(This should probably be expanded to a proper policy.)

