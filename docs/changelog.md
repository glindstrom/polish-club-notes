# Changelog
All notable changes to the Polish Club Notes will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.16] - 2026-06-05
### Fixed
- `openings/one-heart.md`: restore "bad forcing" (13-15 HCP, 4-3-3-3) to 2NT response definition — erroneously dropped in v1.4.15

## [1.4.15] - 2026-06-05
### Changed
- `openings/one-heart.md`: restructure raise continuations after 1♥–2♥ and 1♥–2NT — opener rebids after 2♥ simplified to pass/2NT/3♥/4♥ based on shape (5332 vs. unbalanced) and support points, with responder continuation tables after invitational 2NT and 3♥; 2NT response updated to 11–12 sp pure limit raise (dropping "bad forcing" 4-3-3-3 variant) with new opener rebid table 3♥/3NT/4♥

## [1.4.14] - 2026-06-05
### Changed
- `openings/one-heart.md`: update opener rebid thresholds after 1♥–2♥ — NV invitation zone widens to 17–19 sp (was 18–19), V game threshold raised to ≥19 sp (was ≥18); pass zone is now ≤16 sp for both NV/V

## [1.4.13] - 2026-06-04
### Added
- `openings/two-diamond.md`: add General Principles section with simulation-based guidance for raising to 4M — IMP (≥16 sp: raise directly), BAM (exactly 16 sp: invite; opener accepts with ≥7 HCP or singleton), 3NT special case (17+ HCP, all stoppers, ≤1 card in opener's major)

## [1.4.12] - 2026-06-04
### Added
- `openings/two-major.md`: add Response 3♦ section with NV/V invitation thresholds — NV (5M+4+m): invite with 16–17 SP, opener accepts SP ≥ 9; V (5M+5+m): bid game directly at 16+ SP

## [1.4.11] - 2026-06-04
### Added
- `hand-evaluation.md`: add Support Points section (responder: HCP + distribution in side suits + extra trumps beyond 3; opener: HCP + distribution in side suits + extra trumps beyond 5)
### Changed
- `openings/one-heart.md`: update major suit raise responses to support points — 2♥ (6–10 sp), 3NT (13–15 sp, no shortness); add NV/V opener rebid thresholds after 2♥

## [1.4.10] - 2026-06-02
### Added
- `competitive-bidding/balancing.md`: add balancing agreements and shape-based guidelines after (1H)-Pass-(2H)-Pass-Pass-?

## [1.4.9] - 2026-06-02
### Changed
- `openings/one-heart-one-spade-interference.md`: after 1♥/1♠ - (X), changed the transfer raise below 2M to show major fit with either 0-6 or game force; standard 2M raise is now 7-10 HLDF

## [1.4.8] - 2026-05-02
### Changed
- `openings/one-diamond.md`: expand 1♦–2NT continuations — fix 3♣ (non-forcing, not forcing to 3♦); add 3NT (balanced, 15-17), 3♥/3♠ (singleton with 5+♣ ask), 4♣ (5-5 minors), 4♦ (6+♦, club shortness); add responder continuations after 3♣

## [1.4.7] - 2026-05-01
### Changed
- `openings/one-club.md`: correct 3♣ rebid after 1♣–1♥ — it is artificial (18+; 5+ diamonds, 4+ clubs; denies 3-card heart fit), not natural 6+ clubs; split 3♣/3♦ row; add continuations after 1♣–1♥–3♣ (3♦ agrees diamonds, 3♥ = 6+ hearts, 3♠ = fourth suit)

## [1.4.6] - 2026-04-13
### Changed
- `competitive-bidding/take-out-doubles.md`: after (1♦)–X–P–1♠, fix misplaced distribution note — moved from 2♦ to 2♠ row where it belongs; 2♦ now correctly reads "Artificial, forcing, strongest action"

## [1.4.5] - 2026-04-08
### Changed
- `openings/one-diamond.md`: splinter responses (3♥, 3♠, 4♣) corrected to 13-15 HCP (was 13-16)
- `openings/one-heart.md`: splinter responses (3♠, 4♣) corrected to 12-14 HCP (was 12-16); HLDF limits unchanged
- `openings/one-spade.md`: splinter response (4♥) corrected to 12-14 HCP (was 12-16); HLDF limits unchanged

## [1.4.4] - 2026-03-28
### Changed
- Convention card: split opening column into four columns — Bid / Cards (Ant. kort) / Description (Beskrivning) / Responses (Svar)
- Renamed "Key Responses" / "Huvudsvar" header to "Responses" / "Svar"
- Cards column values: 1♣=0, 1♦=4+, 1♥/1♠=5+, 1NT=blank, 2♣=5+, 2♦=0, 2♥/2♠=5+, 2NT=blank, 3x/4x=6+/7+, 3NT=blank

## [1.3.8] - 2026-03-24
### Changed
- Convention card: multi-line response rows with `•` (item separator) and `|` (group separator) for better visual scanning
- 1♣ row: replaced green background with left accent bar (3pt solid green border)
- 3NT opening description: switched to `|` separator style

## [1.3.6] - 2026-03-24
### Added
- Bilingual convention card (`convention-card.html`) with 🇬🇧/🇸🇪 language toggle; preference saved in localStorage
- Defense methods: vs strong 1♣ (X=♣, 1NT=♣+♦, 2X=Multi-Landy) and vs NT (Multi-Landy direct/weak; reopen: 2♣=♥+♠, 2♦/2♥/♠=NAT)
- Transfers after overcall (vs 1♦: X→♥, 1♥→♠, 1♠→NT; vs 1♥: X→♠, 1♠→NT) and transfers after double of 1M

### Changed
- Swedish card uses correct bridge terminology: Schneider, Malmö, Italiensk sakning (Odd/Even + Lavinthal), Vända i partnerns färg, Hög-x/Låg-x, utgångskrav/okrav, Upplysningsdubbling, balanseringsläge
- 1♣: added "(or 4♦441)" to 12–14 balanced description
- 1♦: split into two strength ranges (5+♦/4♦441: (10)12–17 and 4♦5♣: (10)12–15)
- 1NT overcall range corrected to 15–17 (was 15–18)
- Transfer notation unified to arrow style (→); minor transfers: 2♠→♣, 3♣→♦
- Replaced Negative Doubles and Support Double/Redbl with transfer-based defenses
- Checkback: `2♣=relay→2♦, 2♦=GF`; 1♥/1♠: `2/1=GF (2♣: 2+♣)`

## [1.3.2] - 2026-03-23
### Changed
- Removed vulnerability-specific HCP ranges throughout, aligning all opening descriptions with the convention card
- Updated 1♥/1♠ to (10)12–17, 1NT to (14)15–17(18), 2♦/2♥/2♠ to (5)6–10 across overview and individual opening pages

## [1.3.1] - 2026-03-23
### Added
- New page `convention-card.html`: Printable A4 portrait convention card (horizontal fold) covering openings, responses, conventions, competitive bidding, signals, and leads

## [1.3.0] - 2026-03-23
### Added
- New page `openings/strong-two-nt.md`: Strong 2NT opening (21–22 HCP) with full Stayman, Smolen, and transfer structure
- New page `openings/precision-two-club.md`: Precision 2♣ (11–14/15 HCP) with 2♦ relay system and opener's rebid structure

### Removed
- `openings/two-nt.md`, `openings/two-club.md`, `openings/two-club-interference.md`: replaced by the new strong variants

### Changed
- `openings/one-nt.md`: fixed typos in responder rebids after 1NT – 2♥ – 2♠
- `openings/one-club.md`: updated 1♣ club variant strengths and rebid structures; 2NT rebid updated to 23–24 HCP
- `openings/one-diamond.md`: updated to 12–17 5+♦, 4♦441, or 12–15 4♦5♣
- `openings/overview.md`: updated descriptions for 1♣, 1♦, and 2♣

## [1.2.8] - 2025-12-23
### Changed
- `openings/one-club.md`: added responder's continuations after 1♣ – 1♥/1♠ – 2♥/2♠ rebids (guidance for hands with and without fit)

## [1.2.7] - 2025-12-23
### Changed
- `carding-agreements.md`: added "Returning Partner's Suit" subsection; clarified original vs present count for later discards

## [1.2.6] - 2025-12-23
### Changed
- `openings/one-club.md`: added transfer acceptance structure after 1♣ – 1♦ – 2NT; clarified when major-suit transfers apply

## [1.2.5] - 2025-11-30
### Changed
- `openings/one-nt.md`: added responder rebid after 1NT – 2♣ – 2♥: 2♠ showing 4♠ 5+♦, non-forcing

## [1.2.4] - 2025-11-10
### Changed
- `openings/one-club.md`: added 2♦ gadget after 1♣ – 1NT (artificial shape ask, GF) with full reply structure

## [1.2.3] - 2025-10-24
### Added
- `overcalls-one-level.md`: responses after 1♦ overcall (non-forcing 1♥/1♠, artificial 2♣, weak raise, natural forcing bids)

## [1.2.2] - 2025-10-20
### Changed
- `openings/one-heart.md`: corrected and simplified responder rebids after 1♥ – 1♠ – 2♣; rewrote After 2♦ (Fourth Suit) table for accuracy

## [1.2.1] - 2025-10-18
### Changed
- `openings/one-club.md`: split 3♣/3♦ after 1♣ – 1♠ into distinct bids (3♣ = 18+, 5+♣ 4+♠; 3♦ = 18+, 5+♠ 5+♦)

## [1.2.0] - 2025-10-13
### Added
- `after-intervention/overview.md`: general principles for doubles and stoppers in competitive auctions
- `competitive-bidding/general-principles.md`: natural suit bid by defenders is not forcing in a competitive auction

## [1.1.0] - 2025-01-07
### Added
- Initial changelog; `weak-jump-overcalls.md`: weak jump overcalls with Ogust convention

### Changed
- `one-diamond.md`: corrected 3♣ response to 1♦ – 1NT (15–17, 5+♦ 5+♣, forcing)
- `one-heart.md`: updated responder rebids after 1♥ – 1NT – 2♣/♦

## [1.0.0] - 2025-01-01
### Added
- Complete Polish Club bidding system documentation
- MkDocs site with Material theme and automated GitHub Pages deployment
