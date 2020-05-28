# ConfettiView

A SwiftUI View that emits confetti with user-defined shapes, images, and text.

<img src="https://github.com/ziligy/ConfettiView/blob/master/docs/assets/example.gif" alt="SwiftUI ConfettiView by ziligy" width="319" height="690" align="right">

## Installation
*ConfettiView is available  through `Swift Package Manager`*

- In Xcode choose `File -> Swift Packages -> Add Package Dependency...`
- Paste this Github URL (https://github.com/ziligy/ConfettiView ) into the search bar. 
- Select the ConfettiView repo from the search results, and click Finish.


## Simple Use
```swift
import SwiftUI
import ConfettiView

struct ContentView: View {

    let confettiView = ConfettiView( confetti: [
                .text("🎉"),
                .text("💪"),
                .shape(.circle),
                .shape(.triangle),
            ])

    var body: some View {
        confettiView
    }
}

```

## Example
*see included example for:*
 - timed-celebration
 - fade out
 - including images

## Attributions
*inspiration and code influences*
- [NSHipster](https://github.com/NSHipster/ConfettiView)
- [ArthurGuibert](https://github.com/ArthurGuibert/SwiftUI-Particles)

