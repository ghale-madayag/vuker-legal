# Vuker — Privacy Policy

Last updated: **13 August 2026** · Effective: **13 August 2026**

---

## 1. Who is responsible for your data

Vuker is operated by **Vuker Booking Services**, **Yakal Street, Block 35 Lot 25, Lumina Homes Subdivision, Maliwalo, Tarlac City 2300, Philippines**, the
*personal information controller* for the purposes of the **Data Privacy Act of
2012 (RA 10173)**.

Data Protection Officer: **asinobagojr2022@gmail.com**, **Yakal Street, Block 35 Lot 25, Lumina Homes Subdivision, Maliwalo, Tarlac City 2300, Philippines**.

## 2. What we collect, and why

We collect only what a booking or a verification actually needs. Grouped by
what it is for, because that is what determines how long we keep it.

### 2.1 If you only browse

Nothing that identifies you. You can search photographers, view portfolios and
see prices without an account. Your approximate location is used **only on your
device** to sort results by distance, and is not stored on our servers. Signed
out, you cannot see any photographer's exact coordinates — the server returns a
distance already rounded, not a position.

### 2.2 If you create an account

| Data | Why | Basis under RA 10173 |
|---|---|---|
| Name, email | To identify you to the other party in a booking | Contract |
| Password (hashed) or Google sign-in identifier | To let you sign in | Contract |
| Mobile number, if you add one | Booking notifications by SMS | Consent |
| City and approximate location, if you allow it | To match you with nearby photographers | Consent |
| Whether you are a client or a photographer | Determines what you can do | Contract |

We never see your Google password. If you sign in with Google we receive only
your name, email address and profile picture.

### 2.3 If you are a photographer seeking verification

This is the most sensitive data we handle, and it is treated separately.

| Data | Why |
|---|---|
| Full legal name, ID type, ID expiry date, **last four digits only** of the ID number | To check the ID is real and current |
| Photographs of your government ID (front, and back where the ID has one) | So a reviewer can confirm the document and the name |
| A selfie | To confirm the person holding the phone is the person on the ID |
| Three original camera files | To confirm the portfolio is your work. We read the camera make, model and capture date from the file's own metadata |
| Business registration or permit, if you provide one | To upgrade the badge to *Verified business* — optional |

**We never store your full ID number.** Only the last four digits are written
to the database.

Government IDs and biometric comparison are **sensitive personal information**
under RA 10173 §3(l). We process them only with your explicit, separate consent
— the tick box on the verification screen — and you cannot submit without it.

### 2.4 If you pay a deposit

Card details **never reach Vuker**. When you save a card, the number, expiry and
CVC go from your device directly to **PayMongo**, our payment processor, which
returns a token. What we store is:

- the token (a reference that cannot be turned back into a card number);
- the card brand and the **last four digits**, so you can tell your cards apart;
- for e-wallets, the wallet type only.

We hold **no** full card numbers, no CVCs and no expiry dates. This is
deliberate: it keeps your card data out of our systems entirely.

We also keep a record of each payment — amount, currency, method type, status
and PayMongo's reference — because we are required to account for money taken.

### 2.5 Messages and bookings

Messages between you and the other party, and the details of each booking
(event type, date, location, package, price, status). Both parties to a booking
can see it. Nobody else can.

## 3. How long we keep it

| Data | Retention |
|---|---|
| **ID photographs and your selfie** | **Deleted 30 days after the verification decision.** Only the outcome — verified or not, and at what level — is kept |
| Verification outcome and audit trail | While your account exists, and afterwards only for as long as needed to resolve a dispute or meet a legal obligation |
| Account details | While your account exists |
| Bookings, payment records and invoices | **[10]** years after the booking, to meet BIR record-keeping requirements — confirm this figure with your accountant |
| Messages | While your account exists |
| Approximate location | Not stored on our servers |

Deleting your account withdraws your verification consent and removes your
profile. Records we are legally required to retain — chiefly financial ones —
survive deletion, and only for as long as that requirement lasts.

## 4. Who else sees your data

We do not sell your data. We do not use it for advertising. We share it only
with the following, and only for the purpose named.

| Who | What they get | Where they process it |
|---|---|---|
| **Supabase** — database, authentication and file storage | Everything above | **Sydney, Australia** (`ap-southeast-2`) |
| **PayMongo** — payments | Card and wallet details you enter at payment, and the deposit amount | Philippines |
| **Semaphore** — SMS | Your mobile number and the message | Philippines |
| **Google** — if you use Google sign-in | Only what is needed to authenticate you | Global |
| The other party to your booking | Your name, and the booking details | — |

**On sending your data abroad.** Your data is stored on Supabase infrastructure in **Sydney, Australia**, not in the Philippines. RA 10173 holds us responsible for it wherever it is processed, and we remain accountable for it there. We rejected one face-matching
provider specifically because it would have sent Philippine government IDs to
servers in China, which we judged an unreasonable cross-border transfer for
this purpose. If we adopt automated face matching we intend to use a provider
processing within **ap-southeast-1 (Singapore)** or the Philippines, and we
will update this notice **before** doing so.

Automated face matching is **not currently enabled**. Verification is decided
by a human reviewer looking at the two photographs.

## 5. Automated decisions

We do not make solely automated decisions that significantly affect you.
Verification is decided by a person. If face-matching software is enabled later,
it will produce a *score for the reviewer*, not a verdict — and you may ask for
the reasoning and contest the outcome.

## 6. Your rights

Under RA 10173 you may:

- **be informed** — this notice, and any change to it;
- **access** the data we hold about you;
- **object** to processing, and withdraw consent for anything based on it;
- **correct** anything inaccurate;
- **erase or block** data processed unlawfully or no longer needed;
- **damages** for a violation that harms you;
- **data portability** — receive your data in a portable electronic format;
- **complain** to the National Privacy Commission.

To exercise any of these, contact our DPO at **asinobagojr2022@gmail.com**. We will respond
within **[15]** working days.

One limit worth stating plainly: whether you signed up as a client or a
photographer **cannot be changed after your account is created**. It determines
what you are permitted to do throughout the service. If you need the other
role, create a separate account.

You may complain to the **National Privacy Commission**, 5th Floor, Delegation
Building, PICC Complex, Pasay City, or at privacy.gov.ph.

## 7. How we protect it

- Every request is authorised per-row in the database, so one account cannot
  read another's bookings, messages or documents.
- Verification documents live in **private storage**. They are reachable only
  through short-lived links issued to you or to a reviewer.
- Payment card data never enters our systems (§2.4).
- Deposits can only be marked paid by our payment server after the processor
  confirms the money moved — not by any app or device.
- Verification verdicts cannot be written from a device, only by review.

No system is perfectly secure. If a breach puts you at risk we will notify you
and the NPC within **72 hours** of becoming aware, as RA 10173 requires.

## 8. Children

Vuker is not for under-18s and we do not knowingly collect their data. If you
believe a child has given us personal information, contact our DPO and we will
delete it.

## 9. Changes

We will post changes here and update the date above. For anything that
materially changes how we use your data, we will tell you in the app before it
takes effect — and where the law requires consent, we will ask again rather than
assume it.

## 10. Contact

**Vuker Booking Services** · **Yakal Street, Block 35 Lot 25, Lumina Homes Subdivision, Maliwalo, Tarlac City 2300, Philippines**
Data Protection Officer · **asinobagojr2022@gmail.com**
