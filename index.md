# Pythia Privacy Policy

_Last updated: 2026-05-20_

Pythia is an iOS app that lets you ask written questions to a small group of named human advisors and receive written replies. We designed Pythia around the belief that asking for advice is a private act. This policy explains, in plain language, what we store about you, what your advisor can see, and what your choices are.

If you ever want to read the full design intent behind these rules, the short version is: collect as little as possible, never sell anything, and let you walk away cleanly.

---

## 1. The three privacy tiers

When you sign up, you choose one of three tiers. The tier determines what we store about you.

### Private
- **What we store:** a username you choose, a one-way hashed recovery code (so you can sign back in), and your About-you answers (age range, country, gender).
- **What we do not store:** no email, no phone number, no Apple ID, no real name, no device identifier tied to you.
- **Account recovery:** only through the recovery code we show you once at signup. If you lose it, the account is unrecoverable by design.

### Standard · Apple
- **What we store:** the same as Private, plus the Apple user identifier returned by _Sign in with Apple_. If you choose Apple's "Hide My Email" relay, that relay address is what we receive.
- **Account recovery:** by signing in with Apple again on any device.

### Standard · Email
- **What we store:** the same as Private, plus your email address (used only for sign-in and account recovery).
- **Account recovery:** by signing in with the same email.

In all tiers we also store the questions you submit, the replies your advisor sends, and which advisor was paid for which question.

---

## 2. What your advisor sees about you

When an advisor opens your question, they see only:

- Your username
- Your age range, country, and gender (from About-you)
- The question text you wrote
- The time you sent it and the deadline by which they should reply

Advisors never see your email address, Apple identifier, payment information, real name, device, location, or any other question you have sent to any advisor.

---

## 3. Crisis detection

Before your question is sent, Pythia runs a simple keyword check **on your device** to detect language suggesting acute risk. If it triggers, Pythia shows you a calm screen with crisis resources for your country (for example, 988 in the US, Samaritans in the UK, Find A Helpline elsewhere).

The on-device check produces only a true/false result for that one question. The result is used at the moment of sending and is **never transmitted to our servers or stored**.

---

## 4. Payments

Questions to advisors are paid via Apple's In-App Purchase. **Apple — not Pythia — handles your payment information.** We never see your card number, billing address, or payment method.

We do receive from Apple a confirmation that the purchase happened, an opaque transaction identifier, and the product you bought, so we can show you the right thread and pay the right advisor. Refund and revocation notices from Apple are also processed automatically.

---

## 5. Notifications

If you grant permission, we send you a push notification when your advisor has replied. You can choose, in Settings, what the notification preview shows:

- **Full preview** — the first line of the reply
- **Advisor name only** _(default)_ — e.g. "Miletus has replied"
- **Generic** — e.g. "A new reply is waiting"

Push delivery is performed by Apple Push Notification service. We send Apple only the device token and the preview text you have chosen.

---

## 6. Account deletion

You can delete your account at any time from Profile → Account.

- **Private accounts** are deleted immediately. Your username, About-you, questions, replies, and recovery code hash are erased.
- **Standard accounts** are marked deleted immediately and fully anonymized after 30 days. During the 30-day window you can sign back in to cancel deletion.
- In both cases, any unanswered question you have already paid for is refunded through Apple, and your advisor's view of your old conversations changes to **[deleted user]** and becomes read-only.
- The username you used is retired permanently and cannot be claimed by anyone else.

---

## 7. What we do not do

- We do **not** sell, rent, or trade your data with anyone.
- We do **not** use third-party analytics, advertising, or tracking SDKs.
- We do **not** profile you or your questions for marketing.
- We do **not** show ads anywhere in Pythia.
- We do **not** access your contacts, photos, location, microphone, or camera.

---

## 8. Where your data is stored

Pythia uses Supabase (PostgreSQL + Storage hosted in the European Union) as its backend. Apple Push Notification service operates globally. We do not transfer your data to any other processor.

---

## 9. Your rights

Regardless of tier, you can at any time:

- See and edit your About-you answers (Profile → Edit About-you)
- See your full question and reply history (Sent tab)
- Delete your account (Profile → Account)

If you have a question about your data that the app does not let you answer yourself, contact us at the address below.

---

## 10. Children

Pythia is rated 17+ and is not directed to children under 17. We do not knowingly collect data from anyone under 17.

---

## 11. Changes to this policy

If we change how we handle your data, we will update this page and update the "Last updated" date at the top. Material changes will also be communicated inside the app before they take effect.

---

## 12. Contact

For privacy questions, email **privacy@pythia.app**.

Pythia is operated by Bahadir Can Gokcel as sole developer.
