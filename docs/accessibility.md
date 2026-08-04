# Accessibility

Nimbus Reader is built with SwiftUI on Apple platforms, which gives us a lot of accessibility support out of the box, and we're actively improving on top of that.

## What we support today

- **VoiceOver** — Key screens (welcome/sign-in, library, subscription, and the speed-reading view) have explicit accessibility labels and hints so VoiceOver users can navigate them.
- **Dynamic Type** — Text throughout the app uses the system's scalable fonts, so it responds to the text size you've set in iOS Settings > Accessibility > Display & Text Size.
- **Standard iOS accessibility features** — Because we use native SwiftUI components, general system-level accessibility features (Bold Text, Increase Contrast, Reduce Motion, Reduce Transparency, etc.) are respected by default unless noted otherwise below.

## Known gaps

Accessibility coverage isn't complete across every screen yet — some areas of the app (in particular, less-common flows) don't yet have explicit VoiceOver labels or have been tested with every assistive technology. We're working through these incrementally.

## Something not working for you?

If you rely on an assistive technology and hit a screen or flow that doesn't work well, please [open an issue](https://github.com/rogerprz/nimbus-reader-support/issues/new) in this repo, or email [summercypressventures@gmail.com](mailto:summercypressventures@gmail.com). Include:

- The assistive technology you're using (e.g. VoiceOver, Switch Control, Voice Control)
- The screen or feature affected
- What you expected vs. what happened

We'll add it to the backlog and prioritize fixes.

## Requesting additional support

More generally — if there's any accessibility feature, ebook format, or app behavior you need that isn't currently supported, [open an issue](https://github.com/rogerprz/nimbus-reader-support/issues/new) describing your use case and we'll add it to our backlog for consideration.
