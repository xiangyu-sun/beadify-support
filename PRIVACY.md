# Privacy Policy — Beadify

**Last updated: October 6, 2026**

Beadify is built by Xiangyu Sun (sole developer). This policy explains what data the app handles and how.

---

## What Beadify does with your data

### Photos and images

When you import a photo, Beadify converts it into a pixel-art bead pattern entirely **on your device**. Your photos are never uploaded to any server, never shared with third parties, and never stored outside your device or your personal iCloud account.

### Patterns you create

Your bead patterns are saved locally using Apple's SwiftData framework. If you are signed into iCloud, patterns are automatically synced to your private iCloud account via Apple's CloudKit. Only you can access your iCloud data — Xiangyu Sun has no access to it.

### Camera

If you use the "Take Photo" option, the image is processed immediately and converted to a bead pattern. No photo is retained beyond what you explicitly save.

---

## Analytics (iPhone, iPad and Mac)

Beadify uses **Google Firebase Analytics** to understand which features are used (for example: which palette or grid size was picked, whether a pattern was exported). This helps decide what to improve. Firebase collects:

- App interactions (the events above) and app version
- Device type, OS version and approximate (country/region-level) location derived from your IP address
- A random app-instance identifier, used to count unique installs

Analytics data is **not linked to your identity**, contains no photos, pattern contents, names or contact details, and is not sold. See [Google's privacy policy](https://policies.google.com/privacy) and [how Google uses data from apps](https://policies.google.com/technologies/partner-sites).

## Advertising (iPhone and iPad only)

Beadify is free. On iPhone and iPad it shows a small banner ad served by **Google AdMob**. The Mac app has no ads.

- **Consent:** in the EEA, UK and Switzerland (and other regions where required), you are asked for consent through Google's consent form before personalised ads are shown. You can change your choice anytime under **••• → Privacy Choices**.
- **Tracking (App Tracking Transparency):** Beadify asks permission before AdMob may use your device's advertising identifier (IDFA). If you choose "Ask App Not to Track", ads are still shown but are not personalised using the IDFA. You can change this in **Settings → Privacy & Security → Tracking**.
- AdMob may collect device information, the advertising identifier (only with your permission), approximate location from your IP address, and ad interaction data, to show and measure ads and prevent fraud. See [Google's ads privacy policy](https://policies.google.com/technologies/ads).

### Beadify Pro

**Beadify Pro** is an optional one-time in-app purchase (called "Remove Ads" before version 1.9). It unlocks extra features, such as the board-by-board PDF, and turns ads off permanently on every device signed in with your Apple Account. When ads are off, the advertising SDK isn't started at all and the consent and tracking prompts are not shown. Pro features run entirely on your device, like the rest of the app. Purchases are processed entirely by Apple — Beadify never sees your payment details.

**If you bought Beadify while it was a paid app**, you automatically have Beadify Pro — no purchase needed.

---

## What Beadify does NOT do

- No selling of your data
- No access to your photos beyond the ones you pick
- Your photos and patterns are never uploaded to the developer or to Google
- No account creation or login required
- No data sent to any server operated by the developer

---

## Data stored on your device

| Data | Where stored | Synced to iCloud? |
|------|-------------|-------------------|
| Bead patterns you save | SwiftData (local) | Yes, if iCloud is enabled |
| App preferences | UserDefaults | No |
| Beadify Pro purchase | Apple (App Store) | Restorable on any device with your Apple Account |
| Photos you import | Not stored — processed in memory only | No |

---

## Children

Beadify is not directed at children under 13. It does not knowingly collect personal information from children, and the developer collects no personal information directly. Ads and analytics are provided by Google as described above.

---

## Changes to this policy

If this policy changes materially, the "Last updated" date above will be updated. The latest version is always at this URL.

---

## Contact

Questions about this policy:
- Email: alexander.xiangyu.sun@gmail.com
- GitHub: https://github.com/xiangyu-sun/beadify-support/issues
