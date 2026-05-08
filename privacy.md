# Privacy Policy

**Effective:** May 7, 2026
**Last Updated:** May 7, 2026

This Privacy Policy explains what information we collect when you use Backstage ("we," "us," "our"), how we use it, and the choices you have. It works alongside our [Terms of Service](./terms).

We've tried to write this in plain English. Backstage is **local-first by design** — most of what the app captures stays on your device unless you explicitly opt in to cloud features.

---

## 1. The Short Version

- **Sales data, buyer info, photos, and manifests stay on your device by default.** They're stored locally in the app's encrypted SQLite database.
- **We use Supabase for two things:** validating your beta access code, and (optionally, if you turn it on) syncing your buyer-name cache and show backups across devices.
- **We don't sell your data, ever.** We don't run ads. We don't share your buyer lists with third parties.
- **You can delete everything** by signing out and uninstalling the app, or by emailing us.

---

## 2. What Information We Collect

### 2.1 Information You Provide

- **Beta access code.** When you sign in, we send the code to Supabase to verify it's valid and to check what tier of access it grants.
- **Account info (when applicable).** If we add email/password sign-in in the future, we'll collect your email address and a hashed password.
- **Feedback you send us.** If you email us, we'll have your email and whatever you wrote.

### 2.2 Information Captured From Live Commerce Platforms

When you run a live show, Backstage captures sale, giveaway, and raid events visible in the Whatnot WebView (or other supported platforms in the future). For each captured event, the app stores **on your device**:

- The buyer's public username (handle) and, when resolved, their public display name
- The item title, lot number, and sale price as Whatnot shows them
- Sale timestamp
- An optional screenshot of the moment the sale happened (only if you've turned on snapshots)
- The bin and box you assigned the buyer to

This data is **only what's already publicly visible** during the live show. We don't capture chat messages, viewer lists, or anything else that wouldn't be visible to any viewer of the show.

### 2.3 Information About Your Device

- **Bluetooth printer UUID + name** when you pair a printer (so we can reconnect)
- **App settings** you configure (popup duration, label size, items per box, etc.) — stored in iOS Preferences locally
- **Diagnostic logs** generated locally on your device (helpful when something goes wrong; not transmitted anywhere automatically)

### 2.4 Permissions We Ask For

- **Bluetooth** — to pair and print to your thermal label printer
- **Photo Library** — to attach item photos when prepping listings
- **Camera** — to capture item photos for listings
- **No location, no contacts, no microphone, no health data, no advertising ID.**

---

## 3. How We Use Information

We use the information we collect to:

- Run the Backstage app's core features (capturing sales, assigning bins, printing labels, generating manifests)
- Validate your beta access code
- Reconnect to your last paired printer when you re-open the app
- Sync your data across devices (only when you've explicitly turned on cloud sync)
- Respond when you email us
- Diagnose bugs you report
- Keep the Services secure and prevent abuse

We **do not** use your information to train AI models, sell to advertisers, or build profiles for marketing.

---

## 4. Cloud Sync (Opt-In)

Cloud sync is **off by default**. When you turn it on:

- A **buyer name cache** (handle → resolved display name) is stored in Supabase so you don't have to re-resolve names on a second device
- An **end-of-show backup** of your manifest can be saved to Supabase so you can re-download it if your device is lost

You can turn cloud sync off at any time in Settings. When you do, no further data is uploaded; previously synced data stays in Supabase until you delete it (see Section 8).

---

## 5. Service Providers We Share Data With

We use a small number of providers to run the Services. They only see what they need to do their job, and they're contractually obligated to keep it confidential.

| Provider | What we share | Why |
|---|---|---|
| **Supabase** | Beta access code, optional buyer-name cache, optional show backups | Database hosting + authentication |
| **Apple App Store / TestFlight** | App install + crash data | App distribution + crash reporting |
| **Email provider** (when you write to us) | The contents of your email | So we can reply |

We **do not** share data with advertisers, data brokers, marketers, or any party not listed above.

---

## 6. Third-Party Platforms

Backstage runs *alongside* live commerce platforms — it doesn't replace them. When you open Whatnot inside Backstage:

- **Whatnot collects whatever Whatnot normally collects when you use their service** (cookies, account info, view history, etc.). That's governed by Whatnot's own privacy policy, not ours.
- We don't transmit Whatnot's data to our servers. The capture pipeline reads what's visible on screen and stores it locally on your device.

---

## 7. Data Retention

- **On your device:** data stays as long as the app is installed. Settings can auto-delete past shows after a period you choose (default: 30 days; "Never" is also an option).
- **In Supabase (when cloud sync is on):** data persists until you delete it or until your account is closed.
- **Diagnostic logs:** kept for as long as needed to diagnose issues; typically auto-rotated within the app.

---

## 8. Your Rights and Choices

You can:

- **Turn off cloud sync** in Settings at any time.
- **Delete your local data** by tapping a past show and choosing Delete, or by uninstalling the app (which removes everything stored on your device).
- **Delete your cloud data** by emailing us at backstageliveapp@gmail.com; we'll remove your records from Supabase within 30 days.
- **Export your data** by sharing manifest PDFs from the Past Shows screen.
- **Sign out** at any time, which clears your access code and any cached session.

If you live in California, the EU/UK, or another jurisdiction with data-rights laws (CCPA, GDPR, etc.), you also have the right to:

- Request a copy of the personal data we hold about you
- Ask us to correct it if it's wrong
- Ask us to delete it
- Object to certain processing
- Lodge a complaint with your local data protection authority

To exercise any of these rights, email us at backstageliveapp@gmail.com.

---

## 9. Children

Backstage is not intended for use by anyone under 18. We don't knowingly collect personal information from children. If you believe a child has used Backstage, please contact us and we'll delete the account.

---

## 10. Security

We protect your data with reasonable industry-standard measures:

- TLS encryption for all network traffic (app ↔ Supabase ↔ Whatnot)
- Local SQLite database encrypted at rest using SQLCipher
- iOS Keychain / Preferences for credential storage
- Row-level security policies on Supabase tables

That said, **no system is perfectly secure**. If we discover a breach that affects your data, we'll notify you as required by law.

---

## 11. International Users

Backstage is operated from the United States. If you use the Services from outside the US, your information will be transferred to and processed in the US. By using the Services, you consent to that transfer.

---

## 12. Changes to This Policy

We may update this Privacy Policy from time to time. When we do, we'll update the "Last Updated" date at the top. For meaningful changes, we'll try to give you additional notice — by email, in-app message, or a prominent notice on our site.

If you keep using Backstage after a change takes effect, you're accepting the new Policy. If you don't agree, stop using the Services and email us to delete your data.

---

## 13. Contact

Questions about this Privacy Policy, or want to exercise a right under it?

**Email:** backstageliveapp@gmail.com
**Operator:** Jackie Willome (DBA BackStageLive)
**Address:** 1100 Broadway, Suite 209, San Antonio, TX

---

*This Privacy Policy is intended to be clear and accurate about how Backstage handles your data. It's not legal advice. If you have specific questions about your situation, please consult an attorney.*
