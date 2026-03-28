# Privacy Policy — Earn It!

**Last updated:** 2026-03-28

## 1. Who We Are

Earn It! is a mobile application that helps families track children's chores and savings goals. The app is operated by:

**Markus Mikola**
Operating as Earn It!
Turku, Finland
Contact: earnit.family@gmail.com

For the purposes of the EU General Data Protection Regulation (GDPR), Markus Mikola is the data controller.

## 2. What Data We Collect

We collect only the data necessary to provide the service. We collect no data for advertising, analytics, or any purpose beyond app functionality.

### Account data
- Email address (one per family, used for sign-in)
- Password (hashed by Supabase Auth — we never see or store plaintext passwords)

### Profile data
- Profile name (parent or child name, as entered by the parent)
- Avatar emoji selection
- Profile role (parent or child)
- Optional PIN (stored as a SHA-256 hash — we never see or store the actual PIN)

### App data
- Family name
- Chore definitions (name and emoji, created by parents)
- Chore log entries (which child completed which chore on which date)
- Book log entries (book title, date, which child logged it)
- Savings goals (title, target amount, start date, completion date)
- Earning settings (family-specific parameters for the earning formula)

### Data we do NOT collect
- Location data
- Device identifiers or advertising IDs
- Usage analytics or behavioral tracking
- Photos or media files
- Contacts or calendar data
- Health or biometric data
- Data from other apps on your device

## 3. How We Use Your Data

We use your data solely to provide the Earn It! service:

- **Account data** — to authenticate you and secure your family's account
- **Profile data** — to identify family members within the app
- **App data** — to calculate earnings, display progress toward savings goals, and show history

We do not use your data for marketing, profiling, automated decision-making, or any purpose beyond delivering the app's core functionality.

## 4. Children's Data

Earn It! is designed for use by families with children. We take children's data protection seriously.

### How children's data is handled
- **Parents create all accounts.** A parent creates the family account and adds child profiles. Children do not create their own accounts or provide their own email addresses.
- **Children's data is minimal.** We store only the child's first name (or nickname), an emoji avatar, chore/book log entries, and savings goal progress. No email, no date of birth, no photos.
- **Parental consent is built into the design.** Because a parent must create the account, add child profiles, and configure the app before any child can use it, parental consent is inherent in the setup process.
- **Children cannot share data externally.** The app has no social features, no messaging, no public profiles, and no way for a child to share data outside the family.

### Applicable law
Under Finnish implementation of GDPR Article 8, the age at which a child can independently consent to data processing by information society services is 13 years. For children under 13, parental consent is required — which our app design ensures by requiring parent-initiated account creation.

## 5. Where Your Data Is Stored

Your data is stored on **Supabase**, a cloud database platform. Our Supabase project is hosted in **Ireland (EU)**, ensuring your data remains within the European Economic Area and is subject to EU data protection law.

Supabase uses encryption in transit (TLS) and at rest. For more information, see [Supabase's security documentation](https://supabase.com/security).

We do not transfer your data outside the EU/EEA. We do not share your data with any third parties.

## 6. Data Sharing

**We do not share your data with anyone.** Specifically:

- No data is sold to third parties
- No data is shared with advertisers
- No data is sent to analytics services
- No data is shared with other families using the app
- No data is accessible to anyone outside your family

The only external service that processes your data is Supabase (our database provider, EU-hosted), which acts as a data processor under GDPR.

## 7. Data Retention

Your data is retained for as long as you have an active Earn It! account. When you delete your account (see Section 8), all associated data is permanently deleted.

Completed savings goals and historical chore/book entries are retained within your account as part of the service — they form your family's history. You can request deletion at any time.

## 8. Your Rights Under GDPR

As a user in the EU, you have the following rights:

- **Right of access** — You can request a copy of all data we hold about your family. Contact us at earnit.family@gmail.com.
- **Right to rectification** — Parents can edit profile names, avatars, and correct historical entries directly in the app.
- **Right to erasure ("right to be forgotten")** — You can delete your entire family account and all associated data from within the app (Settings → Delete account). Deletion is immediate and permanent.
- **Right to data portability** — You can request your data in a machine-readable format. Contact us at earnit.family@gmail.com.
- **Right to object** — Since we only process data to provide the service (not for marketing or profiling), this right applies if you wish to stop using the service — simply delete your account.
- **Right to lodge a complaint** — You can file a complaint with the Finnish Data Protection Ombudsman (Tietosuojavaltuutettu): [tietosuoja.fi](https://tietosuoja.fi/en/home), or with the data protection authority in your country of residence.

## 9. Data Security

We implement the following security measures:

- All data transmitted between the app and our servers is encrypted with TLS
- Passwords are hashed using industry-standard algorithms (by Supabase Auth)
- PINs are hashed with SHA-256 before storage
- Row-level security (RLS) policies ensure families can only access their own data
- No data is stored on your device beyond your authentication session and language preference
- We conduct security audits of our database access policies

## 10. Subscription and Payments

If you subscribe to Earn It!, payment processing is handled entirely by Apple (App Store) or Google (Google Play). We do not receive, process, or store any payment information — no credit card numbers, no billing addresses, no payment tokens. Apple/Google handle all payment data under their own privacy policies.

The only subscription-related data we store is your family's subscription status (active, trial, or expired) to determine which features are available.

## 11. Changes to This Policy

We may update this privacy policy to reflect changes in the app or applicable law. When we make significant changes, we will update the "Last updated" date at the top of this page.

We encourage you to review this policy periodically.

## 12. Contact

For any privacy-related questions or to exercise your rights:

**Email:** earnit.family@gmail.com

You may also contact the Finnish Data Protection Ombudsman:
**Tietosuojavaltuutetun toimisto**
Lintulahdenkuja 4, 00530 Helsinki
[tietosuoja.fi](https://tietosuoja.fi/en/home)
