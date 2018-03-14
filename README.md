Android Video Player Sample
===========================

This sample shows how to implement a media app that allows
playback of video from local storage (assets folder in the APK)
or remote sources over HTTP(S).
1. It supports playlists, so that multiple videos can be strung
together to play one after the other, and skip between them.
2. It supports `MediaSession` so that external Bluetooth headphones
can control your media (play, pause, skip to next, etc), and see
what media is currently playing (like from a car's Bluetooth head
unit).
3. It supports Audio Focus, so that you can respect Android's 
audio focus system and pause playback if something else is playing.
4. It supports picture in picture (PIP) so that the app's video
playback can continue in a minimized window while the user is
in other apps.
To learn more about `ExoPlayer`, `MediaSession`, Audio Focus, and PIP, 
please read this series of [articles on Medium](https://goo.gl/HpTnka)
that goes into the details of these APIs.

Pre-requisites
--------------

- Android SDK 26
- Android Build Tools v26.0.1
- Android Support Repository

Getting Started
---------------

This sample uses the Gradle build system. To build this project, use the
"gradlew build" command or use "Import Project" in Android Studio.

Support
-------

- Google+ Community: https://plus.google.com/communities/105153134372062985968
- Stack Overflow: http://stackoverflow.com/questions/tagged/android

If you've found an error in this sample, please file an issue
on GitHub.

Patches are encouraged, and may be submitted by forking this project and
submitting a pull request through GitHub. Please see CONTRIBUTING.md for more details.

License
-------

Copyright 2018 The Android Open Source Project, Inc.

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.