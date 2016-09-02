---
layout: multipage
title: Writing guidelines
---

## Abbreviations

Avoid abbreviations where possible. Use “for example” or “such as” instead of “e.g.” or “that is” instead of “i.e.”. – or, better yet – edit copy to avoid these constructs entirely.

## Articles

In all UI copy, we avoid articles wherever possible. Articles include “a”, “an”, “the”, etc. In a similar vein, we also avoid demonstrative words such as “this” and “those”.

## Capitalization

We use all caps for system messages (“UNBLOCK”) in the conversation view and in certain other places as necessary to agree with (Android) platform conventions.

However, for longer phrases or sentences, we use sentence case: we only capitalize the first word of a phrase or sentence (“You’ve left this conversation”).

Headings on the website, support site, and longer documents should use case consistently _(either sentence case or title case)_ based on context.

For example, CS content at [support.wire.com](https://support.wire.com/) uses sentence case in the question list, but title case in page headings _(as required by the Zendesk customer service platform)_. Certain channels _(such as press releases)_ may have other conventions to which we respectfully adhere.

For long-form documents, we prefer sentence case for headings, as we feel this is a better match for our “humble and friendly” voice. Some perceive title case as more formal and a bit too stiff for our tone, so we avoid it in contexts where it’s not required.

In [UI copy](#ui-copy), we capitalize according to the platform conventions, such as Apple’s conventions from the _Human Interface Guidelines_ for [iOS][iOS-HIG] and [OS X][OSX-HIG].

As a general rule, menu commands use title case, but checkboxes and radio buttons use sentence case. See [Use the Right Capitalization Style in Labels and Text](https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/TerminologyWording.html#//apple_ref/doc/uid/20000957-CH15-SW4).

## Numbers

In the application, numerals should be used in all cases to save space:

* _1 message pending_
* _3 conversations_
* _Your password must be at least 6 characters_

However, on the website, numbers from one to nine should be spelled out (for example, “there are three ways to download Wire.”)

## Politeness

We try to sound courteous without being obsequious. While we are not afraid to use “please” or thank you” where applicable, we use these phrases judiciously.

For example, in an initial message in the application, we may ask a user to “Enter a phone number”. If there’s a mistake and we need to generate a second message, this is the time to say: “Please enter a valid phone number”.

## Punctuation

* We do not use periods in most UI strings unless there are two or more sentences. (For example, “Start a conversation”). However, copy on the website should be punctuated correctly.
* We use the serial comma (for example, “Email, phone number, and address”).
* Avoid apostrophes, exclamation marks, ampersands, and the “+” symbol in UI copy.
* Use proper typography for “quotation marks”, em- and en- dashes (–/–), ellipses (…), and other characters wherever possible. (Most UI strings files are now UTF-8 encoded, so typographically correct characters can be used in most cases — there’s no excuse for substituting ASCII text where proper typography is available.)

For complete punctuation rules, we suggest you refer to any good American style guide (_The Chicago Manual of Style_ or _The Yahoo Style Guide_).

## Word choice

Whenever possible, cut unnecessary words. Avoid using too many qualifiers (adjectives, adverbs), modifying clauses and jargon.

Be careful that you don’t bury the action of your sentence in a noun. Instead, take the action out of the noun and put it in the verb format.

## Common usage issues

_(This section complements the Glossary with preferred phrasing & additional explanations for copy issues we find ourselves correcting repeatedly.)_

**For example:** _“in Wire” or “on Wire”?_

We say “in Wire” to mean “in the app”, but “on” is more appropriate when we mean the platform as a whole: “let’s connect on Wire” and “look at the conversation in Wire”.

Easiest to remember as _**in** the app, **on** the plaform_.

### Account references
People _“create an account”_ with Wire — they no longer “join”, “register”, or “sign up”.

They can then “log in” _(two words)_ to their account — _no longer “sign in”_.

**NOTE:** This terminology was changed in December 2015, one year after launch.

People can “log out” of the application and reset their password by selecting options from the … menu in their “Profile”.

### Calls to action
We never ask people to **click here**. Instead we link the key nouns or verbs in the call to action.

### Dates and times
Time indications in conversations are automatically updated and we use timestamps that are relative to the moment, supported by a “casual” writing style (for example, “yesterday”).

Use the following long date format when possible: July 6, 2016.

To avoid ambiguity, do not use 06.07.16, 06/07/2016 or similar formats.

### Icon references
When referring to icons that appear in the user interface, use the name of the action or command that they perform, not the symbol that appears on the button: **Settings** or **Preferences**, not **Gear** or **Cog**.

> “To end the call, tap the Close × icon in the upper left corner of the conversation.”

For an overview of our UI icons, see [User Interface Icon Names](https://github.com/wearezeta/copywriting/blob/master/UI%20copy%20clients/Zeta%20font/preview_icon_names.pdf?raw=true).

### Preferred spelling variants
* Internet _(capitalized per Apple style guide — see note below)_
* email _(no hyphen)_
* web _(lowercase)_
* webpage _(One word. A self-contained document on a website. A single website can contain many webpages. Don’t use website and webpage interchangeably.)_
* website _(One word. Refers to a collection of webpages.)_
* megapixel
* Wi-Fi _(hyphenated per iOS, OS X & Android)_
* log in / out _(verb: as in “log in to your account” – not “sign in”)_

The default language for Wire copy is U.S. English — so no “u” in “color”, etc.

**NOTE:** In June 2016, the Associated Press and many mainstream newspapers announced they would no longer capitalize “Internet”. Since Apple still uses the capitalized form in iOS and OS X, Wire does the same in UI copy to ensure our app remains consistent with the spelling used in the operating systems.

### Security references
We intentionally leave some elements of our UI copy abstract. This can help to protect users from people with malicious intent (for instance, bots searching for account details).

A good example is the UI error message that tells people they have entered the “wrong address or password”. We may know exactly what’s wrong, but we leave our message vague to stop people from trying to find out if a user account exists.

### Select/choose vs. click/tap/touch
Since people can _(and will)_ interact with Wire across a variety of devices, with a variety of input options (touchscreens, mice, keyboards, etc.), use generic verbs like “select” or “choose” if the content applies to all platforms.

Where the platform context is clear, use the verbs specific to the platform, such as “click”, “tap”, or “touch”.

For more information, see the [Touch Gesture Reference Guide](http://www.lukew.com/ff/entry.asp?1071).

### URLs
Write URLs beginning with the **wire.com** domain, and without the trailing slash — _most modern browsers will add this automatically if necessary_.

For example, write _wire.com/privacy_, instead of:

* wire.com/privacy**/**
* ~~www.~~wire.com/privacy
* ~~http://www.~~wire.com/privacy

## Reference resources

In addition to the platform-specific resources described under [UI Copy](#ui-copy), the following resources provide useful reference.

> For guidance on Apple-specific terminology, the writer should refer to the Apple Style Guide. That document covers style and usage issues, and is the key reference for how Apple uses language.

* Apple Style Guide – <https://help.apple.com/asg/mac/2013/>

For complete punctuation rules and other writing conventions, refer to these style guides:

* The Chicago Manual of Style
* The Yahoo Style Guide

---

[iOS-HIG]:  https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/

[OSX-HIG]:  https://developer.apple.com/library/mac/documentation/UserExperience/Conceptual/OSXHIGuidelines/