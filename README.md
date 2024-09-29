# cancel-duplicate-downloads

## Description

Firefox WebExtension addon to automatically cancel all downloads

## Usage

Clicking the extension icon will toggle whether the cancellation function is enabled. For example, if you actually need to download a file that looks like a duplicate.

The extension icon will show a badge with the number of cancelled downloads. You can SHIFT-click the badge to reset the count.

The badge will be red if the last download was cancelled, otherwise green. You can also hover the extension icon for some stats.

## Notes

1. The addon won't automatically cancel files without an extension, so `blah(1)` will always be allowed.
