# Cell-Cell-Communication

## Proposed BMP10–ACVRL1 Signaling Between Atrial Cardiomyocytes and Endothelial Cells

## Biological Question
Can BMP10 produced by atrial cardiomyocytes signal through ACVRL1 on endothelial cells and regulate cellular signaling in the receiving endothelial cell?

**Chosen sender cell and biological context**
| **Item** | **Answer** |
|---|---|
| **Sender cell** | Atrial cardiomyocyte |
| **Biological context** | Cardiac cell-to-cell communication and signaling |
| **Main purpose** | To investigate how a signal from atrial cardiomyocytes may influence signaling in endothelial cells |

**Candidate ligand and evidence for sender-cell expression**
| Item | Information |
|---|---|
| **Sender cell** | Atrial cardiomyocyte |
| **Candidate gene** | **BMP10** |
| **Protein name** | Bone morphogenetic protein 10 |
| **Signal type** | Secreted signaling protein / growth factor |
| **Expression evidence** | Human Protein Atlas information supports BMP10 expression in cardiac tissue/cells, including its association with atrial cardiomyocytes |
| **Source** | Human Protein Atlas |
BMP10 was selected because it is a signaling protein that can function as an extracellular ligand. It is therefore suitable for investigating a possible paracrine communication pathway from an atrial cardiomyocyte to another cell type.

**Receptor and receiver cell with supporting evidence**
| **Item** | **Information** |
|---|---|
| **Ligand** | BMP10 (Bone morphogenetic protein 10), encoded by *BMP10* |
| **Receptor** | ACVRL1 (Activin A receptor like type 1 / ALK1), encoded by *ACVRL1* |
| **Receiver cell** | Endothelial cell |
| **Signaling type** | Proposed paracrine signaling |
| **Signaling context** | BMP/ACVRL1 signaling involving downstream SMAD proteins and regulation of cellular signaling |
| **Supporting source** | OmniPath |
| **Expression/context source** | Human Protein Atlas |
The endothelial cell was selected as the receiver because ACVRL1 is a receptor associated with endothelial signaling, making it a biologically plausible receiving cell for the proposed BMP10 signal.

**OmniPath evidence**
| **Component** | **Gene** | **Role** |
|---|---|---|
| BMP10 | `BMP10` | Ligand/signal |
| ACVRL1 | `ACVRL1` | Receptor on receiver cell |
OmniPath identified ACVRL1 as a receptor associated with BMP10. The selected BMP10–ACVRL1 relationship had evidence supporting a directed and stimulatory interaction, making ACVRL1 a suitable receptor for the proposed signaling model.

**STRING Network Image and Interpretation**
| **Item** | **Information** |
|---|---|
| **Enriched process** | SMAD signaling pathway |
| **Relevant pathway** | Signaling by BMP |
| **Number of proteins** | 11 in the analyzed network |
| **Observed edges** | 47 |
| **PPI enrichment p-value** | 2.05 × 10⁻¹⁴ |
| **Protein 1** | SMAD1 – downstream signaling protein associated with BMP signaling |
| **Protein 2** | SMAD5 – SMAD protein involved in BMP-related signaling |
| **Protein 3** | SMAD9 – SMAD protein associated with BMP signaling |
| **Protein 4** | SMAD4 – common SMAD involved in downstream signal regulation |

The STRING network was generated using ACVRL1 as the receptor-centered protein. The initial network contained 11 proteins and 47 observed edges, with a PPI enrichment p-value of 2.05 × 10⁻¹⁴.
The enriched biological processes included positive regulation of SMAD protein signal transduction, activin receptor signaling, TGF-beta receptor superfamily signaling, and the SMAD signaling pathway. A relevant Reactome pathway was Signaling by BMP.
The network therefore supports the involvement of SMAD-related proteins in the signaling system surrounding ACVRL1. Relevant downstream proteins selected for the final model were SMAD1, SMAD5, SMAD9, and SMAD4.
