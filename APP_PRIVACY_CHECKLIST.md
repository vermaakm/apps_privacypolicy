# App-specific privacy checklist

Complete this checklist for every app before publishing its policy and store disclosures.

## Basics

- [ ] App name, publisher legal name, support email, and policy effective date are correct.
- [ ] Every `[[PLACEHOLDER]]` is replaced or removed.
- [ ] The policy is hosted at a stable public HTTPS URL.
- [ ] The policy matches the app's actual current release, including all SDKs.

## AdMob / Google Mobile Ads

- [ ] List the formats used: banner, interstitial, rewarded, native, app-open, or other.
- [ ] Confirm whether personalized ads, mediation, Ad Manager, or any Google signals are enabled.
- [ ] Configure a UMP consent message and an in-app privacy-options entry point where required.
- [ ] Review the current Google Mobile Ads disclosure guidance before completing App Store App Privacy or Google Play Data Safety.
- [ ] Confirm whether the app is child-directed or intended for users under the age of consent; configure the relevant ad-request settings if so.

## RevenueCat / subscriptions

- [ ] List subscription or purchase data used by the app.
- [ ] State whether a RevenueCat App User ID, customer attributes, email, or other identifying attributes are sent.
- [ ] Confirm the retention/deletion process for subscription records and customer attributes.
- [ ] Complete the App Store App Privacy "Purchases" disclosure when RevenueCat is used.

## Supabase

- [ ] List the enabled services: Auth, Postgres database, Storage, Realtime, Edge Functions, Vector, or other.
- [ ] List the exact data fields stored, including any sensitive fields or uploaded files.
- [ ] State the retention period and the deletion method for users.
- [ ] Confirm row-level security and Storage policies prevent users from accessing other users' data.
- [ ] If special-category data, health data, payment-card data, or regulated data is stored, obtain appropriate legal and security review before launch.

## Other collection and sharing

- [ ] Include all analytics, crash reporting, attribution, sign-in, support, push notification, and payment SDKs.
- [ ] Describe data shared with each third party and why.
- [ ] State international transfer, access, deletion, correction, and withdrawal-of-consent procedures that apply to the app.
