<h1 align="center">Chatter - Building a Flutter Chat Application From Scratch</h1>

<p align="center">
    <a href="https://pub.dev/packages/stream_feed_flutter_core"><img src="https://img.shields.io/pub/v/stream_feed_flutter_core?include_prereleases" alt="Pub"></a>
    <a href="https://pub.dev/packages/flutter_lints"><img src="https://img.shields.io/badge/style-flutter__lints-blue" alt="style: flutter lints"></a>
    <a href="https://github.com/GetStream/flutter-samples"><img src="https://img.shields.io/badge/flutter-samples-teal.svg?longCache=true" alt="Flutter Samples"></a>
    <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
    <a href="https://getstream.io/"><img src="https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/HayesGordon/e7f3c4587859c17f3e593fd3ff5b13f4/raw/11d9d9385c9f34374ede25f6471dc743b977a914/badge.json" alt="Stream Feeds"></a>
</p>

<p align="center">  
Chatter is a demo application showing how to create a chat app from scratch using <a href="https://flutter.dev/">Flutter</a> and the <a href="https://pub.dev/packages/stream_chat_flutter_core/">Stream Chat Flutter Core package</a>.
</br>

<p align="center">
<img src="https://user-images.githubusercontent.com/13705472/160611526-5caf7e95-4377-4798-881b-7a6c6e932c6b.gif" />
</p>

## Where To Start
If you're new to Stream Chat Flutter, we recommend taking a look at the official tutorial: https://getstream.io/chat/flutter/tutorial/

Or take a look at the tutorial videos: [Chatter YouTube series playlist](https://www.youtube.com/watch?v=vgqBc7jni8c&list=PLNBhvhkAJG6sH7dkmwt4BiCclFkMoXq4r)

## Installation Instructions

```bash
git clone https://github.com/HayesGordon/chatter.git
```

Check out the required branch

```bash
git checkout {branch-name}
```

Install dependencies
```bash
flutter pub get
```

Generate the needed platform folders (Android, iOS). Some of the branches may have these already included.

```bash
flutter create .
```

## Further Setup

Add your Stream app's key in `lib/app.dart`.

In the [third tutorial](https://github.com/HayesGordon/chatter/tree/tutorial-003-firebase-authentication) the application requires Firebase Authentication and Cloud Functions to be setup. From the [fourth tutorial](https://github.com/HayesGordon/chatter/tree/tutorial-004-version-four-and-firebase-extensions) this is even easier with [Stream's Firebase Extensions](https://getstream.io/blog/stream-firebase-extensions/), see the [video](https://youtu.be/Dt_taxX98sg) for more information.

## Episodes / Tutorials

![Episode 1 - Design/UI](https://user-images.githubusercontent.com/13705472/133966143-57658323-8de3-4060-b4cc-343c8c17cda1.jpg)

**Episode 01 - Design/UI** \[ [Video](https://youtu.be/vgqBc7jni8c) \] \[ [Entry Code](https://github.com/HayesGordon/chatter/tree/tutorial-001-base-ui) \] \[ [Completed Code](https://github.com/HayesGordon/chatter/tree/tutorial-001-base-ui-complete) \] - Create the UI and structure for the application.

![Episode 02 - Stream API](https://user-images.githubusercontent.com/13705472/133966035-96604a21-0625-4114-a76d-bb938c72493f.jpg)

**Episode 02 - Stream API** \[ [Video](https://youtu.be/-s5iU9D5-AI) \] \[ [Entry Code](https://github.com/HayesGordon/chatter/tree/tutorial-002-stream-chat-flutter-core) \] \[ [Completed Code](https://github.com/HayesGordon/chatter/tree/tutorial-002-stream-chat-flutter-core-complete) \] - Connect to the Stream API with basic chat functionality

![Episode 03 - Firebase Auth and Functions](https://user-images.githubusercontent.com/13705472/142461222-6df1c049-b265-4d6c-ab2c-81540ccc6904.jpg)

**Episode 03 - Firebase Auth and Functions** \[ [Video](https://youtu.be/y6OlrO3Bzag) \] \[ [Entry Code](https://github.com/HayesGordon/chatter/tree/tutorial-003-firebase-authentication) \] \[ [Completed Code](https://github.com/HayesGordon/chatter/tree/tutorial-003-firebase-authentication-complete) \] - Use Firebase Authentication and Cloud Function to generate Stream API user tokens

![Episode 04 - Migrate Version 4 & Stream Firebase Extensions](https://user-images.githubusercontent.com/13705472/180415364-35520085-cff0-4139-8672-f60e089b3c6a.jpg)

**Episode 04 - Migrate Version 4 & Stream Firebase Extensions** \[ [Video](https://youtu.be/Dt_taxX98sg) \] \[ [Entry Code](https://github.com/HayesGordon/chatter/tree/tutorial-004-version-four-and-firebase-extensions) \] \[ [Completed Code](https://github.com/HayesGordon/chatter/tree/tutorial-004-version-four-and-firebase-extensions) \] - Make use of Stream's Firebase Extensions to simplify authentication and migrate to V4 of the [Stream Chat Flutter Core](https://pub.dev/packages/stream_chat_flutter_core) SDK.
