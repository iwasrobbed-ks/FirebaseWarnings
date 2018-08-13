## Firebase Warnings

### Versions

Firebase (5.5.0) and Google-Mobile-Ads (7.31.0)

Following discussion here: https://github.com/firebase/firebase-ios-sdk/issues/196#issuecomment-403566692

### Reproduction steps:

1. Clone this repo
2. Open `FirebaseWarnings.xcworkspace` with Xcode 9.4.1 or 9.3.x
3. Choose `Generic iOS Device` next to the scheme dropdown
4. On the menu, run `Product` --> `Archive`
5. View the build logs and notice ~133 warnings that look like the below

```
Showing All Issues
ld: warning: Linker asked to preserve internal global: 'sharedInstance.sharedInstance'
ld: warning: Linker asked to preserve internal global: '__block_descriptor_tmp'
ld: warning: Linker asked to preserve internal global: '__block_literal_global'
``
