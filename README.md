# Mouse Button Remapper

This application remaps the fake mouse button on ![a certain 7 inch mini laptop from aliexpress](https://i.imgur.com/Bz1Dyyu.jpg) to real mouse buttons using autohotkey.

This works much better and more reliable than the keyboard mouse function of the accessibility tools. Especially things like drag and drop work much more reliable, and support in games is generally also better.

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

## Drawbacks

This solution is not without flaws. The primary one being that the script is not active unless you sign into your account. This means you're forced to navigate the lock screen and logon screen using the keyboard, an external mouse, or the touch screen.

Another problem is that the `5` key on the numpad no longer works. This is not an issue with the internal keyboard, but if you connect a full sized keyboard to it and want to use the numpad, you may find this annoying. To fix that, you can rightclick the green "H" icon in the tray icon section and pause the script.
