# Unihan Database

The purpose of this repository is for reviewing draft Unihan database changes, removals, and additions by experts.

Each provisional Unihan database property currently being worked on has its own data file. At the moment, these are:

- [kCantonese](https://unicode.org/reports/tr38/#kCantonese).txt
- [kDefinition](https://unicode.org/reports/tr38/#kDefinition).txt
- [kMeyerWempe](https://unicode.org/reports/tr38/#kMeyerWempe).txt
- [kSpoofingVariant](https://unicode.org/reports/tr38/#kSpoofingVariant).txt
- [kZVariant](https://unicode.org/reports/tr38/#kZVariant).txt

Also included is the *CantoneseLookup.txt* file, which is an aid to editors of the *kCantonese* property, and includes ideographs for which a Cantonese reading is known to exist, but whose Cantonese reading has not been confirmed by an authoritative source.

Changes to properties that are not provisional require UTC approval. As such, the appropriate way to request changes to non-provisional properties is by [preparing and submitting a proposal](https://www.unicode.org/pending/docsubmit.html), or submitting feedback via the [Contact Form](https://corp.unicode.org/reporting.html), not by submitting a pull request, or creating a new issue in this repository.

The *format* for the data files in this repository is exactly as they appear in the Unihan database, using tabs to delimit the three fields, but with the actual ideograph following the code point in the first column to ease review. For example:

`U+4E95 井	kCantonese	zeng2`

Please use the `#unihan` channel in the Unicode Consortium’s Slack organization for general discussions, or for requesting that other property data files be added to this repository.

Please use the `#cantonese` channel in the Unicode Consortium’s Slack organization for discussions regarding *kCantonese* property values.

### License

The data files in this repository are governed by the terms of the [Unicode, Inc. License Agreement](https://www.unicode.org/license.html), a copy of which is included as [LICENSE](./LICENSE.md).

### Copyright and Terms of Use

Copyright © 1991–2021 Unicode, Inc. All rights reserved. See [Unicode Copyright and Terms of Use](http://www.unicode.org/copyright.html).
