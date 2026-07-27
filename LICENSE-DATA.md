# Data licensing

The camp registry's data is open. Three kinds of content, three answers:

## The index database — ODbL 1.0

The index database (everything under `plugins/`, `discovery/`, and the
generated repository metadata such as `packages.json`) is made available
under the [Open Database License 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

In practice: you may copy, redistribute, and build on the database
freely. A **produced work** (a website, storefront, search tool,
install client, or anything else built *from* the data) is yours,
attribution only. A **derivative database** (a replicated, corrected,
or extended copy of the index itself) must be shared under these same
terms. Suggested attribution: "Contains information from the camp
registry (camp-registry.org), made available under ODbL."

## Advisories — CC BY 4.0

Security advisories (everything under `advisories/`) are licensed
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Warnings
should propagate without friction: carry them in any product, mirror,
scanner, or feed, with attribution to the camp registry.

## Author content — the plugin's own license

Listing content that authors provide from their own repositories
(`.camp/listing.yml` names, descriptions, screenshots) and plugin
artifacts themselves remain under each plugin's own license (GPL
family). The registry pins and redistributes them; it does not
relicense them.

## Contributions

Contributions to the index (claim pull requests, entry edits, release
records) are accepted under
[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/); see
[CONTRIBUTING.md](CONTRIBUTING.md). This keeps the project able to
adjust the database license as one party, forever, without a
contributor-consent campaign.
