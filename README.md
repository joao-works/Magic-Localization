# ✨ The Magic Localization Initiative

<p>
    <img src="https://img.shields.io/badge/Download Magic-7D28DF.svg" />
    <a href="https://twitter.com/joogps">
        <img src="https://img.shields.io/badge/Contact-@joogps-lightgrey.svg?style=social&logo=twitter" alt="Twitter: @joogps" />
    </a>
</p>

Hello! And welcome to the Magic Localization Initiative. This is the community language repository for [Magic](https://magic.joogps.com).

If you'd like to have your language fully supported by Magic or make a correction to the current translations (and you know how to use Git), feel free to make add an issue or make a pull request to this repository.

## Supported languages
- [English](/en.lproj/)
- [Brazilian Portuguese](/pt-BR.lproj/)

## Request language
To request a language or report an issue with a translation, please create an issue on the [issues section](https://github.com/joao-works/Magic-Localization/issues). If you wish to contribute and add a language, please follow the guidelines below:

## Guidelines

Before you contribute, please make sure that you follow these guidelines:

- First, fork and clone the repository to your local machine.
- The currently supported languages are stored in the root directory of this repository with filenames `language_code.lproj`. If you want to add a new language, create a new file with the language code and `.lproj` extension. For example, if you want to add Spanish, create a file called `es.lproj`.
- The .lproj file contains a `Localizable.strings` file. This is the file that contains all the strings used in the app. To translate, just translate the right-hand side of the equal sign. For example, if you want to translate `"hello"` to Spanish, you would change the file to `"hello" = "hola";`. Don't translate the commented text, as it is used for context.
- There's also a `Localizable.stringsdict` that can be opened with Xcode or edited by hand. Currently, it's only used for support of the pluralization of "n-month" strings (detailing a subscription period). For example, in English, if talking about a single month, "monthly" can be used, but for 6 months, it's "6-month". Feel free to reach out to me regarding this specific translation!

There is also a [previews.txt](previews.txt) file that contains the text used for the app previews of Magic on the app store – you can optionally add your language to it with the same format as the other languages. Finally, the [descriptions.txt](descriptions.txt) file contains the text used for the app description of Magic – you can also optionally add your language to it with the same format as the other languages, if you wish to see it on the App Store.

### Approval

Once you've made your changes, please make a pull request to this repository. I'll review it and merge it if everything is correct. If you have any questions, feel free to reach out to me. I might require a second opinion from a native speaker of the language you're translating to.

## What you get

That's a lot! But wait! It's _your_ work. If you contribute to this repository, you'll get your name in the app's credits associated with the language you contributed with. In addition, I'll personally send you a promo code to Magic Unlimited for the duration of 6 months.

## Thank you

Thank you for your contribution! It means a lot to me, Magic and to the community. If you have questions, feel free to open an issue or contact me at [joogps@icloud.com](emailto:joogps@icloud.com). I'll be happy to help you out. Have a nice day!
