# MaxCard catalog

The card catalog for the MaxCard iOS app: cards, welcome offers, credits and card paths.
The app downloads `catalog.json` from GitHub Pages and falls back to its bundled copy.

This repo is published from the app's repository with `scripts/publish-catalog.sh`.
Don't edit it here.

Card terms are checked against each issuer's site (see `sourceURL` and `verifiedAt` on
each card) but can change at any time. This is not financial advice.
