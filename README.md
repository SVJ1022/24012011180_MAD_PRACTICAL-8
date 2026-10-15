# 24012011180_MAD_PRACTICAL-8
# 🍎 Practical-8 — Hello World iOS App Using SwiftUI

## 🎯 Aim

Create your first **Hello World iOS application using SwiftUI**.

## 📌 Practical Overview

This practical introduces the process of creating a basic iOS application in Xcode using SwiftUI and Swift. The application displays the text **“Hello, world!”** on the screen.

## 🛠️ Project Setup

1. Open Xcode and select **File → New → Project**.
2. Under the iOS tab, select the **App** template.
3. Set the application name to `hello_world`.
4. Select **SwiftUI** as the interface technology.
5. Select **Swift** as the programming language.
6. Leave Core Data and unit testing options unselected, as described in the practical.
7. Select **Create Git repository on my Mac** and save the project.

## 🧩 Understanding the App Structure

The basic SwiftUI project contains two important source files.

### `hello_worldApp.swift`

This file defines the app's main entry point and scene. It uses `WindowGroup` to display `ContentView`.

```swift
import SwiftUI

@main
struct hello_worldApp: App {
    var body: some Scene {
        WindowGroup {
            ContentView()
        }
    }
}
```

### `ContentView.swift`

This file defines the main view shown by the application. The `Text` view displays the greeting, and `.padding()` adds space around it.

```swift
import SwiftUI

struct ContentView: View {
    var body: some View {
        Text("Hello, world!")
            .padding()
    }
}
```

## ▶️ Run the Application

1. Choose an iOS simulator from the simulator menu in Xcode.
2. Click the **Run** (▶) button at the top of the Xcode project window.
3. Wait for the project to build and launch in the selected simulator.
4. Confirm that **“Hello, world!”** appears on the screen.

## 👀 SwiftUI Preview

SwiftUI also provides a preview of the view without launching the full application in a simulator. The preview updates to reflect changes made to the view's code.

```swift
struct ContentView_Previews: PreviewProvider {
    static var previews: some View {
        ContentView()
    }
}
```

## 🧠 Concepts Covered

- iOS application project creation in Xcode
- Swift programming language
- SwiftUI
- `App` protocol and `@main`
- `Scene` and `WindowGroup`
- `View` protocol
- `Text` view
- `.padding()` modifier
- iOS Simulator
- SwiftUI Preview
- Git repository initialization

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Swift | Programming language |
| SwiftUI | Building the user interface |
| Xcode | iOS development environment |
| iOS Simulator | Running and testing the app |
| Git | Version control |

## 📂 Project Structure

```text
hello_world
├── hello_worldApp.swift
├── ContentView.swift
└── Assets.xcassets
```

*The exact project files and folders may vary depending on the Xcode version and project configuration.*


## ✅ Result

A basic iOS application was created using Swift and SwiftUI. The application displays **“Hello, world!”** and can be run using the iOS Simulator or previewed directly in Xcode.

---

**Subject:** Mobile Application Development (MAD)  
**Practical:** 8  
**Topic:** First Hello World iOS App Using SwiftUI  
**Language:** Swift  
**Development Environment:** Xcode
