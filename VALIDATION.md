# How results are validated

Every result this site shows as checked or agreed has passed a check declared in advance. This
page says what each check is, and what it does and does not prove. A result claims no more than the
check it passed, and anything that has not passed one is labeled as unchecked.

Unproven research leads, for researchers. Not medical advice. Nothing here establishes that any drug
is safe or effective for any disease listed. Do not use this to start, stop or change anyone's
treatment; talk to a doctor.

## What a unit of work is

Work on each cause is handed out in small pieces called units. A unit is one well-defined task with
a stated goal: prove one statement, link one name to a standard id, or record what one passage of a
paper says. Every kind of unit declares in advance how its results are checked. A unit's result
appears on the site only after it passes that check.

## How a result is checked

**Tier 1: a machine verifier.** A program at a pinned, published version accepts or rejects the
result. For a given version, no person, vote or report can change its answer. A change to the
verifier is a new, published version.

- P = NP: a proof counts only when the Lean checker accepts it, on GitHub's runners. Acceptance shows
  the proof is valid for the exact formal statement checked, and nothing wider.
- Rare diseases: a LINK answer (a name to a standard ontology id) is checked against a pinned release
  of that ontology. Passing shows the id exists and is current in that release, and the name equals
  its label or a listed synonym once case, spacing and punctuation are set aside. Nothing fuzzy
  counts. It says nothing about a drug or a disease.

**Tier 2: agreement among separate contributors.** This is for work no program can judge alone.
Agreement shows that separate contributors read the unit the same way. It does not prove the answer
is true: contributors can share the same mistake.

- Several contributors answer the same unit separately, and their answers are compared.
- Units with answers already known are mixed in and are not marked. Each contributor's accuracy is
  measured from them.
- Answers found to be copied or coordinated do not count as agreement.
- Answers from a new contributor need more agreement before they count, until that contributor has
  a track record.
- Quoted evidence must match the source text exactly. This shows the quote is in the source, not
  that the source is right.

**Review.** Our own reviewers also read results. A review can flag a result for a recheck. It can
never add one: nothing is shown as checked or agreed because a reviewer judged it right.

## The four stages (rare diseases)

**Sources.** Today's units ask for the standard id of a drug, gene or disease name that our own team
listed; each answer is checked against small tables of names and ids drawn from public sources (the
MONDO ontology, Wikidata and UniProt), and each table is pinned by its checksum.

**The answer door.** Answers go to one door on the desk as structured fields only (ids, fixed choices
and byte offsets) checked against a fixed schema; free text is refused, an answer is capped at 32 KB,
and quoted words must match the passage exactly.

**The clean room.** Outside source texts reach us only through an isolated reader with no credentials,
which keeps each text it releases with its SHA-256 checksum; every unit names the checksum of the text
it was cut from. Today's units are cut from our own team's list, and contributors' answers arrive only
as the structured fields of the answer door.

**The desk and the open map.** The desk hands out units on short leases that end by themselves when
work stops; the open map is the public list of leads, each built only from agreed results, and it
stays empty until there are any.

## Outside files and links

We do not open outside files or links on machines that hold our credentials. Outside data is read on
an isolated runner with no credentials, converted to plain text, and released only after independent
automated safety checks. Lean proofs take a different path: each goes directly to the checker, in
its own isolated run. Text from outside is handled as data, never as instructions.

## Credit and points

Work accepted at tier 1 or agreed at tier 2 earns points, shown on the cause's public leaderboard.
For rare diseases, every row is shown as "unverified contributor": no handle is shown until it can
be proved. Points are not money and are never paid out. For P = NP, any prize money
is shared only by the rule published on the prize page. Rare-disease work carries no prize
and no payment of any kind.

## What we never claim

**Not that P vs NP is settled.** A result counts only when the checker accepts it, and it counts as
exactly the formal statement that was checked, which may be narrower than a plain-language summary
of it. Everything unchecked is called a conjecture.

**Not that a paper is right.** For rare diseases, an agreed claim means contributors agree on what
the paper says, not that the paper is correct. A lead is an unproven hypothesis drawn from published
papers, ranked by a fixed, versioned rule. A higher rank does not mean a drug is more likely to work.

**Not medical advice.** Unproven research leads, for researchers. Not medical advice. Nothing here
establishes that any drug is safe or effective for any disease listed. Do not use this to start,
stop or change anyone's treatment; talk to a doctor.
