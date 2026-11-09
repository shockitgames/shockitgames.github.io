# Shockit Games — GitHub Pages files

Public website files for `shockitgames/shockitgames.github.io`.

The website files cover a studio homepage, privacy-policy pages for
Bloom & Bow, Ant & Kanji and FactFlip, Ant & Kanji data deletion
information, and a shared player support page.

The supplied website uses no JavaScript, external fonts, or analytics scripts.
Review this statement if the website implementation changes.

## Repository files

- `index.html` — studio homepage; the previously supplied version features Bloom & Bow and Ant & Kanji
- `styles.css` — shared website styling
- `support.html` — shared player support page
- `bloom-and-bow-privacy.html` — Bloom & Bow privacy policy
- `bloom-and-bow.svg` — Bloom & Bow artwork
- `ant-and-kanji-privacy.html` — Ant & Kanji privacy policy
- `ant-and-kanji-deletion.html` — Ant & Kanji data deletion information
- `ant-and-kanji-icon.png` — Ant & Kanji artwork
- `factflip-privacy.html` — FactFlip privacy policy
- `README.md` — repository documentation

Adding FactFlip's privacy page does not automatically add a FactFlip section
to the homepage. Update `index.html` separately when adding its game listing,
artwork and privacy link. Preserve the existing games and any newer edits.

## Uploading updates

1. Open the repository's **Code** tab, then **Add file → Upload files**.
2. Upload individual website files directly into the repository root.
   Do not upload a ZIP or an extra enclosing folder.
3. For the FactFlip privacy update, upload `factflip-privacy.html`.
4. Upload this `README.md` to replace the older repository documentation.
5. Keep the existing Bloom & Bow and Ant & Kanji policies, artwork,
   deletion information and shared support page.
6. Replace shared files such as `styles.css`, `support.html` or `index.html`
   only when intentionally updating them. Compare with the current files
   first to preserve newer changes.
7. Commit changes to the repository's publishing branch. A suitable commit
   title for this README is **Update README to include FactFlip**.
   The extended commit description is optional.
8. If GitHub Pages is already working, retain its existing configuration.
   For a new branch-based setup, configure **Settings → Pages** to publish
   from **main → / (root)**, or use the repository's intended Pages workflow.
9. Wait for the deployment to finish in **Actions**.
10. Open the public pages in a signed-out/private browser window and confirm
    they load without requesting access.

Updating `README.md` changes repository documentation. Updating `index.html`
changes the website homepage. Neither action changes the Android games.

## Public addresses

| Page | Address |
| --- | --- |
| Homepage | https://shockitgames.github.io/ |
| Bloom & Bow privacy policy | https://shockitgames.github.io/bloom-and-bow-privacy.html |
| Ant & Kanji privacy policy | https://shockitgames.github.io/ant-and-kanji-privacy.html |
| Ant & Kanji data deletion information | https://shockitgames.github.io/ant-and-kanji-deletion.html |
| FactFlip privacy policy | https://shockitgames.github.io/factflip-privacy.html |
| Player support | https://shockitgames.github.io/support.html |

These are deployment addresses. Their presence in this README does not
confirm that every page has been published or verified.

Use each game's own privacy-policy address in its store listing and in-game
links after confirming that the public page loads correctly.

For FactFlip, use:

**https://shockitgames.github.io/factflip-privacy.html**

## Support and privacy contact

**shockitgames@gmail.com**

Players should include the game name, device model, app version, what happened
and the steps needed to reproduce a problem. Reports should not include
passwords, signing keys or other credentials.

## Policy review scope

Each game's policy must match its actual released Android build, enabled SDKs,
account features, advertising behaviour and support process.

### Bloom & Bow

The original Bloom & Bow policy was prepared on 18 October 2026.
Its preparation notes described a 13+ intended audience, guest/local progress,
optional Google rewarded ads and UMP privacy tools, with Google sign-in and
cloud synchronization inactive at that time. These are historical review
notes, not confirmation of current behaviour.

### Ant & Kanji

Ant & Kanji has its own policy and deletion information. Do not automatically
apply Bloom & Bow's audience declaration or account and advertising
configuration to Ant & Kanji.

### FactFlip

FactFlip has its own privacy policy. Its release preparation dated
9 November 2026 uses local gameplay progress without accounts, advertising,
analytics or developer-operated cloud synchronization. Quiz content, artwork
and sounds are included for offline play. External reference, privacy and
support links open in the player's browser.

Copy controls place selected information on the device clipboard. Fact and
technical reports are not sent automatically; players choose whether to
share them. Support correspondence is handled through the studio's contact
email as described in FactFlip's policy.

The prepared release export disables Android app backup. Verify the final
exported application's manifest and actual device behaviour before relying
on that configuration. Reset Saved Progress removes local game and learning
progress while keeping settings; Android's Clear app data can remove settings
and saves. There is no in-game cloud restore in this preparation.

These notes describe the prepared source, not independent confirmation of a
signed release binary. Recheck the policy and store declarations if ads,
accounts, analytics, cloud saves or other data handling are added.

### Review before any release

Before releasing any game, review its policy and store disclosures against
the final exported build. Update them when enabling or changing advertising
providers, analytics, accounts, cloud saves or other data handling.

Confirm that the published deletion instructions match the available in-game
controls and the support process the studio can actually provide.

The documents do not guarantee store approval or legal compliance.

## Advertising configuration

Do not add a guessed `app-ads.txt` entry.

If required, copy the authorized-seller entry supplied by the actual AdMob
account and publish it as `app-ads.txt` at the website root.

Website publication alone does not enable live ads, Google sign-in, cloud
saves or other game services. Configure and verify these separately in each
game. FactFlip's current release preparation contains no advertising SDK.

## Validation before release

- Confirm all public pages open without authentication.
- Check page titles, game names and contact details.
- Check navigation links and images.
- Check readability on desktop and mobile.
- Confirm the homepage lists only games and features intentionally presented.
- Review policy wording against each game's final Android build.
- Confirm the in-game privacy links open the correct game's policy.
- Enter each game's verified policy URL in its own Google Play listing.
- Review support instructions so players can identify the correct game.

These are checks to perform, not a claim that they have all passed.

## References

- GitHub Pages: https://docs.github.com/en/pages/quickstart
- Google Play User Data policy: https://support.google.com/googleplay/android-developer/answer/10144311
- Google privacy policy: https://policies.google.com/privacy
- Google partner-service information: https://policies.google.com/technologies/partner-sites
- GitHub privacy: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

## Repository safety and licensing

Keep game source archives, Android builds, signing keys, passwords and
credentials out of this public website repository.

No open-source license is granted by this README or website package.
