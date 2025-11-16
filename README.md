SwiftPlayfulMicroInteractionsApp

![SwiftUI_Playful_Interactions](https://github.com/user-attachments/assets/b3ea51d3-d30b-4e86-ba4b-605f96ee8442)

🚀 What This Project Is

This is a SwiftUI playground showcasing seven small, delightful interactions that can elevate user experience. These micro-interactions are inspired by and explained in my Medium article, and here you can see and use the actual code.



The interactions include:

Bouncy Button — button with spring bounce on tap 
Medium

Wiggly Toggle — toggle that “wiggles” when changed 
Medium

Breathing Floating Action Button (FAB) — a button that gently scales in and out 
Medium

Typing Indicator — animated dots like chat “…” typing 
Medium

Confetti Celebration — confetti burst for celebrating an action 
Medium

Liquid Progress Bar — a wavy / sloshing progress bar 
Medium

Light/Dark Theatrical Toggle — a sun/moon toggle with rotation 
Medium



📁 Project Structure

Here’s an overview of how the repository is organized:

<img width="423" height="261" alt="Screenshot 2025-11-17 at 3 23 36 AM" src="https://github.com/user-attachments/assets/1d63fa2b-ab2b-4ec8-8e2e-986618ce89ea" />


🛠️ How to Run This

Clone the repository

git clone https://github.com/gauravtakdev/SwiftPlayfulMicroInteractionsApp.git  
cd SwiftPlayfulMicroInteractionsApp  


Open in Xcode

open SwiftPlayfulMicroInteractionsApp.xcodeproj  


Run

Select a simulator (or a physical device)

Build and run the app

Navigate through the list to try each interaction module

🧭 How to Use / Extend

Explore each demo
Try each interaction to understand how it works, and tweak the parameters (animation duration, scale, etc.) to get a feel for them.

Add your own interactions

Create a new SwiftUI view for your custom micro-interaction.

Add a NavigationLink or button in the main view so it's accessible.

Use animation APIs like withAnimation, AnimatableModifier, TimelineView, etc.

Keep things modular so it's easy to copy into other projects.

Extract into a Swift Package
If some interactions are especially reusable, you can turn parts of this repo into a Swift Package, making it easier to use in your production apps.

📖 About the Blog

The code here is directly aligned with my Medium article: Bring Your SwiftUI Apps to Life: 7 Playful Micro-Interactions… 
Medium
+1

In the blog, I explain:

Why each interaction matters

How to implement them in SwiftUI

The design/UX reasoning behind each

Code snippets for each interaction

If you like to understand not just how but why these interactions work, I strongly recommend reading the article along with exploring this project.

✅ Contributing

Contributions are very welcome! If you want to:

Add a new micro-interaction demo

Improve or refactor existing ones

Add unit tests, performance optimizations

Improve documentation or README

… feel free to:

Fork the repo

Create a feature branch (feature/my-cool-interaction)

Commit your changes

Open a pull request with a clear description of what you added or changed

📜 License

This code is open-sourced under the MIT License (or whichever license you choose). Use it freely for personal or commercial projects, and feel free to modify or extend it.
