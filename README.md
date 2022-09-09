# Unihan Database

The purpose of this repository is for reviewing draft Unihan database changes, removals, and additions by experts.

Each provisional Unihan database property currently being worked on has its own data file. At the moment, these are:

- [kCantonese](https://unicode.org/reports/tr38/#kCantonese).txt
- [kDefinition](https://unicode.org/reports/tr38/#kDefinition).txt
- [kMeyerWempe](https://unicode.org/reports/tr38/#kMeyerWempe).txt
- [kPhonetic](https://unicode.org/reports/tr38/#kPhonetic).txt
- [kSemanticVariant](https://unicode.org/reports/tr38/#kSemanticVariant).txt
- [kSimplifiedVariant](https://unicode.org/reports/tr38/#kSimplifiedVariant).txt
- [kSpoofingVariant](https://unicode.org/reports/tr38/#kSpoofingVariant).txt
- [kTraditionalVariant](https://unicode.org/reports/tr38/#kTraditionalVariant).txt
- [kZVariant](https://unicode.org/reports/tr38/#kZVariant).txt

Additional files included are:

- AlternateRadicals.txt
- CantoneseLookup.txt

*AlternateRadicals.txt* is a list of characters which could reasonably be looked up in a radical-stroke index such as Unicode's under multiple radical-stroke values. Excluded are instances where the radical is the same but stroke counts differ only slightly. For easier editing, the characters for the radicals are generally shown, *e.g.*

`U+61D5 懕	⼼ 61.14	⼚ 27.16`

In all cases, the first value should be considered the standard value as defined in [UAX #38](https://www.unicode.org/reports/tr38/#kRSUnicode).

Simplified radicals are not indicated.

*CantoneseLookup.txt* is an aid to editors of the `kCantonese` property, and includes ideographs for which a Cantonese reading is known to exist, but whose Cantonese reading has not been confirmed by an authoritative source.

Changes to properties that are not provisional require UTC approval. As such, the appropriate way to request changes to non-provisional properties is by [preparing and submitting a proposal](https://www.unicode.org/pending/docsubmit.html), or submitting feedback via the [Contact Form](https://corp.unicode.org/reporting.html), not by submitting a pull request, or creating a new issue in this repository.

The *format* for the data files in this repository is almost exactly as in the Unihan database, using tabs to delimit the three fields, but with the actual ideograph following the code point in the first column to ease review. For example:

`U+4E95 井	kCantonese	zeng2`

Please use the `#unihan` channel in the Unicode Consortium’s Slack organization for general discussions, or for requesting that other property data files be added to this repository.

Please use the `#cantonese` channel in the Unicode Consortium’s Slack organization for discussions regarding *kCantonese* property values.

### License

The data files in this repository are governed by the terms of the [Unicode, Inc. License Agreement](https://www.unicode.org/license.html), a copy of which is included as [LICENSE](./LICENSE.md).

### Copyright and Terms of Use

Copyright © 1991–2022 Unicode, Inc. All rights reserved. See [Unicode Copyright and Terms of Use](http://www.unicode.org/copyright.html).
