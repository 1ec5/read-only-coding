## Creating a service

The services in this project are Automator workflows that run AppleScript code. To create a service:

1. Open Automator.app in Mac OS X 10.4 “Tiger” or above.
1. In the sheet that appears, choose Service (the gear icon) and click Choose.
1. In the sidebar on the left, select the Actions filter and double-click “Run AppleScript” or “Run JavaScript” from the Library ‣ Utilities category.
1. Compose your script in the new action’s text box. If you’re writing the action in AppleScript, make sure to `tell application "Xcode"`.
1. Go to File ‣ Save. In the sheet that appears, choose the file name, which will also be the name of the menu item in the Services menu. The workflow is saved to ~/Library/Services/.
1. Copy the workflow bundle to a checkout of this project, commit it, and create a pull request.

To find out what you can do with Xcode in an AppleScript or JavaScript action, open Script Editor.app (AppleScript Editor.app in earlier versions of Mac OS X) and go to File ‣ Open Dictionary. Select Xcode.app and click Choose.

An Automation workflow can contain many kinds of actions. Depending on the circumstances, you may find it more maintainable to keep everything inline in an AppleScript or JavaScript action, or you may find it more maintainable to use a more specific action.

## Reporting a bug

Bug reports are welcome. In your issue, please indicate:

1. The version of macOS, OS X, or Mac OS X you’re running.
1. The version of Xcode you’re using and where it’s installed.
