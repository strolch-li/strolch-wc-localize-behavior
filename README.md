# strolch-wc-localize-behavior
Custom localization behavior for Strolch Polymer-Apps.

## Usage
Add the custom behavior in your app shell

`behaviors: [StrolchLocalizeBehavior, ...]`

and configure the language and resource file, e.g.:

`strolchLocalLanguage = "en";`

`strolchLocalResourceUrl = this.resolveUrl("../locales.json");`
