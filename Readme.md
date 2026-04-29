# Swift Projects

iOS projects built in Swift and SwiftUI.

---

## [Flashforge](https://github.com/johnsaurabh/Flashforge)

An iOS app that generates flashcards from anything you share into it. Uses a Share Extension to accept text, images, and URLs from any app. On-device OCR extracts the text; the Claude API writes the flashcards; SM-2 spaced repetition schedules reviews.

**Key technical areas:** Share Extension, Vision framework, Anthropic REST API, Swift actors, WidgetKit, Keychain, XCTest with URLProtocol stubbing.

---

## Orbit *(planned)*

A native iOS dashboard for GitHub activity. Pulls pull requests, reviews, and notifications through the GitHub GraphQL API. Custom Swift Charts contribution heatmap, multi-layer caching (memory + disk + HTTP ETag), WebSocket for live PR status.

**Key technical areas:** GraphQL, custom disk cache, Swift Charts, Keychain OAuth storage, BackgroundTasks.

---

## Moodcast *(planned)*

A private mood journal that pairs entries with HealthKit context (steps, heart rate variability). An on-device CoreML model classifies sentiment. Everything runs locally with no backend or user accounts.

**Key technical areas:** CoreML, HealthKit, CloudKit private sync, Swift Charts, privacy manifest.
