# Goblin Workshop

Public game and privacy pages for Goblin Workshop by SinSoft Studios. Matches the static HTML layout and `docs/` structure used by Another Tabata App.

## GitHub Pages

After committing and pushing to `main`, choose **Settings > Pages > Deploy from a branch**, branch **main**, folder **/docs**. No build is required. `docs/.nojekyll` disables Jekyll processing.

Expected addresses once hosting is enabled:

- Home: https://sinsoft-studios.github.io/GoblinWorkshop/
- Privacy policy: https://sinsoft-studios.github.io/GoblinWorkshop/privacypolicy/goblinworkshop.html

Use the privacy-policy address in the game and store listing. Keep internal links relative.

## Privacy and monetization planning

The current development game has local progress and recovery saves, with no ads, billing, accounts, cloud synchronization, analytics, or crash-reporting integration. The policy separates this from planned AdMob rewarded ads and possible purchases. It does not promise a purchase catalog or restoration system that has not been implemented.

Audience remains undecided. Teens and adults (13+) is a recommendation to evaluate against the actual design and marketing, not an approved age restriction. A store content rating is separate from the intended audience. Finalize audience, regional age treatment, and child/teen protections before monetization. Do not assume 13+ permits personalized ads for minors.

Before enabling ads, confirm SDK/providers, consent and withdrawal controls, age treatment, reward behavior, and store ads/Data safety disclosures. Before enabling purchases, document the store, verification services, transaction data, retention, deletion, refunds, and restoration. Revise the public policy to match the released implementation, including any future server or cloud services.

References:

- [Google Play audience guidance](https://support.google.com/googleplay/android-developer/answer/9867159?hl=en)
- [Google Play Families policy](https://support.google.com/googleplay/android-developer/answer/9893335?hl=en)
- [AdMob privacy and consent](https://developers.google.com/admob/android/privacy)
- [AdMob SDK data disclosure](https://developers.google.com/admob/android/privacy/play-data-disclosure)
- [AdMob guidance on European privacy and younger users](https://support.google.com/admob/answer/7666366?hl=en)

This repository contains public pages only. Keep implementation in the game project and never add credentials, private project information, or player data here.
