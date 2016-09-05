---
layout: multipage
title: Translation
weight: 3
---

## Translation

Wire is busy learning new languages, and you can help us by contributing to the translations in our Crowdin localization projects:

* [Wire iOS][1]
* [Wire Android][2]

If you're translating Wire to your native language, make sure to familiarize yourself with the official localizations for the operating system to ensure you use the correct platform terminology for your locale.

For example, the location sharing feature in Wire uses terms that are related to similar features in mobile operating systems. You can use this to your advantage when deciding how to translate Wire for your language.

In the English version of iOS, a force-touch on the Maps app reveals the **Send My Location** command. In the German version of iOS, the command is translated as **Standort senden**. So for the German version of our location sharing feature, we use the word “Standort” for location, although other options such as “Ort” or “Lage” might seem equally appropriate.

Using terms consistently helps to ensure that Wire users enjoy a seamless experience on each device and platform we support.

This principle is especially important when referring to system settings and other operating system dialogs. Make sure to verify your translations with the terms used in the localized version of the operating system.

### Terminology resources

If you don't have access to a device in the language, check public resources provided by the device manufacturer or software developer to verify the official terms.

For example, to verify terminology for iOS, you might visit [https://support.apple.com/][3] and search for a term such as “location sharing”.

Many articles are available in multiple languages, so you can select an article from the search results and switch to a different language to verify the localized language equivalents, for example:

* [https://support.apple.com/kb/PH19426?viewlocale=en\_US][4]
* [https://support.apple.com/kb/PH19426?viewlocale=de\_DE][5]
* [https://support.apple.com/kb/PH19426?viewlocale=sv\_SE][6]


### German terminology

There's also an initial version of the [German/English glossary][7] that you can use to search for the German equivalents of our English terms.

This file was created from the translation memory for the iOS project, so it still contains many long strings and placeholders, but it should give you a good idea of the current German terminology we use.

We're working on integrating a proper multilingual glossary into our Crowdin localization platform, so translators will have access to annotated terminology suggestions within the translation tool.

For a list of multi-touch gesture terms & their German equivalents, see [multi-touch-gestures.csv][8]. These terms are derived from Apple's official German glossary.


[1]: https://crowdin.com/project/wire-ios
[2]: https://crowdin.com/project/wire-android
[3]: https://support.apple.com/
[4]: https://support.apple.com/kb/PH19426?viewlocale=en_US
[5]: https://support.apple.com/kb/PH19426?viewlocale=de_DE
[6]: https://support.apple.com/kb/PH19426?viewlocale=sv_SE
[7]: https://github.com/wearezeta/copywriting/blob/master/Glossary/Wire-iOS_EN-DE.csv
[8]: https://github.com/wearezeta/copywriting/blob/master/Glossary/multi-touch-gestures.csv