# Changelog
All notable changes to the Polish Club Notes will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
## [Unreleased]

## [1.3.5] - 2026-03-24
### Changed
- `convention-card.html`: Added defenses vs strong 1♣ (X=♣, 1NT=♣+♦, 2X=Multi-Landy) and vs NT (Multi-Landy direct; reopen: 2♣=♥+♠, 2♦/2♥/♠=NAT)
- Replaced Negative Doubles and Support Double/Redbl with transfers after overcall (vs 1♦/1♥) and transfers after double of 1M
- Fixed 1NT overcall range: 15–17 (was 15–18)
- Changed discard: Odd/Even with Lavinthal on even; Swedish: Italiensk sakning
- Transfer notation unified to arrow style (→) throughout both cards
- 1NT responses: explicit `2♠→♣, 3♣→♦`; 2NT: `3♠=♣&♦`
- Suit symbols consistently coloured throughout Swedish card

## [1.3.4] - 2026-03-23
### Changed
- `convention-card.html`: Merged Swedish translation into the English card with a language toggle (🇬🇧/🇸🇪); selected language is remembered in localStorage
- Removed separate `convention-card-sv.html` page; Swedish content is now accessible via the toggle on the convention card page
- Swedish card uses correct bridge terminology throughout: Schneider, Malmö, Romersk sakning, Vända i partnerns färg, Hög-x/Låg-x, utgångskrav/okrav, Upplysningsdubbling, balanseringsläge
- Fixed Checkback: `2♣=relay→2♦, 2♦=GF` (was `2♣=weak, 2♦=strong (13+)`)
- Fixed leads table: `Hi-x`/`Lo-x` (was `Hi-X`/`Lo-X`) in English card
- Updated 1♥/1♠ responses: `2/1=GF (2♣: 2+♣)`; removed point range from 3♣/3♦ for brevity

## [1.3.3] - 2026-03-23
### Added
- New page `convention-card-sv.html`: Swedish translation of the convention card (Polsk Klöver – Konventionskort)

## [1.3.2] - 2026-03-23
### Changed
- Removed vulnerability-specific HCP ranges throughout, aligning all opening descriptions with the convention card
- `openings/overview.md`: simplified to single-column table; updated 1♥/1♠ to (10)12–17, 1NT to (14)15–17(18), 2♦/2♥/2♠ to (5)6–10
- `openings/one-heart.md`, `one-spade.md`: updated to (10)12–17 HCP
- `openings/one-nt.md`: updated to (14)15–17(18) HCP
- `openings/two-diamond.md`: updated to (5)6–10; removed vulnerability-split min/max hand examples
- `openings/two-major.md`: updated to (5)6–10, 5+m vul; removed vulnerability-split min/max hand examples

## [1.3.1] - 2026-03-23
### Added
- New page `convention-card.html`: Printable A4 portrait convention card (horizontal fold), covering opening bids, 1♣/1NT/2NT/2♣ responses, key conventions (Odwrotka, Drury, Checkback, RKCB 1430, etc.), competitive bidding overview, signals, and opening leads; includes partner name input fields printed on the card

## [1.3.0] - 2026-03-23
### Added
- New page `openings/strong-two-nt.md`: Strong 2NT opening (21-22 HCP balanced) with full response structure — Stayman (four replies including 3NT for both majors), Smolen after 3♦, transfers with opener's support/control-quality rebids, 3♠ minor preference, and 4NT quantitative
- New page `openings/precision-two-club.md`: Precision 2♣ opening (11-14/15 HCP, 6+ clubs or 5+ clubs with a four-card major) with 2♦ relay system, opener's rebid structure (major, 2NT/3♣ club variants, singleton-showing 3♦/3♥/3♠, solid 3NT), continuations after each rebid, 2NT ambiguous response, and bidding after intervention

### Removed
- Removed `openings/two-nt.md`: Weak 2NT (5-5 minors) replaced by the strong 2NT opening
- Removed `openings/two-club.md`: Weak 2♣ (both majors) replaced by the precision 2♣ opening
- Removed `openings/two-club-interference.md`: No longer applicable after replacing the weak 2♣ opening

### Changed
- Updated `openings/one-nt.md`: Fixed typos in responder rebids after 1NT – 2♥ – 2♠ sequence (self-splinter bids were incorrectly listed as 3NT instead of 4♣ and 4♣ instead of 4♥)
- Updated `openings/one-club.md`:
  - 1♣ club variant strength changed from 12-17 to 15-17 HCP
  - 1♣ – 1♦ – 2♣ rebid updated to 15+; 5+ clubs, no 4-card major (unless 20+)
  - 1♣ – 1♦ – 2NT rebid updated from 21-23 to 23-24 HCP; continuations now reference and match the Strong 2NT Opening page
  - 1♣ – 1♥ – 2♣ and 1♣ – 1♠ – 2♣ rebid structures updated per reference material: strength corrected to 15-17, response ranges and forcing status revised, and after-2♦ continuations corrected
- Updated `openings/one-diamond.md`: Description updated to 12-17 5+♦, any 4♦441, or 12-15 4♦ 5♣
- Updated `openings/overview.md`: Descriptions updated for 1♣, 1♦, and 2♣ openings to reflect new system agreements

## [1.2.8] - 2025-12-23
### Changed
- Updated `openings/one-club.md`:
  - Added new subsection "Responder's Continuations after 2♥ / 2♠ Rebids" detailing responses after opener's 21-22 HCP rebid
  - Clarified that invitations are not used after these strength-defining rebids
  - Added guidance for responder without fit (pass with 0-3 HCP, bid suit with 4+ HCP, 2NT with 4-8 or 11+ HCP, 3NT with 9-10 HCP)
  - Added guidance for responder with fit (jump to game with 4-10 HLDF, economical agreement with 11+ HLDF for slam invitation)

## [1.2.7] - 2025-12-23
### Changed
- Updated `carding-agreements.md`:
  - Added new subsection "Returning Partner's Suit (Original Length)" explaining how to show original suit length when returning partner's lead
  - Clarified that even original length → return lowest spot; odd original length → return high spot
  - Added example with West ♠ QJ10 and East holding various combinations
  - Changed "Later Discards" to reference "original count" instead of "present count" for consistency
  - Updated "Discarding from suit partner led" to show original count rather than current count

## [1.2.6] - 2025-12-23
### Changed
- Updated `openings/one-club.md`:
  - Added detailed transfer acceptance structure after 1♣ – 1♦ – 2NT, showing how opener indicates support quality and control richness
  - Clarified when responder should use major-suit transfers after 2NT rebid (only with game-oriented hands)
  - Improved formatting and readability of notes section in notrump rebids

## [1.2.5] - 2025-11-30
### Changed
- Updated `openings/one-nt.md`: Added responder rebid after 1NT – 2♣ – 2♥ sequence: 2♠ showing 4♠, 5(+)♦, non-forcing.

## [1.2.4] - 2025-11-10
### Changed
- Updated `openings/one-club.md`:
- Expanded **Opener’s Rebids after 1♣ – 1NT** table to include the conventional **2♦ gadget**:
  - **2♦** = artificial ask about responder’s shape; GF.
  - Replies:
    - 2♥ = 2‑3‑4‑4
    - 2♠ = 3‑2‑4‑4
    - 2NT = 3‑3‑3‑4 (clubs or diamonds)
    - 3♣ = 5♣‑3‑3‑2
    - 3♦ = 5♦‑3‑3‑2
- Minor formatting improvements for consistency in the 1NT response section.
## [1.2.3] - 2025-10-24
### Added
- Added `overcalls-one-level.md`: New section documenting responses after 1♦ overcall, including non-forcing 1♥/1♠ responses, artificial 2♣, weak 2♦ raise, and natural forcing higher bids. Includes note that continuations after 1♥/1♠ response are identical to after 1♦ opening.
### Fixed
- Fixed `overcalls-one-level.md`: Minor whitespace and formatting cleanup throughout the file.
## [1.2.2] - 2025-10-20
### Summary
Clarified responder rebids after 1♥ – 1♠ – 2♣, including the corrected “Fourth Suit” (2♦) continuations, aligned with Polish original sources and improved internal consistency.
### Changed
- Updated `openings/one-heart.md`:
- Simplified and corrected the note section under **Responder Rebids after 1♥ – 1♠ – 2♣**:
- Removed three unrelated notes not specific to this sequence.
- Added explicit in-table footnote references:
- **(1)** for 2♠: “With 4–8 HCP and six spades, responder would have bid 2♠ in the previous round.”
- **(2)** for 3♠: “3♠ is forcing (including game-try hands), since the invitational role is already taken by 2♠.”
- Rewritten **After 2♦ (Fourth Suit)** table for accuracy and clarity:
- 2♥, 2♠, 2NT, 3♣, 3♦, 3♥, 3♠, and 3NT now match original Polish definitions for opener’s strength and distribution ranges.
- Ensured indentation and note hierarchy match MkDocs formatting.
## [1.2.1] - 2025-10-18
### Summary
Refined hand description for 1♣ – 1♠ continuations to clarify differences between 3♣ and 3♦ rebids.
### Changed
- Updated `openings/one-club.md`:
- Split the previous combined description of **3♣/3♦** after 1♣ – 1♠ into two distinct bids for improved precision:
- **3♣** = 18+, 5+ clubs, 4+ spades
- **3♦** = 18+, 5+ spades, 5+ diamonds
## [1.2.0] - 2025-10-13
### Summary
Expanded defensive and post-intervention bidding principles for greater clarity in competitive auctions.
### Added
- Added new **general principles** under `after-intervention/overview.md`:
- Responder’s double is for takeout whenever the previous bidding has not limited responder’s strength.
- When a double is for takeout, its main goal is to search for a major-suit fit; bidding the opponents’ suit looks for a stopper or prepares for slam.
- When the opponents have bid two suits, we bid the suit we stop.
- Added new **principle** under `competitive-bidding/general-principles.md`:
- In a **competitive auction** (when all four players have bid), a **natural suit bid by the defenders is not forcing**.
### Changed
- Updated structure of `after-intervention/overview.md` to include the new “Doubles & Stoppers” subsection for better readability and organization.
---
## [1.1.0] - 2025-01-07
### Added
- Initial changelog implementation
- Added `weak-jump-overcalls.md`: Documented weak jump overcalls, including their definition (6-card suit at 2-level, 7-card suit at 3-level, 5-10 HCP), responses, and the Ogust convention for 2NT responses.
### Changed
- Documentation structure improvements
- Updated `one-diamond.md`: Corrected 3♣ response to 1♦ - 1NT to show 15-17 HCP, 5+♦, 5+♣, forcing to 3♦ (previously described incorrectly as 15-17 HCP, 6+♣, invitational). Partner should not pass; with a weak hand, partner bids 3♦.
- Updated `one-heart.md`: Modified responder rebids after 1♥ - 1NT - 2♣/♦ to reflect 2♠ showing 10-11 HCP with 5+♣/♦ and 3♣/♦ showing 8-11 HCP with 4+♣/♦ (previously only described for 2♣).
- Updated `overview.md`: Added reference to Weak Jump Overcalls section.
### Fixed
- Minor formatting corrections
## [1.0.0] - 2025-01-01
### Added
- Complete Polish Club bidding system documentation
- MkDocs web documentation with Material theme
- All existing conventions, openings, and competitive bidding strategies
- Automated GitHub Pages deployment