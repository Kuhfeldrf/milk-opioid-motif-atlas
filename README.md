# Milk Opioid Motif Atlas

**[kuhfeldrf.github.io/milk-opioid-motif-atlas](https://kuhfeldrf.github.io/milk-opioid-motif-atlas/)**

Where human and bovine milk proteins can release opioid peptides, and which of those
sites are actually produced by digestion.

Every tyrosine in the mature chain of five milk proteins is scored for the opioid
pharmacophore that met-enkephalin (`YGGFM`) and β-casomorphin-7 (`YPFPGPI`) share, then
checked against **14,572 peptides measured in human and bovine milk digesta** — the
Abbott set plus preterm gastric, preterm intestinal and term intestinal sheets.

| | |
|---|---|
| Tyr sites in mature human and cow chains | **86** |
| Carrying an opioid-like motif | **39** |
| Released as a peptide N-terminus | **11** |
| Released but undocumented | **5** |

Proteins covered: β-casein, κ-casein, β-lactoglobulin, α-lactalbumin and lactoferrin,
human and bovine (humans do not express β-lactoglobulin).

## The one rule that makes this a screen rather than a list

**A peptide supports a site only when its N-terminus sits at that tyrosine.** Peptides
that merely span the tyrosine do not count, because a blocked N-terminus abolishes
opioid binding. That single constraint is what cuts 39 motif-bearing sites down to the
11 that digestion actually produces, and it is why five candidate sites here are
released but carry no documented opioid.

## Motif model

A candidate is a tyrosine in the mature chain that could start a 4–8 residue peptide and
has a second aromatic residue (F, Y or W) nearby:

- **Aromatic at position 3–4** — the strong case, matching F4 of met-enkephalin and F3 of
  β-casomorphin-7.
- **Aromatic at position 5–6** — the weaker case, which is what recovers YPVEPF and both
  lactoferroxins.

**Enk score** compares the first five residues to `YGGFM`, scoring 2 per identity and 1
per conservative match, out of 10.

## Coverage and limits

Goat and sheep sequences were scanned but have no peptide data in this set, so they are
excluded from the figures. Sheep lactoferrin is an unreviewed UniProt entry. This is a
sequence-level screen: it says where an opioid-like peptide *can* be released, not that
any of them is active at a receptor. Nothing here supports a dietary or clinical claim.

Protein sequences from [UniProt](https://www.uniprot.org/).
