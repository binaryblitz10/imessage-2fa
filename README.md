
# 2FA Code Finder

This is a fork of the original Raycast extension for 2FA detection.
The original extension sometimes failed to display 2FA codes from Apple Mail.
This version includes fixes to mailbox selection, message parsing, and content handling, ensuring that 2FA codes from emails reliably show up in Raycast.

## Installation

This extension is not available on the Raycast Store, but installation from source is straightforward:

	1.	Download the source code from the latest release
	2.	Navigate to the directory, and open a Terminal window at the downloaded folder.
	3.	Install required dependencies: **npm ci --production**
	4.	Build and load the extension into Raycast: **npm run dev**

The extension and all its commands should now appear in your Raycast app.