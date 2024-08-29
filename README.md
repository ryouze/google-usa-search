# google-usa-search

google-usa-search is a Firefox extension that forces Google to display search results in American English.


## Motivation

By default, Google ignores your preferred language settings, and uses your current location (e.g., Poland) to determine your language (e.g., Polish).

Although the region can be changed in the website's settings, this default behavior is infuriating, especially for anyone who clears their cookies/cache frequently.

This extension adds a search engine that behaves just like regular Google Search, but with the language forcefully set to American English (by appending `hl=en&gl=us` to the URL).


## Install

Follow these steps to install the extension:

1. **Enable unsigned addons**

    **Note:** This does not work on regular Firefox. It only works on Firefox Extended Support Release (ESR), Firefox Developer Edition, and Nightly. Personally, I use ESR.

   - Go to `about:config`.
   - Set `xpinstall.signatures.required` to `false`.


2. **Download the extension**

    - Go to the [Releases](../../releases) page.
    - Download `google-usa-search.zip`.

    If the zip doesn't work, go to the `src` directory, then right click the `manifest.json`, and the `icons` directory, then click `Compress`. Refer to [extensionworkshop.com/documentation/publish/package-your-extension](https://extensionworkshop.com/documentation/publish/package-your-extension/) for more information.


3. **Install the extension**:

   - Go to `about:addons`.
   - Click the Gear icon.
   - Click `Install Add-on From File...`.
   - Select `google-usa-search.zip`, and click add.
   - Optionally, also enable `Allow this extension to run in Private Windows`.

4. **Set Google USA as default**:

   - Navigate to `about:preferences#search`.
   - Set `Default Search Engine` to `Google USA`.

That's it.


## Credits

This extension is a simple fork of [google-uk-search](https://github.com/jscher2000/google-uk-search/), and is intended for my own personal use.


## Contributing

All contributions are welcome.


## License

This project is licensed under the Unlicense License.
