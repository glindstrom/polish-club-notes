# Changelog

All notable changes to the Polish Club Notes will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

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
