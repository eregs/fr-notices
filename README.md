fr-notices
==========

This is part of the [eRegulations](https://eregs.github.io/) project.

In some cases, we edit the XML for a Federal Register notice to make it easier
to parse with
[regulations-parser](https://github.com/eregs/regulations-parser). This
repository is a canonical place to store those edits, across all agencies, so
that developers remain in sync.

**Note**: These are unofficial changes. All official notices are available
through the [Federal Register](https://www.federalregister.gov/) - for
example, [here are CFPB
notices](https://www.federalregister.gov/agencies/consumer-financial-protection-bureau).

## Usage

Use these notices with regulations-parser as part of eRegulations.

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)

## Migration

The Federal Register recently reworked their URL scheme, which invalidates
filenames. Notably, we need to move the contents of the `articles` directory
into `documents/full_text` and rename each file. Rather than move these all
over at once, we'll move them as needed to get an accounting of what files are
still used.
