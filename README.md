# minimal-functional-fox

I liked the original [minimal-functional-firefox mod](https://github.com/mut-ex/minimal-functional-fox), but it just wasn't... minimal... enough.

## Preview

## Features

* Minimal bloat
* Easy way to quickly change colors, tab dimensions, paddings to your liking through CSS variables
* Pinned tabs are re-styled to stand out
* Tab list underneath the navigator area
* Centered URL bar, with a thinner, centered results list
* Fix for buggy shadows on Linux
* **Only in this fork**: tabs, urlbar, and bookmarks are hidden by default, unless you hover your mouse over the navbar

## Instructions

* Make sure that you have enabled the **userChrome** option
  1. Go to the address `about:config` in Firefox
  2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
  3. Confirm the option is set to true

* Make sure that you have the `Dark` theme enabled
  1. Go to the address `about:addons`
  2. Select `Themes`
  3. Enable the `Dark` theme if not already enabled

* Copy the contents of this repository to `.mozilla/firefox/<your-profile-name>/chrome/`
  * <your-profile-name> will be a directory ending with '-release' and have a bunch of files in it
  * If there isn't a chrome folder, you can just go ahead and create one

* If your new tab button looks too tiny/squished, [check out this fix](https://www.reddit.com/r/unixporn/comments/ebchep/oc_i_created_this_userchrome_configuration_to_be/fb59g0k?utm_source=share&utm_medium=web2x)

* **Optional but recommended**
  1. Select the Customize option from the hamburger menu
  2. Remove all items except for:
    * Forward button
    * Back button
    * Downloads button

* [You can find the new tab page extension here](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
