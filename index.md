# PlateCall Privacy Policy

Effective 27 September 2026. Sanvvy, Inc., 8 The Green #12050, Dover, DE 19901, US ("we") publishes PlateCall for iPhone and Apple Watch. Contact: [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com).

## The short version

- There is no account. Your meals, profile and weight history are stored **only on your devices**.
- A meal leaves your iPhone only when you ask for a verdict, and only after you tap **Allow** on the screen that explains what is sent. You can turn this off in **Settings › About**.
- We do not sell your data, show ads, or track you across apps or websites.

## What stays on your device

- Meals you log: your words, the recording of a spoken take, the time, and any verdict.
- Your profile: year of birth, sex, height; your weigh-ins, target weight and weekly pace.
- Health data read from Apple Health (steps, sleep, workouts, stand and exercise minutes, cardio fitness/VO₂ max), cached locally so the app works offline.
- Your preferences (appearance, units, dictation language).
- A counter of free verdicts used, kept in the iPhone's Keychain. Unlike the rest, it **survives deleting and reinstalling the app**, so the free allowance can't be reset. It holds a number only.

Speech is transcribed on your device by Apple's speech recognition. Recordings never leave your devices. The Apple Watch app sends your take to your iPhone only.

We never write to Apple Health, never store health data in iCloud, and never use health data for advertising or marketing.

## What is sent, to whom, and why

Only when you ask for a verdict and only after you allowed it:

| Recipient | What | Why |
|---|---|---|
| **Our relay server** (run on Cloudflare) | everything in the TypeSafe row, passed straight through and not stored or logged; your IP address, as with any web request, not stored; a random key your iPhone creates when the app is installed, which proves the request comes from the genuine app. We keep that key with a count of today's requests to limit misuse. It is not linked to you and is replaced when you reinstall the app | to protect the service from misuse and forward the request to TypeSafe |
| **TypeSafe** ([typesafe.ai](https://typesafe.ai)), which runs the model behind "Instinct" | the meal in words and the time; your age, sex and height; current and target weight and weekly pace; today's steps, stand minutes and latest workout, last night's sleep and sleep score, your most recent VO₂ max; today's weather; the meals you already logged today with their verdicts | to produce the verdict for that meal |
| **ipinfo.io** | your IP address | to find an approximate city for the weather |
| **Apple (WeatherKit)** | that approximate location | to get the day's forecast |

Separately, whether or not you ask for verdicts, the app sends anonymous usage statistics to **TelemetryDeck** ([telemetrydeck.com](https://telemetrydeck.com)): that the app was opened and for how long, the app and iOS version, the device model, language and region, when the subscription screen was shown, a purchase or free trial (product, price and App Store country) and which kind of error occurred. These are tied to a random identifier that is salted and hashed on your iPhone before it is sent, so neither we nor TelemetryDeck can tell who you are. Your meals, health data and weight are never part of it. We use it only to see how the app is used and where it breaks, never for advertising or tracking.

No name, email or advertising identifier is sent; the only identifiers are the random app key above, which goes to our relay only, and TelemetryDeck's hashed identifier. Each recipient processes the data only for the purpose above, under its own terms and privacy policy: [Cloudflare](https://www.cloudflare.com/privacypolicy/) (for our relay), [TelemetryDeck](https://telemetrydeck.com/privacy/), [TypeSafe](https://typesafe.ai/privacy-policy), [ipinfo.io](https://ipinfo.io/privacy-policy), [Apple](https://www.apple.com/legal/privacy/). TypeSafe states that it does not train or fine-tune AI models on what it receives. Cloudflare handles each request at a data centre near you, and TypeSafe and ipinfo.io process data in the United States, so if you use PlateCall outside the US, this data is transferred there. We require each recipient to protect the data at least as well as this policy does.

Purchases are handled by Apple; we receive only whether your subscription is active, never your payment details.

## Your choices

- **Turn off sending:** Settings › About › Get Meal Verdicts. Nothing is sent afterwards; you can keep logging meals without verdicts.
- **Apple Health:** change access in the Health app › Sharing › Apps, or in Settings › Apple Health.
- **Microphone:** iOS Settings › PlateCall. You can always type instead.
- **Delete your data:** deleting the app removes everything stored by it except the free-verdict counter. Our relay passes the meals and health data you send for a verdict on to TypeSafe without keeping them, and nothing sent carries your name or anything that identifies you, so we cannot look it up for you. The random app key and its daily count are replaced when you reinstall the app. To ask about or delete data already sent, contact TypeSafe at [privacy@typesafe.ai](mailto:privacy@typesafe.ai), or ipinfo.io through its [privacy policy](https://ipinfo.io/privacy-policy).

## Children

The app is not directed at children under 13 and we do not knowingly collect their data.

## Changes

We will update the effective date and, for material changes, tell you in the app.

## Contact

Sanvvy, Inc. · 8 The Green #12050, Dover, DE 19901, US · [lufei.zhou@sanvvy.com](mailto:lufei.zhou@sanvvy.com)
