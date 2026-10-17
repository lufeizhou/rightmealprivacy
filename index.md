# RightMeal Privacy Policy

Effective 17 October 2026. Sanvvy, Inc., 8 The Green #12050, Dover, DE 19901, US ("we") publishes RightMeal for iPhone and Apple Watch. Contact: [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com).

## The short version

- There is no account. Your meals, weight goal and weight history are stored **only on your devices**.
- A meal leaves your iPhone only when you ask for a verdict, and only after you tap **Allow** on the screen that explains what is sent. You can turn this off in **Settings › Instinct**.
- We do not sell your data, show ads, or track you across apps or websites.

## What stays on your device

- Meals you log: your words, the recording of a spoken take, the photo if you take one, the time, and any verdict.
- Your weight goal (lose, maintain or gain) and its weekly pace; your weigh-ins and target weight, if you log them.
- Health data read from Apple Health (steps, sleep, workouts, stand minutes, cardio fitness/VO₂ max), cached locally so the app works offline.
- Your preferences (appearance, units, dictation language).
- A counter of free verdicts used, kept in the iPhone's Keychain. Unlike the rest, it **survives deleting and reinstalling the app**, so the free allowance can't be reset. It holds a number only.

Speech is transcribed on your device by Apple's speech recognition. Recordings never leave your devices. The Apple Watch app sends your take to your iPhone only.

We never write to Apple Health, never store health data in iCloud, and never use health data for advertising or marketing.

## What is sent, to whom, and why

Only when you ask for a verdict and only after you allowed it (the one exception: when you first open the app, it sends our relay the random app key described below, so your first verdict is fast; nothing else goes with it):

| Recipient | What | Why |
|---|---|---|
| **Our relay server** (run on Cloudflare) | everything in the TypeSafe row, passed straight through and not stored or logged; your IP address, as with any web request, not stored; a random key your iPhone creates when the app is installed, which proves the request comes from the genuine app. We keep that key with a count of today's requests to limit misuse. It is not linked to you and is replaced when you reinstall the app | to protect the service from misuse and forward the request to TypeSafe |
| **TypeSafe** ([typesafe.ai](https://typesafe.ai)), which runs the model behind "Instinct" | the meal in words and the time, and its photo if you add one (resized, with location and camera details removed); your weight goal and weekly pace, and your current and target weight if you logged them; today's steps, stand minutes and latest workout, last night's sleep and sleep score, your most recent VO₂ max; the meals you already logged today with their verdicts | to produce the verdict for that meal |

Separately, whether or not you ask for verdicts, the app sends anonymous usage statistics to **PostHog** ([posthog.com](https://posthog.com), servers in the United States): that the app was installed and opened, the app and iOS version, the device model, language and region, when the subscription screen was shown, a free trial, purchase or renewal (product, price and App Store country) which kind of error occurred, and, if the app crashes, a crash report (where in the app's code it stopped). These are tied only to a random identifier created when the app is installed; no profile is kept about you, and your IP address is not used to locate you. Your meals, photos, health data and weight are never part of it. We use it only to see how the app is used and where it breaks, never for advertising or tracking.

No name, email or advertising identifier is sent; the only identifiers are the random app key above, which goes to our relay only, and PostHog's random identifier. Each recipient processes the data only for the purpose above, under its own terms and privacy policy: [Cloudflare](https://www.cloudflare.com/privacypolicy/) (for our relay), [PostHog](https://posthog.com/privacy), [TypeSafe](https://typesafe.ai/privacy-policy). TypeSafe states that it does not train or fine-tune AI models on what it receives. Cloudflare handles each request at a data centre near you, and TypeSafe and PostHog process data in the United States, so if you use RightMeal outside the US, this data is transferred there. We require each recipient to protect the data at least as well as this policy does.

Purchases are handled by Apple; we receive only whether your subscription is active, never your payment details.

## Your choices

- **Turn off sending:** Settings › Instinct › Stop Sending Meals. Nothing is sent afterwards; you can keep logging meals without verdicts.
- **Apple Health:** change access in the Health app › Sharing › Apps, or in Settings › Apple Health.
- **Microphone and camera:** iOS Settings › RightMeal. You can always type instead.
- **Delete your data:** deleting the app removes everything stored by it except the free-verdict counter. Our relay passes the meals and health data you send for a verdict on to TypeSafe without keeping them, and nothing sent carries your name or anything that identifies you, so we cannot look it up for you. The random app key and its daily count are replaced when you reinstall the app. To ask about or delete data already sent, contact TypeSafe at [privacy@typesafe.ai](mailto:privacy@typesafe.ai).

## Children

The app is not directed at children under 13 and we do not knowingly collect their data.

## Changes

We will update the effective date and, for material changes, tell you in the app.

## Contact

Sanvvy, Inc. · 8 The Green #12050, Dover, DE 19901, US · [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com)
