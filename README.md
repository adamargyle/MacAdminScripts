# Mac Admin Scripts
Scripts I use to customize systems not specific to Jamf.

## Utility Scripts
Scripts that I use for managing general settings not specific to Jamf Pro
* **NVRAMclear** runs the command line version of an NVRAM/PRAM reset. This can help some issues and when an EFI firmware password is enabled it will allow a user who cannot utilize the option to hold modifier keys during startup.
* **resetkeychain** is a script to reset a keychain when an AD mobile account user changed their password elsewhere and it is not updating correctly. It just creates a new keychain.
* **startupChime** re-enables the startup chime on newer macs, because it's fun and it made the blog rounds https://mrmacintosh.com/how-to-enable-the-mac-startup-chime-on-your-2016-macbook-pro/

## Outset User Default Scripts
These are scripts intended to be used with login-once using outset
* **defaultdock** using dockutil this clears the dock and sets a default. Its set to run once at login-once and this sets but does not enforce for a new user's profile
* **defaultusersettings** sets security settings and finder preferences as well as sets the desktop image with desktoppr to a default image.