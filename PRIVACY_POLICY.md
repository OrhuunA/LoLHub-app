# LoLHub Privacy Policy

_Last updated: 2026-07-03_

This document describes what data LoLHub ("the app") collects, stores, and
transmits, and why. It reflects the app's actual current behavior; if that
behavior changes (for example, when ads or subscriptions are added), this
policy will be updated to match before the change ships.

## Summary

LoLHub does not operate its own servers and does not collect or transmit
your data to us. Everything the app stores is kept locally, on your own
computer. The app talks directly to Riot Games' official API (using an API
key you provide), to your local League of Legends client, and to a small
number of third-party image/update services described below.

## What is stored, and where

All of the following is stored **only on your own device**, in the app's
local data folder — never on a server we operate:

- **Account credentials you enter** (League login name and password), used
  solely to fill in the League Client's login form for the app's "auto
  login" convenience feature. These are encrypted at rest on your device.
- **Your Riot Developer API key**, if you provide one, encrypted at rest.
  It is used only to authenticate the app's requests to Riot's official API
  on your behalf.
- **Match history, opponent, and prior-encounter data** the app fetches
  from Riot's API for accounts you track and opponents you've faced — cached
  locally so the app doesn't need to re-fetch it every time.
- **App settings** (e.g. your preferred server region, UI preferences).
- **Application logs**, kept locally to help diagnose problems, containing
  request metadata (e.g. which Riot API endpoint failed and why) but never
  your API key or account password.

## Where data is sent, and to whom

- **Riot Games' official API** (`*.api.riotgames.com` and regional
  equivalents): the app sends your API key and relevant identifiers (Riot
  ID, PUUID) to fetch rank, match history, mastery, and live-game data. This
  is governed by [Riot Games' own privacy policy](https://www.riotgames.com/en/privacy-notice).
- **Your local League of Legends client** (a connection to
  `127.0.0.1`/localhost only): used for auto-login and to detect game state
  (e.g. champ select, in-game). This never leaves your machine.
- **Data Dragon / Community Dragon** (Riot's public CDN for champion
  images): no account-identifying data is sent — these are simple, anonymous
  image requests.
- **LeagueOfGraphs.com**: only if you explicitly click the "View on
  LeagueOfGraphs" button, which opens your browser to that site with the
  relevant Riot ID in the URL. The app does not otherwise contact this site.
- **GitHub Releases**: used for update checks (not yet active). No personal
  data is included in this request beyond what's needed to check for a
  newer app version.

## What LoLHub does not do

- We do not operate any server that receives or stores your data.
- We do not use any analytics, telemetry, or tracking SDK.
- We do not sell or share your data with third parties for advertising or
  any other purpose.

## If you use LoLHub through Overwolf

If you install LoLHub via the Overwolf platform, Overwolf's own client and
services (and, if the app's optional subscription features are enabled,
Overwolf's payment processor) may separately collect data under their own
privacy policy — see [Overwolf's Privacy Policy](https://www.overwolf.com/privacy-policy/).
This document only covers data handled by LoLHub itself.

## Your data, your control

Because everything is stored locally, you control it directly:

- Deleting the app's data folder removes all locally stored data.
- Removing an account from within the app deletes its cached data.
- Uninstalling the app removes everything it stored, aside from anything
  you've separately exported (e.g. via the app's "Export Accounts" feature).

## Changes to this policy

This policy will be updated whenever the app's actual data practices
change — for example, if monetization features that involve a third-party
payment processor or ad network are added.

## Contact

For questions about this policy, open an issue on the project's GitHub
repository.

## Disclaimer

LoLHub is not endorsed by Riot Games and does not reflect the views or
opinions of Riot Games or anyone officially involved in producing or
managing Riot Games properties. Riot Games and all associated properties
are trademarks or registered trademarks of Riot Games, Inc.
