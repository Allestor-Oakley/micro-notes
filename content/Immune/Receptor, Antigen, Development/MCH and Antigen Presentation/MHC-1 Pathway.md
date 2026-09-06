---
aliases:
  - MHC Class I Pathway
  - Cytosolic Pathway of Antigen Processing
  - Endogenous Antigen Processing Pathway
  - MHC Class I Peptide Loading Complex Assembly
  - Cross-Presentation Pathway
disease_category: Primary Immunodeficiencies / Bare Lymphocyte Syndrome Type I
inheritance_pattern: Autosomal recessive for genetic defects (e.g., TAP1, TAP2, or Tapasin deficiencies)
primary_defect_gene:
  - TAP1
  - TAP2
  - TAPBP
  - PSMB8
  - PSMB9
  - B2M
affected_cells:
  - All Nucleated Cells
  - CD8+ Cytotoxic T Lymphocytes
  - Dendritic Cells
acquired_vs_congenital: Both (Congenital genetic mutations in pathway machinery or Acquired viral/tumor evasion hijacking)
initiating_stimulus: Production of cytosolic foreign proteins (derived from replicating viruses, intracellular bacteria, or mutated tumor-associated antigens) or host-derived defective ribosomal products (DRiPs)
cellular_participants:
  - All Nucleated Cells
  - Dendritic Cells
  - CD8+ Cytotoxic T Lymphocytes
key_cytokines:
  - Interferon-gamma
  - Interferon-alpha
  - Interferon-beta
  - Tumor Necrosis Factor
anatomic_location: Cytosol, rough endoplasmic reticulum (RER) lumen, Golgi apparatus, and cell surface membrane of all nucleated cells
date: 2026-09-06
draft: false
---

### MHC Class I Antigen Processing (Cytosolic Pathway)

#### Initiation & Triggers
*   **Primary Stimulus / Trigger:**
    *   The pathway is triggered by the presence of proteins in the cytosol. These proteins can be endogenous self-proteins (including misfolded proteins or normal proteins undergoing turnover), mutated self-proteins (tumor-associated antigens), or foreign proteins synthesized inside the cell during infection by replicating viruses or cytosolic intracellular bacteria.
    *   A major source of triggers is **Defective Ribosomal Products (DRiPs)**—newly synthesized polypeptides containing translation errors or folding defects that are immediately targeted for rapid degradation, providing real-time immunologic surveillance of cellular protein synthesis.
*   **Anatomic Location of Pathway:**
    *   The pathway begins in the **cytosol** (ubiquitination and proteasomal cleavage), transitions into the **lumen of the rough endoplasmic reticulum [RER]** (peptide translocation, chaperone-assisted folding, and loading), progresses through the **Golgi apparatus** (carbohydrate remodeling), and terminates on the **plasma membrane** (cell surface presentation).
*   **Initial Sensor / Receptor:**
    *   The initial sensor is the host cell's **ubiquitin-activating and ligating enzyme system (E1-E2-E3 cascade)**.
    *   This enzymatic cascade recognizes unfolded, damaged, or foreign cytosolic proteins and covalently attaches chains of **ubiquitin** molecules to lysine residues on the target protein, marking it for degradation.

#### Step-by-Step Cascade
*   **Phase 1 (Recognition/Initiation): Ubiquitination & Proteasomal Cleavage:**
    1.  Target cytosolic proteins are covalently tagged with polyubiquitin chains by E3 ubiquitin ligases.
    2.  The polyubiquitinated protein is recognized and captured by the regulatory caps of the **26S Proteasome** (a large, multi-subunit catalytic machine containing a hollow 20S cylindrical core and two 19S regulatory caps).
    3.  The proteasome unfolds the protein, strips the ubiquitin tags, and threads the polypeptide chain into the central 20S catalytic core, where proteolytic enzymes cleave it into short peptide fragments (typically 3 to 22 amino acids in length).
    4.  *Immunoproteasome Conversion*: In cells exposed to inflammatory cytokines like **Interferon-gamma (IFN-γ)** or **Interferon-alpha/beta (IFN-α/β)**, the constitutive catalytic $\beta$ subunits of the proteasome ($\beta1, \beta2, \beta5$) are replaced by three inducibly synthesized subunits: **$\beta1i$ (LMP2)**, **$\beta2i$ (MECL-1)**, and **$\beta5i$ (LMP7)**. The resulting **immunoproteasome** cleaves proteins with altered specificity, preferentially generating peptides of 8 to 11 amino acids with hydrophobic or basic C-terminal residues, which match the binding requirements of MHC Class I peptide-binding grooves.
*   **Phase 2 (Amplification/Signaling): TAP Transport & Peptide Loading Complex Assembly:**
    1.  The generated cytosolic peptides are captured and transported across the membrane of the rough endoplasmic reticulum (RER) into the RER lumen by the **Transporter associated with Antigen Processing (TAP)**.
    2.  TAP is an ATP-dependent heterodimer composed of **TAP1 (ABCB2)** and **TAP2 (ABCB3)** proteins, members of the ATP-binding cassette (ABC) transporter superfamily. TAP selectively translocates peptides containing 8 to 16 amino acids that possess basic or hydrophobic C-termini.
    3.  *MHC Class I Heavy Chain Folding*: Simultaneously, newly synthesized MHC Class I heavy chains ($\alpha$ chains) are translocated into the RER membrane. To prevent misfolding, the empty heavy chain binds to the integral membrane molecular chaperone **Calnexin**.
    4.  Upon binding **$\beta_2$-microglobulin ($\beta_2m$)** to form the MHC Class I heterodimer, Calnexin dissociates. The heterodimer then associates with a soluble molecular chaperone called **Calreticulin** and a thiol oxidoreductase called **ERp57** (which maintains the disulfide bonds of the MHC cleft).
    5.  *Peptide Loading Complex (PLC) Assembly*: This chaperone-bound heterodimer docks directly onto the TAP transporter via the adaptor protein **Tapasin (TAPBP)**. This forms the macromolecular **Peptide Loading Complex (PLC)**, which consists of:
        *   The TAP1/TAP2 heterodimer
        *   The Tapasin adaptor
        *   The MHC Class I heavy chain paired with $\beta_2m$
        *   The soluble chaperones Calreticulin and ERp57
    6.  *Peptide Editing & Trimming*: Tapasin physically bridges the empty MHC peptide-binding cleft to TAP, positioning the cleft adjacent to the pore where TAP delivers translocated peptides. Tapasin acts as a "peptide editor," stabilizing the empty MHC Class I molecule and promoting the exchange of low-affinity peptides for high-affinity peptides.
    7.  If the TAP-delivered peptide is too long (e.g., 10 to 16 amino acids) to fit the MHC Class I groove, it is recognized and cleaved at its N-terminus by **Endoplasmic Reticulum Aminopeptidase (ERAP)** (specifically ERAP1 or ERAP2) in the RER lumen, trimming it to the optimal length of 8 to 9 amino acids.
*   **Phase 3 (Effector Response): Surface Presentation & CD8+ T Cell Ligation:**
    1.  When a peptide with high affinity binds to the peptide-binding groove (spanning the $\alpha1$ and $\alpha2$ domains), it stabilizes the tertiary structure of the MHC Class I heterodimer ($\alpha$ chain + $\beta_2m$).
    2.  This stable, trimeric peptide-MHC Class I complex dissociates from the Peptide Loading Complex (PLC) and exits the RER in transport vesicles.
    3.  The vesicles fuse with the Golgi apparatus, where the MHC Class I heavy chain undergoes complex carbohydrate remodeling and glycosylation.
    4.  Remodeled complexes are packaged into exocytic transport vesicles, carried along microtubules, and fused with the plasma membrane, displaying the peptide-MHC Class I complex on the extracellular surface of the nucleated cell.
    5.  *Ligation and CTL Activation*: On the cell surface, the displayed peptide-MHC Class I complex is surveyed by **CD8+ Cytotoxic T Lymphocytes (CTLs)**. The $\alpha\beta$ T-Cell Receptor (TCR) of the CTL binds specifically to the combined surface of the peptide and the surrounding $\alpha1/\alpha2$ helices of the MHC Class I cleft.
    6.  Simultaneously, the **CD8 coreceptor** on the CTL binds to the nonpolymorphic $\alpha3$ domain of the MHC Class I heavy chain, stabilizing the TCR-MHC interaction and recruiting the tyrosine kinase **Lck** to initiate the intracellular T-cell activation cascade.
    7.  *Specialized Pathway - Cross-Presentation (Cross-Priming)*: Specialized **CD141+ (Clec9A+) dendritic cells (cDC1)** can ingest extracellular viral or tumor antigens via phagocytosis/endocytosis. Instead of subjecting these antigens to lysosomal degradation, they retrotranslocate the intact extracellular proteins from endosomes/phagosomes into the host cytosol (potentially via the Sec61 channel). Once in the cytosol, these antigens enter the classical cytosolic MHC Class I pathway (ubiquitination, proteasomal cleavage, TAP transport, and PLC loading), allowing the DC to present extracellular-derived peptides on MHC Class I to naive CD8+ T cells to initiate CTL differentiation.
*   **Required Cofactors / Metal Ions:**
    *   **Adenosine Triphosphate (ATP)**: Essential for two active steps: the covalent activation of ubiquitin by the E1 activating enzyme, and the active, conformational pumping of peptides across the RER membrane against a concentration gradient by the TAP1/TAP2 heterodimer.
    *   **Calcium (Ca2+)**: Required to maintain the calcium-dependent chaperoning activity and structural conformations of both **Calnexin** and **Calreticulin** within the RER.
    *   **Zinc (Zn2+)**: Required as an essential catalytic cofactor for the metalloprotease activity of **ERAP1 and ERAP2** during N-terminal peptide trimming in the ER lumen.

#### Regulation & Checkpoints
*   **Inhibitory Molecules & Checkpoints:**
    *   **ER-Associated Degradation (ERAD) Quality Control**: If an MHC Class I heterodimer fails to bind a high-affinity peptide within the RER, it remains structurally unstable. This unstable conformation is recognized by ER-resident quality-control proteins, which retrotranslocate the empty MHC heavy chain out of the RER back into the cytosol. In the cytosol, it is polyubiquitinated and degraded by the 26S proteasome, preventing the display of empty or unstable MHC molecules at the cell surface.
    *   **B-cell and Monocyte CD22 Checkpoints**: N/A
*   **Feedback Loops:**
    *   **IFN-γ Positive Feedback Loop**: Activated CD8+ CTLs and NK cells secrete **Interferon-gamma (IFN-γ)**. IFN-γ binds to the IFN-gamma receptor on target cells, activating the JAK1/JAK2-STAT1 pathway. STAT1 homodimers translocate to the nucleus and directly upregulate the transcription of:
        *   MHC Class I heavy chains and $\beta_2m$
        *   TAP1 and TAP2 translocators
        *   Tapasin chaperone
        *   ERAP1 aminopeptidases
        *   LMP2, LMP7, and MECL-1 immunoproteasome subunits
    *   This feedback loop dramatically increases the speed, capacity, and efficiency of endogenous antigen processing in infected tissues, accelerating CTL-mediated viral clearance.
*   **Mechanisms of Termination / Resolution:**
    *   **Receptor Internalization and Endocytosis**: Peptide-MHC Class I complexes at the cell surface undergo slow, continuous constitutive endocytosis. Once internalized, the complexes are routed to endosomes. If the peptide dissociates in the acidic endosomal environment, the empty heavy chain is routed to lysosomes for degradation, terminating presentation.

#### Physiologic & Pathologic Outcomes
*   **Primary Physiologic Purpose:**
    *   **Intracellular Pathogen Defense**: Continuous sampling and display of the internal proteome of all nucleated cells, enabling the immune system to detect and destroy cells harboring replicating viruses, cytosolic bacteria, or parasites.
    *   **Tumor Surveillance**: Presentation of mutated self-proteins (neoantigens) or aberrantly expressed proteins on tumor cells, triggering CD8+ CTL-mediated tumor lysis.
    *   **Self-Tolerance Education**: During thymic development, presentation of self-peptides on MHC Class I in the thymic cortex and medulla drives positive and negative selection of developing CD8+ single-positive thymocytes, shaping a self-tolerant T-cell repertoire.
*   **Consequence of Pathway Failure:**
    *   **Bare Lymphocyte Syndrome Type I (BLS I)**:
        *   *Genetic Defects*: Autosomal recessive loss-of-function mutations in **TAP1**, **TAP2**, or the **TAPBP** (Tapasin) genes.
        *   *Molecular Consequence*: Severe or complete failure of peptide translocation into the RER (in TAP defects) or complete loss of peptide-loading efficiency (in Tapasin defects). Unstable MHC Class I molecules fail to load, are targeted by ERAD, and are degraded. This results in a **>95% reduction in cell-surface MHC Class I expression** across all tissues.
        *   *Clinical Presentation*: Patients suffer from recurrent, severe, necrotizing respiratory bacterial infections (bronchitis, sinusitis, pneumonia) beginning in early childhood, leading to progressive bronchiectasis. Paradoxically, these patients do not exhibit severe or life-threatening systemic viral infections, because NK cells and CD8+ T cells utilize alternative, TAP-independent or non-classical pathways for baseline viral control. However, they frequently develop chronic, granulomatous skin ulcers on the extremities.
    *   **B2M Genetic Mutation**:
        *   *Genetic Defects*: Homozygous mutations in the **B2M** gene.
        *   *Molecular Consequence*: Total inability to synthesize the $\beta_2$-microglobulin chain. MHC Class I heavy chains cannot assemble correctly, fail to bind peptide, and remain trapped in the RER or are targeted for degradation, leading to a complete absence of surface MHC Class I expression.
*   **Microbial / Tumor Evasion Strategies:**
    *   **TAP Blockade (HSV - ICP47)**: Herpes Simplex Virus synthesizes the **ICP47** protein, which binds with exceptionally high affinity to the cytosolic face of the TAP1/TAP2 heterodimer. ICP47 physically blocks peptide binding and locks the TAP transporter in an inactive conformation, halting peptide translocation.
    *   **TAP Inhibition (HCMV - US6)**: Human Cytomegalovirus produces the **US6** protein. US6 localizes to the RER lumen, where it binds TAP and inhibits ATP binding and hydrolysis, preventing TAP-mediated peptide translocation.
    *   **ERAD Hijacking (HCMV - US2 and US11)**: HCMV-derived **US2** and **US11** proteins bind newly synthesized MHC Class I heavy chains in the RER membrane and physically retrotranslocate them out of the RER into the cytosol, targeting them for rapid degradation by the host 26S proteasome.
    *   **ER Retention (Adenovirus - E3-19K & HCMV - US3)**: The Adenovirus **E3-19K** protein and HCMV **US3** protein bind specifically to MHC Class I molecules within the RER, physically retaining them in the ER and preventing their exit to the Golgi and the cell surface.
    *   **Endocytic Internalization (HIV-1 - Nef)**: The HIV-1 **Nef** protein recruits the host adaptor protein-1 (AP-1) complex to the cytoplasmic tail of cell-surface MHC Class I molecules, triggering rapid endocytosis and routing them to lysosomes for degradation, shielding HIV-infected cells from CTL detection.
    *   **Proteasomal Degradation Blockade (EBV - EBNA1)**: The Epstein-Barr Virus nuclear antigen 1 (**EBNA1**) protein contains a long, repetitive Glycine-Alanine repeat sequence. This specific domain physically blocks proteasomal degradation, preventing the generation of EBNA1 peptides and allowing EBV to persist latently in B cells.
    *   **Tumor Somatic Deletions**: Many solid tumors downregulate the MHC Class I pathway by selecting for somatic mutations or deletions in the **B2M** gene or the **TAP1/TAP2** genes, rendering the tumor cells invisible to tumor-specific CD8+ CTLs.

#### Clinical & Therapeutic Manipulation
*   **Pharmacologic / Biologic Targeting (e.g., Monoclonal Antibodies):**
    *   **Therapeutic Enhancement of Antigen Presentation**: In cancer immunotherapy, treatment with **Type I Interferons (IFN-α/β)** or **Interferon-gamma (IFN-γ)** is used to upregulate the transcription of TAP, Tapasin, immunoproteasomes, and MHC Class I molecules on tumor cells, enhancing their immunogenicity and sensitizing them to checkpoint blockade therapy (such as anti-PD-1 or anti-CTLA-4).
    *   **N/A** (Direct pharmacological agonists of the Peptide Loading Complex are not currently in routine clinical use, although research focuses on small-molecule tapasin mimics).
*   **Use in Vaccines or Immunotherapy:**
    *   **CD8+ T-Cell Directed Vaccines**: Designing vaccines that deliver antigens directly into the host cell cytosol to utilize the classical cytosolic pathway. This is accomplished using:
        *   *mRNA Vaccines*: Lipid nanoparticles deliver mRNA into the host cell cytoplasm, where host ribosomes translate target antigens that are immediately processed as DRiPs or turned-over proteins via the proteasome-TAP-MHC Class I pathway.
        *   *Recombinant Viral Vectors*: Modified, non-replicating viruses (such as Adenovirus vectors) infect host cells and drive the transcription and translation of vaccine antigens directly in the cytosol, generating robust CD8+ CTL responses (cross-priming and direct priming).
        *   *DNA Vaccines*: Plasmids transfect host cells, driving cytosolic antigen synthesis to engage the endogenous Class I presentation pathway.

#### Trivia & Edge Cases
*   **Buzzwords & Descriptors:**
    *   **"Peptide Loading Complex (PLC)"**: The multi-protein RER machinery responsible for stabilizing MHC Class I and executing peptide editing.
    *   **"Defective Ribosomal Products (DRiPs)"**: Newly synthesized proteins that are immediately degraded due to translation or folding defects, acting as the primary rapid-response trigger of the pathway.
    *   **"Immunoproteasome"**: The specialized, cytokine-induced proteasome variant optimized to generate MHC Class I-compatible peptides.
    *   **"Cross-Presentation"**: The specialized process by which extracellular antigens are diverted into the MHC Class I pathway within dendritic cells.
*   **Historical Discoveries or Assays:**
    *   **The Zinkernagel and Doherty Milestone (1974 / 1996 Nobel)**: Rolf Zinkernagel and Peter Doherty demonstrated that CD8+ T cells recognize virus-infected cells only when the viral antigen is presented on host MHC Class I molecules, establishing the foundational concept of **MHC Restriction**.
    *   **The Discovery of the Peptide Pump (1990)**: The identification of the TAP1 and TAP2 genes as the ATP-dependent transporters that physically pump cytosolic peptides across the hydrophobic RER membrane into the secretory pathway.
*   **Exceptions to the Rule:**
    *   **TAP-Independent MHC Class I Presentation**: While the vast majority of peptides presented on MHC Class I require TAP transport, some exceptions exist. Hydrophobic signal sequences of membrane-bound or secreted proteins are cleaved within the RER membrane by **Signal Peptide Peptidase (SPP)** and can load directly onto newly synthesized MHC Class I molecules without ever entering the cytosol or utilizing TAP.
    *   **Erythrocyte MHC Class I Exception**: Mammalian mature erythrocytes completely lack a nucleus and organelles, and thus are the only nucleated-origin cells that completely lack any MHC Class I expression. This renders them completely resistant to CTL-mediated lysis but highly susceptible to certain intracellular parasites (e.g., Plasmodium) which evade CD8+ T cell detection.
    *   **Alternative LMP Subunit Composition**: While LMP2, LMP7, and MECL-1 are typically induced as a coordinated triad by IFN-γ, intermediate "mixed" proteasomes containing a blend of constitutive and inducible subunits can assemble in tissues under low-level inflammatory stress, creating a highly diverse and tissue-specific peptide repertoire.
```