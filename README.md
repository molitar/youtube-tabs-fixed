# Youtube Tabs Fixed

| Preview Builds | Release Builds | License | Downloads |
|:---:|:---:|:---:|:---:|
| [![Preview](https://img.shields.io/github/v/release/molitar/youtube-tabs-fixed?include_prereleases&label=preview&color=orange)](https://github.com/molitar/youtube-tabs-fixed/releases) | [![Download](https://img.shields.io/github/v/release/molitar/youtube-tabs-fixed?label=download&color=blue)](https://github.com/molitar/youtube-tabs-fixed/releases/latest) | [![License](https://img.shields.io/github/license/molitar/youtube-tabs-fixed?color=orange)](https://github.com/molitar/youtube-tabs-fixed/blob/main/LICENSE) | [![Downloads](https://img.shields.io/github/downloads/molitar/youtube-tabs-fixed/total?color=green)](https://github.com/molitar/youtube-tabs-fixed/releases) |

**Tidy up your YouTube subscription list with tabs, in Firefox.**

Youtube Tabs Fixed adds tabs to the Subscriptions list in YouTube's left-hand menu, so you can group channels, name and colour each tab, mark favourites, and hide the tabs you don't need right now.

This is a community-maintained fork of the original [Youtube Tabs](https://addons.mozilla.org/en-US/firefox/addon/youtube-tabs-/) by Geek Overdrive Studio. It keeps the original behaviour and fixes problems caused by YouTube interface changes.

## Features

- Create tabs inside the Subscriptions panel and file channels into them.
- Rename tabs, change their colours, reorder them and show or hide them.
- Favourite a channel to have it listed first.
- A quick menu to file a new subscription as soon as you subscribe.
- Back up and restore your tabs with the import / export buttons in the help window (the **?** button in the Subscriptions header).

Your tab data is stored in your browser only. If you clear your browser's data without a backup, it is lost, so export a backup now and then.

## What's fixed in 2.0.29

- The tab panel no longer scrolls up past the YouTube header.
- The fly-out button for editing, renaming, recolouring or changing a channel's link now stays on screen long enough to use (2.5 seconds instead of a quarter of a second).
- The fly-out menu and the new-subscription chooser open on top of the video list, stay inside the window, and are no longer hidden behind YouTube's own layers.

See [CHANGELOG.md](CHANGELOG.md) for the full list.

## Installation

Download the latest `.xpi` from the [Releases](https://github.com/molitar/youtube-tabs-fixed/releases) page and open it in Firefox. Releases marked "Pre-release" are unsigned builds waiting for Mozilla: they install in Firefox Developer Edition, Nightly or ESR with `xpinstall.signatures.required` set to `false`, or can be loaded temporarily from `about:debugging`. Normal releases are signed by Mozilla and install in regular Firefox.

The extension only runs on `https://www.youtube.com/*` and collects no data.

## Support

Bug reports, questions and ideas are welcome: [GitHub Issues](https://github.com/molitar/youtube-tabs-fixed/issues). Please include your Firefox version and what you did before the problem appeared.

## Source

The extension is plain JavaScript and CSS with no build step: the `.xpi` is a zip of `manifest.json`, `youtube-tabs.js`, `tabs.css`, `help.html`, `iro.min.js` and the icon images.

## License

MIT License. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md) for the original author's credit and the bundled iro.js library.
