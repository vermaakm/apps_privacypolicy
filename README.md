# App Privacy Policy Template

A reusable privacy-policy repository for apps that may use:

- Google AdMob / Google Mobile Ads
- RevenueCat for subscription management
- Google Firebase for authentication, cloud databases, storage, analytics,
  diagnostics, notifications, configuration, or server functions
- Supabase for authentication, database, storage, realtime, or server functions

The contact email is prefilled as `mcvlimited.uk@gmail.com`.

## Purrsuit

- [Purrsuit privacy details](PRIVACY_POLICY.md#app-specific-information-purrsuit)
- [Support and account help](SUPPORT.md)

## Use this policy across your apps

Use [PRIVACY_POLICY.md](PRIVACY_POLICY.md) as the single umbrella policy for every MCV Limited app that links to it. It covers Apps that use AdMob, Firebase, RevenueCat, Supabase, app-store payments, or none of those services. Each App still needs accurate App Store App Privacy / Google Play Data Safety disclosures and, where it materially differs from the umbrella policy, a short app-specific privacy notice.

## Before publishing

1. Copy `PRIVACY_POLICY_TEMPLATE.md` to a policy page for the specific app.
2. Replace every `[[PLACEHOLDER]]` and delete every section that does not apply.
3. Complete `APP_PRIVACY_CHECKLIST.md` against the app's actual code, SDK configuration, and data flows.
4. Have the final policy reviewed by a qualified privacy professional where appropriate. This is a practical template, not legal advice.
5. Host the policy at a stable public HTTPS URL and enter that URL in App Store Connect and/or Google Play Console.

## Important accuracy rules

- Do not claim that data is never shared if AdMob, Firebase, RevenueCat, Supabase, analytics, crash reporting, sign-in, or other SDKs receive data.
- Do not retain a section merely because it appears in the template. Remove unused integrations and describe the data your app actually collects.
- Review the App Store App Privacy and Google Play Data Safety disclosures separately; the exact disclosures depend on each app's SDKs and configuration.

## Helpful primary sources

- [Google Mobile Ads privacy guidance](https://developers.google.com/admob/flutter/privacy)
- [RevenueCat Apple App Privacy guidance](https://www.revenuecat.com/docs/platform-resources/apple-platform-resources/apple-app-privacy)
- [Firebase privacy and security information](https://firebase.google.com/support/privacy)
- [Supabase privacy notice](https://supabase.com/privacy)
- [Supabase data processing addendum](https://supabase.com/legal/customer-resources/data-processing-addendum)
