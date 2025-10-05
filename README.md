# Stepstone 🪨👣

A gamified step-tracking iOS app that turns your daily walks into epic journeys.

## Overview

Stepstone lets you set ambitious walking goals based on real-world journeys and famous trails. Instead of arbitrary step counts, choose to walk the Oregon Trail, complete a Marathon, or hike the Appalachian Trail - all from wherever you are.

Every step you take brings you closer to your destination. Watch your progress grow as you place stepping stones along your journey.

## Features

- 📍 Choose from preset journey goals (Oregon Trail, Marathon, Appalachian Trail, and more)
- 👟 Automatic step tracking via HealthKit
- 📊 Visual progress tracking with milestones
- 🎯 Custom distance goals
- 🎉 Celebrate achievements along the way

## Tech Stack

- **Language:** Swift
- **UI Framework:** SwiftUI
- **Architecture:** MVVM with Protocol-Oriented Programming
- **Concurrency:** Swift async/await with @MainActor
- **Health Data:** HealthKit integration
- **Minimum iOS:** iOS 17.0+

## Project Structure

Stepstone/
├── Features/         # Feature modules (GoalSelection, Progress, etc.)
├── Services/         # Protocol-based services (HealthKit, Storage)
├── Models/           # Data models
└── App/              # App entry point and dependencies

## Development Principles

- Protocol-oriented design for testability
- Dependency injection throughout
- @Observable for modern state management
- Comprehensive unit tests for ViewModels
- SwiftUI previews for rapid UI iteration

## Getting Started

1. Clone the repo
2. Open `Stepstone.xcodeproj` in Xcode
3. Build and run on iOS Simulator or device with HealthKit enabled

## Roadmap

- [ ] Goal selection screen
- [ ] Progress tracking view
- [ ] HealthKit integration
- [ ] Milestone celebrations
- [ ] Custom journey creation
- [ ] Social sharing
- [ ] Historical data visualization

## License

MIT License - feel free to use this as a learning resource!
