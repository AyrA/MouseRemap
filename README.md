# Mouse Button Remapper

This application remaps the fake mouse button on a certain 7 inch mini laptop from aliexpress to real mouse buttons using autohotkey.

## How the built-in mouse works

The red nub registers as a regular mouse and moves the cursor appropriately. The two mouse buttons however, are for some weird reason not part of said mouse, but the keyboard. The left button maps to the "5" key on the numpad, and the right button maps to the context menu key that's usually found below the right shift key on full sized keyboards.

## Installation

The easiest way is to download the executable from the releases section of this repository and placing it in your startup folder.

The easiest way to reach this folder is to open any file explorer window and typing `shell:startup` into the address bar.

**Note**: Windows marks all downloaded executables as unsafe. If the file refuses to run or Windows keeps throwing messages at you, you may need to open the file properties, and then click the checkbox in the lower wight corner that says "Unblock", then click "OK".

## Using the script

If you prefer to use the script directly, follow these steps

1. [Install Autohotkey](https://www.autohotkey.com)
2. Copy the `MouseRemap.ahk` file into your startup folder (see chapter above on how to do this)

## Pausing the script

A green "H" icon will be placed in the tray icon section while the script is running. You can right click the icon and pause the script if it interferes with something. In general you only have to do this if you connect an external keyboard and want to use the two keys that are remapped.

## Drawbacks

This solution is not without flaws. The primary one being that the script is not active unless you sign into your account. This means you're forced to navigate the lock screen and logon screen using the keyboard, an external mouse, or the touch screen.
