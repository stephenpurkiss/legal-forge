---
name: exhibit-manager
description: Manage exhibits in court filings. Handle numbering, cover pages, cross-references, renumbering, and validation.
---

# Exhibit Management

## Numbering Rules
- Maker's initials + sequential number: SP1, SP2, SP3...
- Continuous across entire witness statement
- Supplementary statements continue from last number
- No gaps (renumber if removing)

## Cover Pages (PD 32.11)
Every exhibit needs: exhibit mark, description, witness name, date, case name.

## Cross-References
- [SP1] format, consistent throughout
- Reference BEFORE exhibit appears in bundle
- Exhibits should not cross-reference by SP number (use description)

## Validation
- [ ] Every bundle exhibit referenced in text
- [ ] Every text reference has corresponding exhibit
- [ ] No duplicate numbers, no gaps
- [ ] Every exhibit has cover page
- [ ] Correspondence in chronological order
- [ ] No single-page truncated exhibits

## Operations
- Insert: assign number, renumber subsequent, update all refs, create cover page
- Remove: remove from bundle, update/remove refs, renumber subsequent
- Merge: combine under single number, update cover page, renumber
