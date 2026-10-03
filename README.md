# Remove the nova update UI changes

This repository contains a drop-in `userChrome.css` to be copied to a new folder `chrome` in your profile (locate using `about:profiles` and check for the one with "This is the profile in use and it cannot be deleted". Copy the path and create the folder `chrome`, then copy the userChrome.css there.

## Dark mode fixes:

Firefox 157.0 comes with a dark alpenglow theme instead of the default dark theme. Use the [Matte Black](https://addons.mozilla.org/en-US/firefox/addon/matte-black-v1/) theme to (try to) restore the black theme.

## Changes which have not been made:

All Firefox UI elements now have rounded corners, including the preferences page at about:preferences, and about:newtab, about:profiles etc. These remain as such, along with the purple accent.

### LLM disclosure

Most of the changes were made by running Gemini on the diff of browser/themes.

### License

This repository is licensed under LGPL-2.1-or-later
