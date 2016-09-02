---
layout: multipage
title: User interface text
weight: 2
---

## User interface text

Text appears in the user interface _(or “UI”)_ in button names, menu labels, application settings, dialog messages, and notification banners.

The care we take in crafting every bit of text _(or “microcopy”)_ in the app should reflect the level of detail invested in the overall application design and user experience that sets Wire apart.

> In the same way that it’s best to work with a professional graphical designer on the icons and images in your app, it’s best to work with a professional writer on your app’s user-visible text. A skilled writer can help you develop a style of expression that reflects your app’s design, and can apply that style consistently throughout your app.

— Apple _OS X Human Interface Guidelines_

Rather than re-invent the wheel or get “creative” in ways that confuse users, we defer to existing platform conventions wherever possible.

The sections below provide resources for each platform we support.

## Mac OS X (desktop)

When writing for the Mac desktop user interface, use the conventions that Apple has established in the [OS X Human Interface Guidelines][OSX-HIG].

The following sections are particularly useful:

* [Naming Menus and Items](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/MenuNaming.html)
* [Terminology and Wording](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/TerminologyWording.html)
* [Use the Right Capitalization Style in Labels and Text](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/TerminologyWording.html#//apple_ref/doc/uid/20000957-CH15-SW4)

**NOTE:** In June, Apple announced that their desktop operating system will be renamed from “OS X” to “macOS” with Version 10.12 (Sierra).

However, since _OS X El Capitan_ (Version 10.11) is still the current version, we’ll stick with the “OS X” terminology until the new version ships this fall. Once _macOS Sierra_ is released, we’ll change all occurrences to reflect the official name of the new “macOS”.

## iOS

When writing for iOS, refer to the [iOS Human Interface Guidelines][iOS-HIG], especially:

* [Terminology and Wording](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/FeedbackCommunication.html)
* [UI Elements](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/Bars.html)

## Android

For guidance on writing conventions for Android, see [Android Writing Style](https://developer.android.com/design/style/writing.html).

## Glossary of Wire terms

See the [draft Glossary on GitHub](https://github.com/wearezeta/copywriting/blob/master/Glossary/zeta-glossary.csv).

Feel free to suggest new terms if there’s something missing there.

## Localization

Wire is busy learning new languages, and you can help us by contributing to the translations in our Crowdin localization projects:

* Wire iOS — <https://crowdin.com/project/wire-ios>
* Wire Android — <https://crowdin.com/project/wire-android>

If you're translating Wire to your native language, make sure to familiarize yourself with the official localizations for the operating system to ensure you use the correct platform terminology for your locale.

For example, the location sharing feature in Wire uses terms that are related to similar features in mobile operating systems. You can use this to your advantage when deciding how to translate Wire for your language.

In the English version of iOS, a force-touch on the Maps app reveals the **Send My Location** command. In the German version of iOS, the command is translated as **Standort senden**. So for the German version of our location sharing feature, we use the word “Standort” for location, although other options such as “Ort” or “Lage” might seem equally appropriate.

Using terms consistently helps to ensure that Wire users enjoy a seamless experience on each device and platform we support.

This principle is especially important when referring to system settings and other operating system dialogs. Make sure to verify your translations with the terms used in the localized version of the operating system.

### Terminology resources

If you don't have access to a device in the language, check public resources provided by the device manufacturer or software developer to verify the official terms.

For example, to verify terminology for iOS, you might visit <https://support.apple.com/> and search for a term such as “location sharing”.

Many articles are available in multiple languages, so you can select an article from the search results and switch to a different language to verify the localized language equivalents, for example:

* <https://support.apple.com/kb/PH19426?viewlocale=en_US>
* <https://support.apple.com/kb/PH19426?viewlocale=de_DE>
* <https://support.apple.com/kb/PH19426?viewlocale=sv_SE>


### German terminology

There's also an initial version of the [German/English glossary](https://github.com/wearezeta/copywriting/blob/master/Glossary/Wire-iOS_EN-DE.csv) that you can use to search for the German equivalents of our English terms.

This file was created from the translation memory for the iOS project, so it still contains many long strings and placeholders, but it should give you a good idea of the current German terminology we use.

We're working on integrating a proper multilingual glossary into our Crowdin localization platform, so translators will have access to annotated terminology suggestions within the translation tool.

For a list of multi-touch gesture terms & their German equivalents, see [multi-touch-gestures.csv](https://github.com/wearezeta/copywriting/blob/master/Glossary/multi-touch-gestures.csv). These terms are derived from Apple's official German glossary.
