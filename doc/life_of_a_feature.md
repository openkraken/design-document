# A lifecircle of a new feature

## From a issue

All new features are start from a new issue. This issue can be issued by any person in kraken repo, or some hardcore problems which everyone are facing.

## Proposal

If a member of kraken team are interested in one issue. He/She can submit a proposal to solve this problem.

The doctype of proposal should follow the [GitHub flavored Markdown format](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown) rules and fileType should ended with `.md`.

When a proposal are submited, it should contains a link to the original issue.

All new proposal should put into the `working` directory.

## Vote

Before new proposal are implemented, it should be voted by [Kraken TSC](https://github.com/openkraken/TSC).

When half of team members are approved, this proposal are accepted, can be moving to the next stage.

## Implement details

The author of proposal or other team members should add more details to this proposal, including API design and side effect to exist components.

It this proposal are too complex, other TSC members can invite to collaborate with.

All new implemented PR should link to original issue and proposal issue.

## Test

New features must have identify tests, including API test, performance test. It's unnessary to cover every corner of situations but all core features.

## Publish

When new feature are published, The team should keep tracking the following works:

1. Help other team member to understand this feature.
2. Ads to external
3. Update our docs.
4. Publish a new release version.

Move release features's document into `accepted` folder.
