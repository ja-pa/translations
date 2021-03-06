# Guidelines: Translating the OONI Probe mobile apps

[OONI Probe](https://ooni.torproject.org/install/) is free and open source
software designed to measure internet censorship and other forms of network
interference. Thanks to great feedback provided by the community, the OONI team
has revamped the OONI Probe mobile apps to improve their design and UI, include
new features, and much more!

**By translating the app, you are enabling your communities to measure their
networks and to increase transparency of internet censorship!**

Translating OONI Probe is therefore important, and the OONI team can't
thank you enough.

We hope the following brief guidelines are helpful. If they're not, please reach
out to us at contact@openobservatory.org.

* [Install the OONI Probe public beta](#install-the-ooni-probe-public-beta)

* [Strings for translation](#strings-for-translation)

* [Style of translation](#style-of-translation)

* [Translation of technical terms](#translation-of-technical-terms)

* [Things to watch out for](#things-to-watch-out-for)

## Install the OONI Probe public beta

Before you get started with the translation, we kindly ask that you first
install the public beta to try out the new OONI Probe mobile app. We also ask
that you use the public beta to see where your translation would appear in the
app.

**Android**

* Sign up to the beta:
https://play.google.com/apps/testing/org.openobservatory.ooniprobe

* Update your OONI Probe mobile app (to get the public beta) from Google Play

**iOS**

* Tap on this link from your device and follow the instructions:
https://testflight.apple.com/join/rh3Ig7fE

## Strings for translation

Thanks to support from the [Localization Lab](https://www.localizationlab.org/),
the translation of the OONI Probe mobile apps is coordinated on Transifex.

To translate the OONI Probe mobile apps, please sign-up with Transifex and
request to get added to the OONI project:
https://www.transifex.com/otf/ooniprobe/

Once you've been added, you can translate the strings included in the following
2 files:

* App store copy: https://www.transifex.com/otf/ooniprobe/description/

* In-app copy: https://www.transifex.com/otf/ooniprobe/strings-json/

## Style of translation

The copy in the apps is meant to be **informal and direct (but still polite)**.

We therefore share the following recommendations:

* Use the informal form when referring to the user (for example, the singular
form of "you", instead of the plural form for formality)

* Use gender-neutral terminology when referring to the user

* Be concise (but clear) to fit the translation within the character limits
(many of which are set by the app stores)

* Avoid direct translation (such as that of "Heads-up!") if it doesn't make
sense in the translated language

* When/if possible, think about localization beyond translation (for example, you can include "GR"
as the country code for "Greece" in the Greek translation) - without changing
the meaning or adding any new information that may be inaccurate

## Translation of technical terms

OONI Probe has a fair amount of technical terminology.

Here are some tips:

1. Please **avoid translating** the OONI Probe test names (you can keep the
English versions):

* Web Connectivity

* WhatsApp

* Facebook Messenger

* Telegram

* HTTP Header Field Manipulation

* HTTP Invalid Request Line

* NDT

* DASH

2. You can consider **avoiding the translation of "middleboxes"**, since this
term is often used *as is* by the international tech community.

3. Not all technical terms (such as caching, ping, endpoints, etc) are
translated by tech communities around the world (particularly if their
translation does not make much sense). **Often, such terms are used in English,
or they're Englishized.** If you're unsure how specific technical terms are used
in your language by technologists, you can try Googling in your language for
those terms (for example, by checking relevant publications), or reach out to a
technologist (if you know one).

We also advise against the translation of "OONI" and "OONI Probe".

## Things to watch out for

*  **Character limits:** Some strings have character limits because they are
either required by the app stores, or by the UX of OONI Probe (only a
certain amount of characters, for example, can fit in a button). We
therefore kindly ask that you try to be concise, while still clearly and
accurately conveying the meaning in the translation.

* **Use of singular & plural forms:** Once you get started with the translation,
you'll probably notice that several strings appear to have duplicate copy
(such as those for terms like "tested", "blocked", "accessible"). These
aren't duplicates, as they are meant to support both the singular and plural
forms of verbs (for many languages, other than English). Please pay
attention to the comments provided inside the strings, indicating whether a
term should be translated to singular or plural form.

* **Composite strings:** You'll come across certain strings that include
variables, such as: `{{Count}} categories enabled`. This means that a number (or
another variable) will appear in the app in the place of `{[Count}}` (for
example, `3 categories enabled`). Please do *not* translate these variables, but
position them in the location where they would make sense in the translated sentence.

* **New lines:** You'll notice that some blue arrows are included in some
strings. These arrows indicate that the next sentence will be in a new line.
Please preserve these arrows in your translation in the same order as
provided in the original copy.

* **Punctuation marks:** Please try (to the degree possible) to preserve the
same punctuation marks (commas, exclamation marks, etc.) as those included
in the original copy.



Questions? You can reach the OONI team for real-time discussion on
[Slack](https://slack.openobservatory.org/), or you can drop us an email at
contact@openobservatory.org.

**Thank you for your support! We are extremely grateful!**
