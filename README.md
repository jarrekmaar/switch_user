# switch_user
Service for macOS to give fast access to the 'Fast User Switching' functionality without having the menu bar active.

## Installation
Just download Switch User.workflow and double-click it. Automator will launch and the Service Installer will ask if you want to install the service or open with Automator. Choose 'Install.'

## Usage
You can either invoke the service by clicking on the name of the currently focussed application (i.e. Finder), navigating to the 'Services' menu, and clicking 'Switch User' or by binding a keyboard shortcut to the service (recommended) by going to System Preferences > Keyboard > Shortcuts > Services (from the left menu) > Scroll to the bottom of the right menu and under 'General' you'll find the 'Switch User' service. Just double-click where it says 'None' and set the desired keyboard shortcut.

## Notes
* It sometimes takes a couple seconds for the service to run, you can tell it's working if a little gear appears in the menu bar.
* Some applications can override the shortcut you set, which will cause it to be non-functional.