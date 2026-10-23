# Shockit Games — GitHub Pages files

Public website files for `shockitgames/shockitgames.github.io`.

The website contains a studio homepage, privacy-policy pages for
Bloom & Bow and Ant & Kanji, Ant & Kanji data deletion information,
and a shared player support page.

The supplied website uses no JavaScript, external fonts, or
analytics scripts.

## Repository files

- index.html — studio homepage featuring both games
- styles.css — shared website styling
- support.html — shared player support page
- bloom-and-bow-privacy.html — Bloom & Bow privacy policy
- bloom-and-bow.svg — Bloom & Bow artwork
- ant-and-kanji-privacy.html — Ant & Kanji privacy policy
- ant-and-kanji-deletion.html — Ant & Kanji data deletion information
- ant-and-kanji-icon.png — Ant & Kanji artwork

## Uploading updates

1. Extract the supplied website ZIP on your computer.
2. Open the repository's Code tab, then Add file → Upload files.
3. Upload individual website files directly into the repository root.
   Do not upload the ZIP itself or an extra enclosing folder.
4. For the Ant & Kanji update, add:
   - ant-and-kanji-privacy.html
   - ant-and-kanji-deletion.html
   - ant-and-kanji-icon.png
5. Upload the updated index.html to show both games on the homepage.
   Compare it with the existing homepage first to preserve any newer edits.
6. Keep the existing Bloom & Bow policy, artwork and support page.
   Replace shared files such as styles.css only when intentionally updating them.
7. Commit changes to the repository's publishing branch.
8. If GitHub Pages is already working, retain its existing configuration.
   Otherwise, configure Settings → Pages to publish from main → / (root).
9. Wait for the deployment to finish in Actions.
10. Open the public pages in a signed-out/private browser window and
    confirm they load without requesting access.

Updating README.md changes the repository documentation.
Updating index.html changes the website homepage.

## Public addresses

- Homepage:
  https://shockitgames.github.io/
- Bloom & Bow privacy policy:
  https://shockitgames.github.io/bloom-and-bow-privacy.html
- Ant & Kanji privacy policy:
  https://shockitgames.github.io/ant-and-kanji-privacy.html
- Ant & Kanji data deletion information:
  https://shockitgames.github.io/ant-and-kanji-deletion.html
- Player support:
  https://shockitgames.github.io/support.html

These are deployment addresses. Their presence in this README does
not confirm that every page has been published or verified.

Use each game's own privacy-policy address in its store listing and
in-game links after confirming the public page loads correctly.

## Support and privacy contact

shockitgames@gmail.com

## Policy review scope

Each game's policy must match its actual released Android build,
enabled SDKs, account features, advertising behaviour and support process.

The original Bloom & Bow policy was prepared on 18 October 2026.
Its preparation notes described a 13+ intended audience, guest/local
progress, optional Google rewarded ads and UMP privacy tools, with
Google sign-in and cloud synchronization inactive at that time.
These are historical review notes, not confirmation of current behaviour.

Ant & Kanji has its own policy and deletion information.
Do not automatically apply Bloom & Bow's audience declaration or
account and advertising configuration to Ant & Kanji.

Before releasing either game, review its policy and store disclosures
against the final exported build. Update them when enabling or changing
advertising providers, analytics, accounts, cloud saves, or other
data handling.

Confirm that the published deletion instructions match the available
in-game controls and the support process you can actually provide.

The documents do not guarantee store approval or legal compliance.

## Advertising configuration

Do not add a guessed app-ads.txt entry.

If required, copy the authorized-seller entry supplied by the actual
AdMob account and publish it as app-ads.txt at the website root.

Website publication alone does not enable live ads, Google sign-in,
cloud saves, or other game services. Configure and verify these
separately in each game.

## Validation before release

- Confirm all public pages open without authentication.
- Check page titles, game names and contact details.
- Check navigation links and images.
- Check readability on desktop and mobile.
- Review policy wording against each game's final Android build.
- Confirm the in-game privacy links open the correct game's policy.

These are checks to perform, not a claim that they have all passed.

## References

- GitHub Pages:
  https://docs.github.com/en/pages/quickstart
- Google Play User Data policy:
  https://support.google.com/googleplay/android-developer/answer/10144311
- Google privacy policy:
  https://policies.google.com/privacy
- Google partner-service information:
  https://policies.google.com/technologies/partner-sites
- GitHub privacy:
  https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

## Repository safety and licensing

Keep game source archives, Android builds, signing keys, passwords,
and credentials out of this website repository.

No open-source license is granted by this README or website package.
