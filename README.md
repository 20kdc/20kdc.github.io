# Hello!

Anything you see here is available at <https://github.com/20kdc/20kdc.github.io> under the Unlicense unless:

* Otherwise noted (check README and LICENSE files in containing directories)
* It's something brought in externally which might be under its own license. Check workflow details.

This repository exists for two reasons.

## Reason A

So, certain social chat platforms have restrictions on what URLs are considered "trusted".

These restrictions appear to have been built from the perspective of preventing IP scraping.

## Reason B

GitHub Packages requires you login with a token to download packages. This is unacceptable for developer onboarding, so I used Pages instead.

This is done via CI, so you can verify where the packages are coming from yourself! See `build` and `download-all-published-artifacts`.

Current packages hosted:

* `t20kdc.era3:era3-github-workaround-plumbing`: This is a dummy package generated to make this whole thing work.
* `t20kdc.datum:datum`: See <https://github.com/20kdc/datum>.