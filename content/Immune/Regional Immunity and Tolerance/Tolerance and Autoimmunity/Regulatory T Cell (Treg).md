---
aliases:
  - Regulatory T Cells
  - Treg Cells
  - Thymus-derived Regulatory T Cells
  - Peripheral Regulatory T Cells
  - Suppressor T Cells
  - CD4+ CD25+ Regulatory T Lymphocytes
defining_cd_markers:
  - CD3
  - CD4
  - CD25
  - CD127
  - CD152
cell_lineage: Lymphoid -> T Cell -> CD4+ T helper lineage -> Regulatory T cell lineage
primary_location: Thymic medulla (for development), peripheral secondary lymphoid organs, mucosal lamina propria, and non-lymphoid tissues
key_transcription_factors:
  - FOXP3
  - Helios
tissue_homing_receptors:
  - CCR4
  - CCR6
  - CCR7
  - CCR9
  - α4β7 integrin
date: 2026-09-06
draft: false
---

### Regulatory T Cell (Treg)

#### Origin & Maturation
*   **Lineage & Precursors:**
    *   Regulatory T cells (Tregs) belong to the lymphoid lineage, originating from multipotent hematopoietic stem cells in the bone marrow that commit to the T-lymphocyte pathway.
    *   During thymic development, lymphoid progenitors progress through double-negative (DN1 to DN4) and double-positive (DP, CD4+CD8+) stages, assembling functional αβ T-cell receptors (TCRs) via somatic V(D)J recombination.
    *   In the thymus, thymocytes with MHC Class II-restricted TCRs commit to the CD4+ lineage. Those that recognize self-antigen with intermediate-to-high (but below the threshold for deletion) avidity are rescued and directed to mature into thymus-derived regulatory T cells (tTregs).
    *   Alternatively, naive CD4+ single-positive T cells that egress into the periphery can be induced to differentiate into peripheral regulatory T cells (pTregs) upon specific antigen recognition in the presence of transforming growth factor-beta (TGF-β) and retinoic acid.
*   **Site of Development & Maturation:**
    *   For **tTregs**: Early lineage commitment, positive selection, and subsequent lineage skewing occur within the specialized microenvironments of the thymic cortex and thymic medulla.
    *   For **pTregs**: Maturation and polarization of naive CD4+ precursors occur in peripheral secondary lymphoid tissues (such as lymph nodes, spleen, and gut-associated lymphoid tissues) draining barrier epithelial tissues.
*   **Key Transcription Factors for Differentiation:**
    *   **FOXP3 (Forkhead Box P3)**: The master, lineage-defining transcription factor encoded by the FOXP3 gene on the X chromosome (Xp11.23). FOXP3 acts as a transcriptional repressor and activator that binds to promoters and enhancers of Treg-defining genes. It directly upregulates genes encoding CD25, CTLA-4, and GITR, while actively repressing the transcription of IL-2 and CD127 (IL-7Rα). FOXP3 epigenetic stability is maintained by demethylation of the conserved non-coding sequence 2 (CNS2) region within the FOXP3 locus.
    *   **Helios**: A zinc-finger transcription factor of the Ikaros family. It is highly expressed in tTregs and is often utilized as a marker to distinguish thymus-derived Tregs from peripherally induced Tregs.
*   **Selection & Tolerance Mechanisms:**
    *   **tTreg Selection**: Immature CD4+ SP thymocytes that encounter self-peptides presented on medullary thymic epithelial cells (mTECs) or medullary dendritic cells with high affinity are selected to become tTregs instead of undergoing apoptosis. This process is heavily dependent on the AIRE (Autoimmune Regulator) gene in mTECs, which drives the ectopic expression of tissue-restricted self-antigens.
    *   **pTreg Selection**: Naive CD4+ T cells that encounter foreign, commensal, or dietary antigens presented by resting, immature dendritic cells in the absence of strong costimulatory signals are skewed to express FOXP3, establishing peripheral tolerance to non-harmful environmental proteins.
    *   **Dominant Tolerance**: Tregs act as the primary mediator of dominant peripheral tolerance, actively suppressing self-reactive effector T cells that have escaped thymic clonal deletion.
*   **Circulation & Extravasation Dynamics:**
    *   Naive and resting Tregs express L-selectin (CD62L) and CCR7 (CD197), allowing them to continuously recirculate through blood and secondary lymphoid organs by crossing high endothelial venules (HEVs).
    *   Activated/effector Tregs downregulate CD62L and CCR7 and upregulate tissue-specific homing receptors to migrate into inflamed tissues and mucosal barriers:
        *   *Gut Homing*: Express CCR9 and the integrin α4β7, allowing them to extravasate along blood vessels expressing MAdCAM-1 and home to the intestinal lamina propria.
        *   *Skin Homing*: Express Cutaneous Lymphocyte Antigen (CLA) and the chemokine receptors CCR4 and CCR10 to migrate to the dermis and epidermis.
        *   *Inflammation Homing*: Express CCR6 (CD196) and CXCR3 to follow gradients of CCL20 and CXCL9/CXCL10 into sites of active tissue injury.

#### Receptors & Surface Markers
*   **Defining CD Markers:**
    *   **CD3**: The invariant multi-subunit signaling complex associated with the TCR.
    *   **CD4**: Monomeric glycoprotein coreceptor that binds to the nonpolymorphic β2 domain of MHC Class II molecules.
    *   **CD25**: The alpha chain of the IL-2 receptor (IL-2Rα), constitutively expressed at exceptionally high surface levels on Tregs.
    *   **CD127**: The alpha chain of the IL-7 receptor (IL-7Rα). Tregs characteristically express extremely low levels of CD127, which serves as a key cell-surface marker to isolate viable human Tregs.
    *   **CD152 (CTLA-4)**: Cytotoxic T-lymphocyte-associated protein 4, constitutively expressed on the surface of regulatory T cells.
*   **Antigen Recognition Receptors:**
    *   **αβ T-Cell Receptor (TCR)**: Disulfide-linked heterodimer of α and β chains. The TCR repertoire of tTregs is highly diverse but strongly biased toward recognizing self-peptide-MHC Class II complexes. pTreg TCRs are similarly diverse but recognize environmental, commensal, or food-derived peptides.
*   **Co-stimulatory & Inhibitory Receptors:**
    *   **CTLA-4 (CD152)**: High-affinity competitive inhibitor of CD28 costimulation. It binds B7-1 (CD80) and B7-2 (CD86) with significantly higher affinity and avidity than CD28, executing physical removal of these ligands from the APC membrane.
    *   **GITR (CD357 / Glucocorticoid-Induced TNFR-Related Protein)**: Highly and constitutively expressed on Tregs; receptor ligation delivers survival and activating signals to the Treg pool.
    *   **LAG-3 (CD223)**: Lymphocyte Activation Gene 3, binds with high affinity to MHC Class II molecules on APCs, delivering inhibitory signals that suppress APC activation.
    *   **TIGIT**: T-cell immunoreceptor with Ig and ITIM domains, suppresses CD4+ and CD8+ T-cell activation.
    *   **PD-1 (CD279)**: Programmed Cell Death Protein 1, expressed on activated Tregs to modulate suppressive capacity.
*   **Cytokine & Chemokine Receptors:**
    *   **IL-2 Receptor Complex (CD25, CD122, CD132)**: High-affinity heterotrimeric receptor complex. CD25 associates with CD122 (IL-2Rβ) and CD132 (common gamma chain, γc) to signal downstream via STAT5.
    *   **TGF-β Receptors (TGFβR1, TGFβR2)**: Bind Transforming Growth Factor-beta to maintain epigenetic stability of the FOXP3 locus.
    *   **IL-10 Receptor (IL-10RA / CD210, IL-10RB)**: Heterodimeric receptor that transduces IL-10 signals.
    *   **CCR4, CCR6, CCR7, CCR9**: Chemokine receptors that direct systemic recirculation and tissue-specific homing.
*   **Tissue Homing & Adhesion Molecules (Integrins/Selectins):**
    *   **α4β7 integrin**: Mediates homing to mucosal endothelial MAdCAM-1.
    *   **LFA-1 (CD11aCD18)**: Integrin that binds ICAM-1 (CD54) on APCs and endothelial cells to stabilize physical contacts.
    *   **VLA-4 (CD49dCD29)**: Integrin that binds VCAM-1 (CD106) on inflamed vascular walls.
    *   **CD44**: Cell-surface glycoprotein that binds hyaluronic acid, retaining Tregs in the extracellular matrix of non-lymphoid tissues.

#### Activation & Differentiation
*   **Primary Activation Signals (Signal 1, 2, 3):**
    *   **For tTregs (Thymus)**:
        *   *Signal 1*: High-to-intermediate avidity binding of the immature TCR to self-peptide-MHC Class II complexes on medullary thymic APCs.
        *   *Signal 2*: Strong costimulatory signals transduced via CD28 binding to CD80/CD86, which is strictly required for the survival and initial upregulation of FOXP3.
        *   *Signal 3*: Interleukin-2 (IL-2) provided by neighboring conventional T cells, which stabilizes FOXP3 expression.
    *   **For pTregs (Periphery)**:
        *   *Signal 1*: Naive CD4+ T cell TCR binds to foreign/commensal peptide-MHC Class II complexes displayed on immature, non-activated dendritic cells.
        *   *Signal 2*: Weak CD28 costimulation (due to low CD80/CD86 levels on resting DCs) combined with high inhibitory signaling via PD-1.
        *   *Signal 3*: High local concentrations of **TGF-β** synergizing with **IL-2** and dendritic cell-derived **retinoic acid**.
*   **Signal Transduction Cascades:**
    *   **IL-2R Signaling (JAK-STAT Pathway)**: IL-2 binding to the CD25/CD122/CD132 complex activates receptor-associated **JAK1** and **JAK3** kinases. JAK1/3 phosphorylate the cytoplasmic tail of CD122, recruiting the transcription factor **STAT5** (STAT5A and STAT5B). STAT5 is tyrosine-phosphorylated, homodimerizes, and translocates to the nucleus, where it binds to the conserved non-coding sequence 2 (CNS2) enhancer region of the FOXP3 promoter, maintaining stable, long-term FOXP3 transcription.
    *   **TGF-β Signaling (Smad Pathway)**: TGF-β binding to TGFβR1/2 triggers serine/threonine kinase activity that phosphorylates **Smad2** and **Smad3**. Phosphorylated Smad2/3 associate with Smad4 to form a transcriptional complex that translocates to the nucleus and binds to the CNS1 enhancer region of the FOXP3 locus, initiating de novo FOXP3 expression in naive CD4+ T cells.
    *   **PI3K/AKT/mTOR Restriction**: High AKT/mTOR signaling (which occurs during strong conventional T-cell activation) phosphorylates and excludes Foxo1 and Foxo3 from the nucleus, repressing FOXP3 expression. Treg differentiation and maintenance strictly require *low* PI3K/Akt/mTOR activity. This metabolic and signaling restriction is enforced by the high expression of the lipid phosphatase **PTEN** (Phosphatase and Tensin Homolog) in Tregs, which continually counteracts PI3K activity.
*   **Polarization & Subsets:**
    *   **Thymus-derived Tregs (tTregs / nTregs)**: Differentiated in the thymus. Characteristically express Helios and Neuropilin-1 (CD304). Their TCRs are biased toward self-antigens, and they primarily function to suppress systemic autoimmunity.
    *   **Peripheral Tregs (pTregs / iTregs)**: Differentiated in peripheral tissues (especially the intestinal lamina propria) from naive conventional CD4+ T cells. They typically lack Helios and Neuropilin-1. Their TCRs recognize commensal, dietary, or environmental antigens, preventing inflammatory mucosal responses and food allergies.

#### Effector Functions & Secretory Profile
*   **Primary Effector Mechanisms:**
    1.  **CTLA-4-Mediated Trans-endocytosis of Costimulators**: Tregs constitutively express high levels of CTLA-4 (CD152). CTLA-4 binds to CD80 and CD86 on antigen-presenting cells with much higher affinity than CD28. Upon binding, the Treg physically pulls CD80/CD86 out of the APC cell membrane via a process called **trans-endocytosis**. These costimulators are internalized and degraded within lysosomes inside the Treg. This depletes CD80/CD86 from the APC surface, rendering the APC incapable of delivering the essential costimulatory Signal 2 (via CD28) to conventional naive T cells, inducing functional unresponsiveness (anergy).
    2.  **Secretion of Immunosuppressive Cytokines**: Tregs secrete high levels of IL-10, TGF-β, and IL-35:
        *   *IL-10*: Binds to IL-10R on macrophages and dendritic cells, suppressing their production of pro-inflammatory cytokines (IL-12, TNF, IL-1) and downregulating MHC Class II and B7 costimulator expression.
        *   *TGF-β*: Directly inhibits T-cell proliferation, classical macrophage activation, and inflammatory cytokine secretion, while promoting tissue repair and wound healing.
    3.  **IL-2 Consumption ("IL-2 Sink")**: Due to continuous, exceptionally high-level expression of CD25 (IL-2Rα), Tregs rapidly capture and internalize extracellular IL-2. Because Tregs cannot transcribe IL-2 themselves (repressed by FOXP3), they act as a physical "IL-2 sink," depriving neighboring activated conventional effector T cells of this essential survival and clonal expansion factor. This deprivation drives the effector T cells into apoptosis via growth factor starvation.
    4.  **Adenosine Generation (Ectonucleotidase Activity)**: Tregs express the membrane ectoenzymes **CD39** and **CD73**. CD39 converts extracellular pro-inflammatory ATP (released by damaged cells) into AMP. CD73 then hydrolyzes AMP into **adenosine**. Extracellular adenosine binds to A2A adenosine receptors on activated T cells and APCs, activating adenylate cyclase to raise intracellular cAMP, which strongly suppresses proximal TCR signaling and cytokine production.
    5.  **Direct Cytolysis**: Tregs can secrete perforin and granzymes (A and B) to directly lyse effector T cells or APCs in a contact-dependent manner.
*   **Key Cytokines Secreted:**
    *   **Interleukin-10 (IL-10)**: Essential immunosuppressive cytokine that limits inflammatory pathology.
    *   **Transforming Growth Factor-beta (TGF-β)**: Suppresses effector lymphocytes and classical macrophage activation.
    *   **Interleukin-35 (IL-35)**: Heterodimeric cytokine of the IL-12 family (composed of EBI3 and IL-12p35 subunits) that directly suppresses T-cell proliferation.
*   **Target Cells & Pathogens:**
    *   **Target Cells**: Dendritic cells, macrophages, conventional CD4+ T helper cells (Th1, Th2, Th17), CD8+ cytotoxic T cells, B lymphocytes, and Natural Killer (NK) cells.
    *   **Pathogens**: Tregs do not directly target pathogens. Instead, they act during active infections (bacterial, viral, fungal, parasitic) to suppress and resolve the host immune response once the pathogen is cleared, preventing excessive collateral immunopathological tissue damage.
*   **Memory Generation & Lifespan:**
    *   Tregs are long-lived and maintain a pool of memory-like Tregs (activated Tregs) that reside within peripheral tissues (such as the skin and gut) to rapidly suppress recurrent local inflammatory responses.
    *   Treg homeostatic survival is strictly dependent on continuous paracrine IL-2 provided by conventional T cells, signaling via STAT5.

#### Pathologic Relevance
*   **Role in Protective Host Defense:**
    *   Provides the essential check that prevents fatal systemic autoimmune destruction.
    *   Aids in the resolution of acute inflammation, allowing tissue repair and wound healing. Tregs express **Amphiregulin**, an epidermal growth factor receptor (EGFR) ligand that directly stimulates epithelial cell proliferation and tissue regeneration.
*   **Role in Hypersensitivity or Autoimmunity:**
    *   **IPEX Syndrome (Immune Dysregulation, Polyendocrinopathy, Enteropathy, X-linked)**: Caused by loss-of-function mutations in the **FOXP3** gene. This leads to a complete absence of functional Tregs. Presenting in infancy, affected males suffer from a catastrophic triad of:
        1.  *Polyendocrinopathy*: Autoimmune destruction of endocrine glands, leading to early-onset Type 1 Diabetes and autoimmune thyroiditis.
        2.  *Enteropathy*: Severe, chronic autoimmune enteropathy, causing intractable diarrhea, villous atrophy, and malabsorption.
        3.  *Dermatitis*: Severe, widespread eczematous dermatitis.
    *   **Autoimmune Diseases**: Deficiencies in Treg numbers or functional suppressive capacity are associated with the pathogenesis of Type 1 Diabetes, Multiple Sclerosis, Rheumatoid Arthritis, and Systemic Lupus Erythematosus.
    *   **Allergy & Asthma**: Defective mucosal Treg function permits runaway Th2 and Th17 responses to environmental allergens, driving allergic rhinitis, atopic dermatitis, and bronchial asthma.
*   **Microbial Evasion of this Cell Type:**
    *   **Tumor Microenvironment Hijacking**: Many solid tumors actively exploit Treg biology to evade host immune surveillance. Tumor cells and tumor-associated macrophages secrete high concentrations of the chemokine **CCL22**. Tregs express the chemokine receptor **CCR4**, which binds CCL22, driving massive recruitment of Tregs into the tumor parenchyma. Additionally, tumor-derived TGF-β converts conventional CD4+ T cells into pTregs within the tumor stroma. These tumor-resident Tregs suppress anti-tumor CTLs and NK cells, protecting the tumor from immunological clearance.
    *   **Helminth Chronicity**: Large parasitic helminths secrete immunomodulatory molecules that actively induce host Treg differentiation. The resulting high levels of Treg-derived IL-10 and TGF-β suppress protective Th2-mediated helminth clearance, allowing the parasite to survive chronically in the host.

#### Trivia & Edge Cases
*   **Buzzwords & Descriptors:**
    *   **"Dominant Tolerance"**: Active suppression of the immune system by regulatory cells, as opposed to passive mechanisms of tolerance like clonal deletion or anergy.
    *   **"IL-2 Sink"**: The physiological process where Tregs capture and deplete local IL-2 to starve activated conventional T cells.
    *   **"Trans-endocytosis"**: The physical removal and internal degradation of APC-bound CD80/CD86 by Treg-expressed CTLA-4.
    *   **"IPEX"**: The definitive, clinical diagnostic acronym for genetic FOXP3 deficiency.
*   **Key Experimental Markers:**
    *   **FOXP3**: Intracellular master transcription factor.
    *   **CD25(high) and CD127(low/absent)**: Gating strategy used in clinical flow cytometry to identify and isolate viable human regulatory T cells.
    *   **Helios**: Intracellular zinc-finger transcription factor used to distinguish tTregs from pTregs.
    *   **CD39 / CD73**: Surface ectonucleotidases analyzed to verify adenosine-producing capability.
*   **Exceptions to the Rule:**
    *   **The CD127 Exception**: Activated CD4+ conventional effector T cells upregulate the IL-7 receptor alpha chain (CD127) to maintain homeostatic survival. Tregs are a unique exception; FOXP3 directly binds to and represses the CD127 promoter, making CD127 expression characteristically low or absent on Tregs despite their highly activated functional state.
    *   **Transient Human FOXP3 Expression**: In mice, FOXP3 is strictly restricted to cells with suppressive regulatory function. In humans, however, conventional CD4+ effector T cells can transiently express low levels of FOXP3 upon acute TCR activation. These transiently FOXP3+ human effector T cells do not possess suppressive capacity, representing an important species-specific difference in experimental immunology.
    *   **T Follicular Regulatory (Tfr) Cells**: A specialized subset of regulatory T cells that express FOXP3, CD25, and **CXCR5**. Driven by BCL-6, Tfr cells migrate selectively into the light zones of germinal centers within secondary lymphoid follicles. Here, they actively suppress Tfh cells and prevent them from selecting self-reactive B-cell clones, representing a crucial follicular checkpoint against autoantibody-driven autoimmunity.