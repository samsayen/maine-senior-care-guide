# Maine Retirement & Care Guide

A single-page, plain-language reference for older adults in **Oxford County, Maine**
(South Paris / Norway area) and the families helping them.

**Live page:** https://sayen.io/maine-senior-care-guide/

It pulls together the things that are otherwise scattered across a dozen state and federal
websites — and written in type large enough to actually read.

## What's in it

| Section | Covers |
|---|---|
| Start here | The three phone calls that unlock almost everything else |
| 1. Legal papers | Will, financial power of attorney, advance directive, transfer-on-death deed — with Maine's actual signing rules (they differ per document) |
| 2. Help at home | MaineCare Section 19 and 63 waivers, Meals on Wheels, HEAP heating aid, and two benefits with **no asset test at all** |
| 3. Money & MaineCare | 2026 asset limits, the 5-year look-back, spousal protections, estate recovery, and lawful ways to spend down |
| 4. Where to live | Five rungs from staying home to skilled nursing, including the Maine Veterans' Home in South Paris |
| 5. Veteran benefits | What 3 years of peacetime service actually qualifies for — and why "no combat" is irrelevant |
| 6. Property tax & bills | Homestead exemption, the refundable $2,000 Property Tax Fairness Credit, deferral, veteran exemption |
| 7. Your numbers | Four calculators (see below) |
| 8. Phone numbers | Everything on the page, collected and tap-to-call |

## The calculators

- **Countable assets vs. the MaineCare limit** — handles single, both-spouses-applying, and the one-spouse case where the at-home spouse is protected up to $162,660
- **Care cost gap and runway** — monthly shortfall, and how long savings last before hitting the limit
- **Home equity** — and how much of it is exposed to estate recovery
- **Wartime service check** — enter DD-214 years, find out whether VA Pension and the $6,000 state exemption are in play

Nothing is transmitted anywhere. Figures are kept in the browser's `localStorage` on that one
device, and an **Erase all my numbers** button clears them.

## Design notes

Built for readers in their 70s and 80s:

- 20px base type, nothing below 16px
- High-contrast light theme, committed (no dark mode — this gets read in daylight and printed)
- Every phone number is a `tel:` link with a 44px minimum tap target
- Sticky table of contents on wide screens; collapses to a tappable bar on phones
- Prints cleanly — collapsed sections auto-expand, navigation is dropped
- Single file, **zero dependencies, no network calls**. Works offline forever.

## Running it

Open `index.html`. That's the whole thing.

## Sources

Every dollar figure traces to a cited source in [`SOURCES.md`](SOURCES.md), with a note on how
often it changes. Most are **2026 amounts that change annually** — the MaineCare and VA
figures also move on a July 1 cycle.

## Disclaimer

This is a summary of public information about Maine and federal programs, assembled September
2026. **It is not legal, tax, or financial advice.** Eligibility is decided by MaineCare, the
VA, and your municipality based on your actual documents.

One thing genuinely worth the warning: **do not give away money or property, and do not put a
house in a child's name, before talking to a Maine elder law attorney.** MaineCare looks back
five years, and a well-meant transfer can block coverage later when the money is already gone.
Free advice for Mainers 60+: Legal Services for Maine Elders, 1-800-750-5353.
