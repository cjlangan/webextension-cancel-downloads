# Firefox Cancel Donwloads

Firefox WebExtension addon to automatically cancel all downloads.

Allowing you to then copy the download link and do whatever you please with it. Such as using `wget` to download it instead.

## Usage

Clicking the extension icon will toggle whether the cancellation function is enabled.

The extension icon will show a badge with the number of cancelled downloads. You can SHIFT-click the badge to reset the count.

The badge will be red if the last download was cancelled, otherwise green. You can also hover the extension icon for some stats.

## Installation

Install from the Mozilla addons site here:  [Mozilla Addons](https://addons.mozilla.org/en-US/firefox/addon/cancel-downloads/)

## Other tools

I use Cancel Downloads in combination with the `cliget` Firefox addon, so that I can retrieve a nice `wget` or `curl` command to download files that require login data, it does this by putting in parameters for cookies.
