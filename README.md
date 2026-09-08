# Human-K2P-QTY-Analogs

This repository contains sequences and AlphaFold3 structures from the study applying the QTY code to four human two-pore-domain potassium channels.

The QTY code replaces selected hydrophobic residues: leucine (L) with glutamine (Q), isoleucine (I) and valine (V) with threonine (T), and phenylalanine (F) with tyrosine (Y).

| Protein | UniProt accession |
| ------- | ----------------- |
| TASK-1 | O14649 |
| TASK-3 | Q9NPC2 |
| TREK-2 | P57789 |
| TRAAK | Q9NYG8 |

The repository contains:

- **QTY_sequences_full:** four full-length QTY sequences submitted to AlphaFold3.
- **QTY_sequences_trimmed:** four sequences extracted from the trimmed QTY structures used in the paper.
- **QTY_AF3_structures:** four trimmed QTY PDBs used in the paper and four full-length QTY PDBs from runs with templates off.
- **native_sequences_full:** four exact native-control sequences used for the AlphaFold3 controls.
- **native_AF3_structures:** four native-control PDBs with templates enabled and four with templates off.

All QTY predictions started from full-length sequences. Trimming was performed on the coordinates after prediction. The trimmed FASTA headers list retained residue ranges; omitted ranges are not included in the sequence. Each trimmed FASTA matches its corresponding trimmed PDB.

Native-control and template-off PDBs contain full-length model 0 predictions. The same native-control sequences were used with templates enabled and off. Template-off QTY sequences match the files in `QTY_sequences_full`.

The experimental reference structures are available from the RCSB Protein Data Bank: [9G9X](https://www.rcsb.org/structure/9G9X), [8K1J](https://www.rcsb.org/structure/8K1J), [8QZ3](https://www.rcsb.org/structure/8QZ3), and [7LJ5](https://www.rcsb.org/structure/7LJ5), respectively.
