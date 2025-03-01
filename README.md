# View Background Image
Chrome extension that adds "View background image" to the context menu

## Installation

[![Install the extension](https://developer.chrome.com/webstore/images/ChromeWebStore_BadgeWBorder_v2_206x58.png)](https://chrome.google.com/webstore/detail/cegndknljaapfbnmfnagomhhgbajjibd) [![Firefox](https://addons.cdn.mozilla.net/static/img/addons-buttons/AMO-button_1.png)](https://addons.mozilla.org/firefox/addon/view-background-images/)

This extension requires permission to access your data on all websites only for viewing background images.

## Usage

1. Install the extension and __reload tabs__.
2. Open the context menu on an image which you want to view.
3. Select `View background image`.
4. Images under the mouse cursor will be displayed on new tabs.

## Known Issues

It is technically impossible to view background images:

* [CSS Paint API](https://developers.google.com/web/updates/2018/01/paintapi?hl=en)
* [Closed Shadow DOM](https://developers.google.com/web/fundamentals/web-components/shadowdom?hl=en#closed) (e.g., [Embedded Tweets](https://developer.twitter.com/en/docs/twitter-for-websites/embedded-tweets/overview.html))
* Some inline SVGs


## Contributing

### Translation
I need your help with translating into the language you speak.

1. Fork this repository.
2. Edit `messages.json` in `src/_locales/[localeCode]`. If not exists, create a directory according to the [supported locales](https://developer.chrome.com/webstore/i18n?csw=1#localeTable).
3. Create a new pull request.

## License
This software is released under the [MIT License](https://github.com/foooomio/view-background-image/blob/master/LICENSE.txt).

## Author
foooomio - [@foooomio](https://twitter.com/foooomio)
