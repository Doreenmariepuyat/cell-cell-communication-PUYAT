# Cell-Cell-Communication

## Proposed BMP10–ACVRL1 Signaling Between Atrial Cardiomyocytes and Endothelial Cells

## Biological Question
Can BMP10 produced by atrial cardiomyocytes signal through ACVRL1 on endothelial cells and regulate cellular signaling in the receiving endothelial cell?

## Chosen sender cell and biological context
| **Item** | **Answer** |
|---|---|
| **Sender cell** | Atrial cardiomyocyte |
| **Biological context** | Cardiac cell-to-cell communication and signaling |
| **Main purpose** | To investigate how a signal from atrial cardiomyocytes may influence signaling in endothelial cells |

## Candidate ligand and evidence for sender-cell expression
| Item | Information |
|---|---|
| **Sender cell** | Atrial cardiomyocyte |
| **Candidate gene** | BMP10 |
| **Protein name** | Bone morphogenetic protein 10 |
| **Signal type** | Secreted signaling protein / growth factor |
| **Expression evidence** | Human Protein Atlas information supports BMP10 expression in cardiac tissue/cells, including its association with atrial cardiomyocytes |
| **Source** | Human Protein Atlas |

BMP10 was selected because it is a signaling protein that can function as an extracellular ligand. It is therefore suitable for investigating a possible paracrine communication pathway from an atrial cardiomyocyte to another cell type.

## Receptor and receiver cell with supporting evidence
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

## OmniPath Evidence
| **Component** | **Gene** | **Role** |
|---|---|---|
| BMP10 | `BMP10` | Ligand/signal |
| ACVRL1 | `ACVRL1` | Receptor on receiver cell |

OmniPath identified ACVRL1 as a receptor associated with BMP10. The selected BMP10–ACVRL1 relationship had evidence supporting a directed and stimulatory interaction, making ACVRL1 a suitable receptor for the proposed signaling model.

## STRING Network Image and Interpretation
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
<img width="660" height="640" alt="image" src="https://github.com/user-attachments/assets/30c5f303-192e-4e64-8825-a3df4e72d60d" />

The STRING network was generated using ACVRL1 as the receptor-centered protein. The initial network contained 11 proteins and 47 observed edges, with a PPI enrichment p-value of 2.05 × 10⁻¹⁴.
The enriched biological processes included positive regulation of SMAD protein signal transduction, activin receptor signaling, TGF-beta receptor superfamily signaling, and the SMAD signaling pathway. A relevant Reactome pathway was Signaling by BMP.
The network therefore supports the involvement of SMAD-related proteins in the signaling system surrounding ACVRL1. Relevant downstream proteins selected for the final model were SMAD1, SMAD5, SMAD9, and SMAD4.

## IntAct Validation
| **Item** | **Information** |
|---|---|
| **Protein pair examined** | LRG1 – ACVRL1-associated receptor complex |
| **IntAct record** | **EBI-16065512** |
| **Interaction type** | Association |
| **Experimental detection method** | Anti-bait co-immunoprecipitation (anti-bait coIP) |
| **Organism** | *Homo sapiens* |
| **Host/context** | In vitro |
| **Positive interaction** | Yes |
| **Publication** | Wang et al. (2013), “LRG1 promotes angiogenesis by modulating endothelial TGF-β signalling” |
| **Journal** | *Nature* |
| **Publication reference** | PubMed: 23868260; DOI: 10.1038/nature12345 |
| **Evidence conclusion** | Supports an association involving an ACVRL1-containing receptor complex |

## Final model and 150–250 word interpretation
<img width="508" height="478" alt="image" src="https://github.com/user-attachments/assets/cb324f9d-4188-4c4f-ac10-7fa78595cb59" />


This model proposes that atrial cardiomyocytes may communicate with endothelial cells through BMP10–ACVRL1 signaling. BMP10 is the proposed extracellular signaling molecule produced or secreted by the atrial cardiomyocyte. OmniPath supports a relationship between BMP10 and the receptor ACVRL1, while endothelial cells provide a biologically plausible receiving-cell context for ACVRL1 signaling. 

After receptor activation, the proposed pathway involves downstream SMAD signaling proteins, including SMAD1, SMAD5, SMAD9, and SMAD4. The STRING analysis showed strong protein-network enrichment and identified the SMAD signaling pathway and BMP-related signaling as relevant processes. IntAct also provided experimental evidence for an association involving an ACVRL1-containing receptor complex, although this evidence involved LRG1 and should not be interpreted as direct proof of BMP10–ACVRL1 binding. 

Therefore, the overall model combines database-supported observations with biological inference. The evidence supports ACVRL1 and SMAD proteins as components of the proposed signaling system, but it does not prove that the complete BMP10 pathway occurs specifically between atrial cardiomyocytes and endothelial cells under all conditions. Further experiments would be needed to confirm the complete cell-to-cell signaling pathway.

# Questions and Answers

### 1. What sender cell did you choose, and in what tissue or biological context does it act?

I chose **atrial cardiomyocytes** as the sender cells. They are specialized heart muscle cells located in the atria and can participate in signaling with other cells in the cardiovascular system.

### 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule identified is **BMP10 (Bone morphogenetic protein 10)**. The Human Protein Atlas provides expression information supporting BMP10 in cardiac/atrial cell contexts. BMP10 was selected because it is a signaling protein suitable for extracellular cell-to-cell communication.

### 3. What receptor receives the signal, and which receiver cell did you select?

The proposed receptor is **ACVRL1 (ALK1)**, and the selected receiver is an **endothelial cell**. ACVRL1 is associated with endothelial signaling and is supported as a receptor for BMP10 by the OmniPath analysis.

### 4. What type of cell-to-cell signaling is represented?

The proposed signaling is **paracrine signaling** because the signal is proposed to be released from one cell and act on a different receiving cell.

### 5. Which proteins in your STRING network appear most relevant to the receptor-associated response?

The most relevant proteins selected for the model are **SMAD1, SMAD5, SMAD9, and SMAD4**. These proteins are associated with SMAD signaling in the ACVRL1-centered STRING network and are relevant to downstream BMP-related signaling.

### 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The relevant enriched processes include the **SMAD signaling pathway**, **positive regulation of SMAD protein signal transduction**, and **TGF-beta receptor superfamily signaling**. The Reactome results also included **Signaling by BMP**.

### 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct showed a positive **association** involving an ACVRL1-containing receptor complex and LRG1. The evidence was obtained using **anti-bait co-immunoprecipitation** in vitro. Because the interaction is classified as an association, it should not be described as proof of direct binding between LRG1 and ACVRL1.

### 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The BMP10–ACVRL1 relationship is supported by OmniPath, while the involvement of SMAD-related proteins is supported by the STRING network and pathway enrichment. The IntAct record provides additional receptor-complex evidence. However, the complete claim that **atrial cardiomyocytes release BMP10 specifically to signal to endothelial cells through ACVRL1** remains a proposed model rather than experimentally proven cell-to-cell communication.

### 9. What cellular response is expected in the receiver cell, and why?

The expected response is an **endothelial cellular response involving changes in signaling and gene regulation**. This is based on the involvement of ACVRL1 and downstream SMAD signaling proteins in the STRING network. The exact response in the specific atrial-cardiomyocyte/endothelial-cell context would require experimental confirmation.

## References and database links

Human Protein Atlas: https://www.proteinatlas.org/ENSG00000163217-BMP10

https://www.proteinatlas.org/ENSG00000139567-ACVRL1

OmniPath : https://explore.omnipathdb.org/search?q=BMP10&tab=interactions&species=9606


STRING : https://string-db.org/cgi/network?taskId=bKJSJSCK811A&sessionId=bv8aYAqrvuQG

IntAct : https://www.ebi.ac.uk/intact/details/interaction/EBI-16065512
