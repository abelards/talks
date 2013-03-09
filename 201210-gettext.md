# GetText
Translations are hard.
This is how we use GetText, a Unix standard, instead of Rails-I18N.

## Why?
* because you'll need I18N someday
    * hard to add later
    * get a working default
    * don't juggle with natural text and technical keys

* GetText is a very mature UNIX standard

## How?
* horror stories: what you will have to manage
    * grammar: number, gender, case
    * conjugation: person, tense, mood, voice, aspect

* GetText code
    * what are these files? .po translations, .mo compiled
    * **setup:** remember to set at least one locale
    * **use:** _('text'), _('text with %{var}') % {var: 'interpolation'}
    * **tricks:** forms & context keys

## What?
* tools around GetText: POEdit, editor modes
* alternatives


