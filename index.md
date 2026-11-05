# RightMeal Privacy Policy

Effective 6 November 2026. Sanvvy, Inc., 8 The Green #12050, Dover, DE 19901, US ("we") publishes RightMeal for iPhone. Contact: [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com).

## The short version

- There is no account. Your meals, weight goal, weight history and GLP-1 details are stored **only on your iPhone**.
- A meal leaves your iPhone only when you ask for a verdict, and only after you tap **Allow** on the screen that explains what is sent. You can turn this off in **Settings › RightMeal Pro**.
- We do not sell your data, show ads, or track you across apps or websites.

## What stays on your device

- Meals you log: your words, the recording of a spoken take, the photo if you take one, the time, and any verdict.
- Your weight goal (lose or maintain) and its weekly pace; your weigh-ins and target weight, if you log them.
- Your GLP-1 details: which medicine (by its generic name), your dose schedule, strength and appetite, the doses you log (with their strength and injection site, if you pick them), your daily side-effect check-ins, and how meals sat if you tell the app.
- Steps read from Apple Health, cached locally so the app works offline. Weight, lean body mass and body fat (from a smart scale, say) are read from Apple Health each time Your GLP-1 shows them, and no copy is kept. If you share medicines from Apple Health, the app reads when you took your GLP-1 doses each time it needs it and keeps no copy.
- Your preferences (appearance, units, dictation language).
- A counter of free verdicts used, kept in the iPhone's Keychain. Unlike the rest, it **survives deleting and reinstalling the app**, so the free allowance can't be reset. It holds a number only.

Speech is transcribed on your device by Apple's speech recognition. Recordings never leave your iPhone.

We never write to Apple Health, never store health data in iCloud, and never use health data for advertising or marketing.

## What is sent, to whom, and why

Only when you ask for a verdict and only after you allowed it (the one exception: when you first open the app, it sends our relay the random app key described below, so your first verdict is fast; nothing else goes with it):

| Recipient | What | Why |
|---|---|---|
| **Our relay server** (run on Cloudflare) | everything in the TypeSafe row, passed straight through and not stored or logged; your IP address, as with any web request, not stored; a random key your iPhone creates when the app is installed, which proves the request comes from the genuine app. We keep that key with a count of today's requests to limit misuse. It is not linked to you and is replaced when you reinstall the app | to protect the service from misuse and forward the request to TypeSafe |
| **TypeSafe** ([typesafe.ai](https://typesafe.ai)), which runs the model behind RightMeal's verdicts | the meal in words and the time, and its photo if you add one (resized, with location and camera details removed); your weight goal and weekly pace, and your current and target weight if you logged them; today's steps; the meals you already logged today with their verdicts; that you take a GLP-1 medicine, weekly or daily, how many days since your last dose, which step of its strengths you're on and for how long (never the medicine's name); your appetite setting; today's side-effect check-in (for example, mild nausea); meals from the last week you said sat badly, with how they sat | to produce the verdict for that meal |

Separately, whether or not you ask for verdicts, the app sends anonymous usage statistics to **TelemetryDeck** ([telemetrydeck.com](https://telemetrydeck.com), servers in the European Union): that the app was opened (once per session), the app and iOS version, the device model, language and region, whether the app came from TestFlight or the App Store, when the subscription screen was shown, whether meal reminders were turned on or off, a free trial, purchase or renewal (product, price and App Store country), and which kind of error occurred. These are tied only to an identifier your iPhone makes by scrambling (hashing) a random number created when the app is installed; TelemetryDeck never stores your IP address, and no profile is kept about you. No crash reports are sent. Your meals, photos, health data and weight are never part of it. We use it only to see how the app is used and where it breaks, never for advertising or tracking.

No name, email or advertising identifier is sent; the only identifiers are the random app key above, which goes to our relay only, and TelemetryDeck's hashed identifier. Each recipient processes the data only for the purpose above, under its own terms and privacy policy: [Cloudflare](https://www.cloudflare.com/privacypolicy/) (for our relay), [TelemetryDeck](https://telemetrydeck.com/privacy/), [TypeSafe](https://typesafe.ai/privacy-policy). TypeSafe states that it does not train or fine-tune AI models on what it receives. Cloudflare handles each request at a data centre near you, TypeSafe processes data in the United States and TelemetryDeck in the European Union, so the data may be transferred outside your country. We require each recipient to protect the data at least as well as this policy does.

Purchases are handled by Apple; we receive only whether your subscription is active, never your payment details.

## Your choices

- **Turn off sending:** Settings › RightMeal Pro › Stop Sending Meals. Nothing is sent afterwards; you can keep logging meals without verdicts.
- **Apple Health:** change access in the Health app › Sharing › Apps, or in Settings › Apple Health; choose which medicines to share in Settings › Your GLP-1.
- **Microphone and camera:** iOS Settings › RightMeal. You can always type instead.
- **Delete your data:** deleting the app removes everything stored by it except the free-verdict counter. Our relay passes the meals and health data you send for a verdict on to TypeSafe without keeping them, and nothing sent carries your name or anything that identifies you, so we cannot look it up for you. The random app key and its daily count are replaced when you reinstall the app. To ask about or delete data already sent, contact TypeSafe at [privacy@typesafe.ai](mailto:privacy@typesafe.ai).

## Children

The app is not directed at children under 13 and we do not knowingly collect their data.

## Changes

We will update the effective date and, for material changes, tell you in the app.

## Contact

Sanvvy, Inc. · 8 The Green #12050, Dover, DE 19901, US · [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com)

