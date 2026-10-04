# google-usa-search

A Firefox extension that forces Google to display search results in American English.

## Motivation

Google uses your location (e.g., Poland) to determine the language of search results (e.g., Polish), ignoring your preferred language settings. You can override this behavior in Google's settings, but the change is lost when you clear your cookies.

This extension forces American English by adding `hl=en&gl=us` to the search URL.

## Install

1. **Enable unsigned add-ons**:

   **Note:** This does not work on regular Firefox. It only works on Firefox Extended Support Release (ESR), Firefox Developer Edition, and Firefox Nightly. I personally use ESR.

   - Go to `about:config`.
   - Set `xpinstall.signatures.required` to `false`.

2. **Download the extension**:

   - Go to the [Releases](../../releases) page.
   - Download `google-usa-search.zip`.

   If the ZIP file doesn't work, go to the `src` directory, right-click `manifest.json` and the `icons` directory, and click `Compress`. Refer to [extensionworkshop.com/documentation/publish/package-your-extension](https://extensionworkshop.com/documentation/publish/package-your-extension/) for more information.

3. **Install the extension**:

   - Go to `about:addons`.
   - Click the gear icon.
   - Click `Install Add-on From File...`.
   - Select `google-usa-search.zip`, then click `Add`.
   - Optionally, enable `Allow this extension to run in Private Windows`.

4. **Set Google USA as the default**:

   - Go to `about:preferences#search`.
   - Set `Default Search Engine` to `Google USA`.

## Credits

This extension is a simple fork of [google-uk-search](https://github.com/jscher2000/google-uk-search/).
