# Marvel API Auth Generator (PAW Extension)

The Marvel API Auth Generator Paw Extension enables the generation of signed requests so that you can explore the [Marvel Comics API](http://developer.marvel.com/) with Paw, using Marvel's [Authentication for Server Side-Applications](http://developer.marvel.com/documentation/authorization) requirements.

## Installation

To manually install the __Marvel API Auth Generator__ extension, navigate to the PAW Preferences panel and click on the Extensions tab:

![PAW preferences](./resources/preferences.jpg)

Click on the `Open Extensions Directory` button. Drag the `com.markeissler.MarvelAPIAuth` folder into the extensions directory. If PAW is already open it will detect and load the extension automatically without needing to restart the application.

## Getting your API keys

Before you can access the API, you will need to sign up for a free developer account. After logging in, you'll be able to retrieve your personal API private and public keys from the [My Developer Account](https://developer.marvel.com/account) navigation item.

## Using your API keys with PAW

Marvel requires that each request is signed with a dynamically generated hash. After installing the __Marvel API Auth__ extension in PAW, simply add an __URL Param__ as shown in the following image:

![apikey URL Param](./resources/url_params.jpg)

For the value, select __Marvel API Auth Generator__ (if the extension has been installed, it should appear in a popup as you begin typing the name). Then, click on the value field and the following popup should appear:

![public and private key entry popup](./resources/key_config.jpg)

The values you enter here should persist between sessions so that you won't have to re-enter them again (unless they change).

## Credits

This plugin makes use of the third-party JavaScript FastMD5 library from xibre. It is available on Github:

[FastMD5 -- Fast JavaScript MD5 library](https://github.com/xibre/FastMD5)



