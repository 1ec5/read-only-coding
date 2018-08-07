# read-only-coding
Automator services to make coding in Xcode easier. Written mostly in AppleScript, the [read-only language](https://en.wikipedia.org/wiki/Read-only_language).

## Services

### Open Selection in GitHub

If a Git-managed source code file is open in Xcode, this service opens a checked-in copy of the file on GitHub in your default Web browser, with the selected line or lines highlighted. The clone containing the file must have a remote named `origin` that points to GitHub via HTTPS.

## Installation

To install these services:

1. [Download a ZIP of this repository](https://github.com/1ec5/read-only-coding/archive/master.zip).
2. Double-click each .workflow bundle and click Install. (Or drop each .workflow bundle into ~/Library/Services/.)

To assign keyboard shortcuts to these services:

1. Open System Preferences and go to the Keyboard preference pane.
2. Switch to the Keyboard Shortcuts tab and select Services from the pane on the left.
3. Select a service and click “add shortcut”.
