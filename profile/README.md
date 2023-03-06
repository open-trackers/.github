The _Open Trackers_ project presently consists of two applications and
their dependent packages:

[_Gym Routine Tracker_](https://open-trackers.github.io/grt/)

[_Daily Calorie Tracker_](https://open-trackers.github.io/dct/)

(Both are available on the App Store as free downloads for the Apple
Watch, iPhone, and iPad.)

## Design Principles

The apps in the _Open Trackers_ family are opinionated and share a set of
principles:

* A watch-first focus, to encourage an active lifestyle with wearable apps
  independent of larger devices. (Leave your phone at home!)

* Convenient and quick interactions, minimizing screen time.

* Focus on the common needs of the basic user -- do not try to be
  everything to everyone. 

* Avoid cluttering the interface by either limiting features or ‘hiding’
  them. (e.g., in GRT, long press the ‘Done’ button to advance intensity.)

* Offload ‘heavy’ features, such as long-term storage and visualization,
  to larger devices.

## Implementation Details

* Leverages the Apple platform (SwiftUI, CloudKit, Core Data, Shortcuts,
  etc.) to provide sophisticated capabilities with minimal code.

* Each platform version uses native conventions where feasible. (e.g., iOS
  version uses group boxes)

* Refactor projects to share code, both to ease maintenance and facilitate
  the development of new tracker apps.

## Shared Features

* Open-source with free and weak ‘copy-left’ licensing (MPL-2.0) to
  encourage long-term community development and support.

* Free to download from the App Store. As this is expected to be
  a community effort, there are no ads, IAPs, or subscriptions.

* Respect for the user’s privacy (see the
  [policy](https://open-trackers.github.io/privacy/)).

* Data mobility, where the user can conveniently export their data for
  review.

## Participation

**The most important thing everyone can do now is to rate and review the
apps in the App Store. Preferably favorably! :)**

Future tracker apps might be possible, should good ideas emerge.

To report a bug or suggest a feature, see the ‘Issues’ for project.

## Contributions

The code is licensed with MPL-2.0 and where the copyright is held by
[@reedes](https://github.com/reedes)’s OpenAlloc LLC. 

Contributions can be under the developer’s name or organization, but must
have a compatible license, preferably MPL-2.0.

(This should probably be expanded to a proper policy.)

