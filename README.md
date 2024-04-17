# google-usa-search

google-usa-search is a Firefox extension that forces Google to display search results in American English.

![Retrofuturistic beach with pipes surrounding the camera](/assets/hero.jpeg)

Image generated using OpenAI's [DALL-E 3](https://openai.com/dall-e-3).


## Motivation

By default, Google ignores your preferred language settings and uses your current location (e.g., Poland) to determine your language (e.g., Polish).

Although the region can be changed in the website's settings, this default behavior is infuriating, especially for anyone who clears their cookies/cache frequently.

This extension adds a search engine that behaves just like regular Google Search, but with the language forcefully set to American English (by appending `hl=en&gl=us` to the URL).


## Setup

### 1. Enable unsigned addons.

> NOTE: This does not work on regular Firefox. It only works on Firefox Extended Support Release (ESR), Firefox Developer Edition and Nightly. Personally, I use ESR.

**Note:** This only works on Firefox Extended Support Release (ESR), Firefox Developer Edition, and Nightly.

- Go to `about:config`.
- Set `xpinstall.signatures.required` to `false`.

I didn't bother getting it signed, because it's only for personal use.


### 2. Download the extension.

- Go to Releases.
- Download `google-usa-search.zip`.

If the zip doesn't work, right click the `manifest.json` and the `icons` directory, then click `Compress` ([source](https://extensionworkshop.com/documentation/publish/package-your-extension/)).


### 3. Install the extension.

- Go to `about:addons`.
- Click the Gear icon.
- Click `Install Add-on From File...`.
- Select `google-usa-search.zip` and click add.
- Optionally, also enable `Allow this extension to run in Private Windows`.


### 4. Set Google USA as default.

- Na to `about:preferences#search`.
- Set `Default Search Engine` to `Google USA`.

That's it.


## Contributing

All contributions are welcome.


## License

This project is released into the public domain and is licensed under the Unlicense.


## Credits

This extension is a simple fork of [google-uk-search](https://github.com/jscher2000/google-uk-search/) and is intended for my own personal use.

No credit is claimed for the original work.
