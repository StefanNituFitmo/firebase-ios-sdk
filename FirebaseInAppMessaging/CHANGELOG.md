# 2020-07 -- v0.22.1
- [fixed] Fixed an inaccurate doc comment in `InAppMessagingDisplay` (#5972).

# 2020-07 -- v0.22.0
- [changed] Functionally neutral updated import references for dependencies. (#5902)
- [changed] Updated In-App Messaging to consume the Protobuf-less AB Testing SDK (#5890).

# 2020-06-02 -- v0.20.2
- [fixed] Fixed log message for in-app messaging test on device flow (#5680).

# 2020-05-19 -- v0.20.1
- [fixed] Fixed an issue where clicks were counted for messages with no action URL (#5564).

# 2020-04-21 -- v0.19.3
- [fixed] Fixed an issue where GoogleUtilities wasn't explicitly listed as a dependency (#5282).

# 2020-04-07 -- v0.19.2
- [fixed] Internal fixes for test apps (#5171).

# 2020-03-17 -- v0.19.1
- [fixed] Fixed display issue with banner messages on iPad Pro 11" (#4714).
- [fixed] Fixed 400 errors from backend due to a bug in the Instance ID SDK (#3887).
- [changed] Internal change in in-app message A/B test flow (#5078).

# 2020-03-10 -- v0.19.0
- [added] Added SDK support for A/B testing in-app messages.

# 2020-02-18 -- v0.17.0
- [added] Added support for data bundles for in-app messages. Data bundles are additional key-value pairs that can be sent along with an in-app message (#4922).

# 2020-01-28 -- v0.16.0
- [changed] Consolidated backend and UI SDKs under `FirebaseInAppMessaging`. Developers should now use `pod Firebase/InAppMessaging` in their Podfile.
- [changed] `FIRIAMDefaultDisplayImpl` is no longer public.
- [changed] `FirebaseInAppMessagingDisplay` is now deprecated and should be removed from developers' Podfiles.
- [changed] Minimum iOS version is now 9.0.

# 2019-12-17 -- v0.15.6
- [fixed] Issues with nullability in card message (#4435).
- [fixed] Unit test failure with OCMock 3.5.0 (#4420).
- [fixed] Crash in test on device error flow (#4446).

# 2019-10-08 -- v0.15.5
- [added] Added support for UIScene based application lifecycle (#3927).

# 2019-09-03 -- v0.15.4
- [fixed] Undeprecated initializer for FIRInAppMessagingAction so it can be used going forward in custom UI display (#3545).

# 2019-07-23 -- v0.15.2
- [fixed] Fixed issue with messages to be triggered on app launch (#3237).

# 2019-06-04 -- v0.15.0
- [added] Added support for card in-app messages (#2947).
- [added] Added direct triggering (via FIAM SDK) of in-app messages (#3081).

# 2019-05-21 -- v0.14.1
- [fixed] Fixed an issue with messages not showing up from custom analytics event trigger (#2981).
- [fixed] Fixed crash from sending analytics events with no instance ID (#2988).

# 2019-03-05 -- v0.13.0
- [added] Added a feature allowing developers to programmatically register a delegate for updates on in-app engagement (impression, click, display errors).

# 2018-09-25 -- v0.12.0
- [changed] Separated UI functionality into a new open source SDK called FirebaseInAppMessagingDisplay.
- [fixed] Respect fetch between wait time returned from API responses.

# 2018-08-15 -- v0.11.0
- First Beta Release.
