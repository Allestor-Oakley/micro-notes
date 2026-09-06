---
aliases:
  - B Lymphocytes
  - B Cells
  - Follicular B cells
  - Marginal zone B cells
  - B-1 cells
defining_cd_markers:
  - CD19
  - CD20
  - CD21
  - CD22
  - CD23
  - CD79a
  - CD79b
  - CD10
  - CD40
  - CD268
cell_lineage:
  - Lymphoid lineage
primary_location:
  - Secondary lymphoid organs
  - Spleen
  - Lymph nodes
  - Mucosal lymphoid tissues
  - Blood
  - Bone marrow
key_transcription_factors:
  - PAX5
  - EBF
  - E2A
  - BLIMP1
  - BCL6
  - IRF4
  - XBP1
tissue_homing_receptors:
  - CXCR5
  - CXCR4
  - CCR7
  - alpha4beta7
date: 2026-09-06
draft: false
---

### B Cell

#### Origin & Maturation
*   **Lineage & Precursors:**
    - B lymphocytes develop from pluripotent hematopoietic stem cells (HSCs) in the adult bone marrow (or fetal liver during embryonic development).
    - HSCs differentiate into Common Lymphoid Progenitors (CLPs). Commitment to the B-cell lineage is driven by the coordinated action of transcription factors E2A, early B-cell factor (EBF), and PAX5. These factors induce the expression of B lineage-specific genes (such as CD19, CD10, and the recombinases RAG1 and RAG2), making the immunoglobulin (Ig) heavy-chain chromatin locus accessible to the somatic recombination machinery.
*   **Site of Development & Maturation:**
    - The adult bone marrow is the primary generative lymphoid organ where the majority of B-cell maturation stages occur (HSC -> CLP -> pro-B -> pre-B -> immature B).
    - Fetal liver is the generative site for embryonic B-1 lineage cells, which populate mucosal tissues and pleural/peritoneal cavities.
    - Follicular B cells complete their functional maturation in the white pulp of the spleen. Naive immature follicular B cells leave the bone marrow, travel through the blood, enter the spleen via the marginal zone, and migrate into the splenic white pulp where they finish maturation.
*   **Key Transcription Factors for Differentiation:**
    - **E2A and EBF:** Essential for early B-lineage commitment and opening the Ig loci; they induce the expression of PAX5 and RAG1/RAG2.
    - **PAX5 (B cell-specific activator protein):** The master regulator of B-cell commitment, suppressing alternative lineage options and inducing B-lineage genes (CD19, Igα/CD79a, Igβ/CD79b, BLNK).
    - **BLIMP-1 (B-lymphocyte-induced maturation protein 1):** Essential for plasma cell differentiation. It is a transcriptional repressor that shuts down BCL-6 and PAX5, allowing terminally differentiated plasma cells to produce large amounts of secreted immunoglobulins.
    - **BCL-6 (B-cell lymphoma 6):** The master transcription factor for the germinal center reaction. It maintains B cells in a highly proliferative, rapid-cycling state, promotes somatic hypermutation, and inhibits premature plasma cell differentiation (blocks BLIMP-1).
    - **IRF4 (Interferon Regulatory Factor 4):** Cooperates with BLIMP-1 to drive plasma cell commitment; induces XBP1 expression.
    - **XBP1 (X-box binding protein 1):** Transcription factor downstream of IRF4 that governs the unfolded protein response (UPR) in plasma cells, allowing them to expand their rough endoplasmic reticulum to accommodate massive antibody synthesis and secretory loads without dying of ER stress.
*   **Selection & Tolerance Mechanisms:**
    - **Central Tolerance (Bone Marrow):** Immature B cells expressing a complete membrane IgM BCR are screened for self-reactivity in the bone marrow:
        - **Receptor Editing:** High-avidity recognition of multivalent self-antigens on bone marrow stromal cells triggers strong cross-linking of the BCR. This signals the immature B cell to reactivate RAG1 and RAG2 genes, leading to further V-J recombination at the light-chain loci (primarily κ first, then λ if κ fails). This replaces the self-reactive light chain with a new, non-self-reactive light chain, salvaging the lymphocyte.
        - **Clonal Deletion:** If receptor editing fails to produce a non-autoreactive BCR, the self-reactive immature B cell is deleted via apoptosis. This is mediated by the mitochondrial apoptotic pathway, where BIM (a pro-apoptotic BH3-only protein) activates BAX and BAK, causing mitochondrial outer membrane permeabilization, cytochrome c release, and caspase-9/caspase-3 executioner cascade activation.
        - **Anergy:** Recognition of soluble self-antigens (which do not cross-link BCRs strongly) results in down-regulation of receptor expression and functional unresponsiveness (anergy).
    - **Peripheral Tolerance:** Autoreactive B cells that escape central tolerance are controlled in the periphery by:
        - **Anergy:** Encounter with self-antigen without T-cell help leads to chronic functional unresponsiveness.
        - **Exclusion from Follicles:** Anergic B cells are excluded from lymphoid follicles (which are crucial for survival niches) due to low CXCR5 and inability to compete with naive B cells for survival factors like BAFF.
        - **Inhibitory Receptors:** Chronic engagement of B-cell inhibitory receptors (e.g., CD22, FcγRIIB) raises the activation threshold, suppressing self-reactivity.
*   **Circulation & Extravasation Dynamics:**
    - **Lymph Node / Mucosal Entry:** Naive follicular B cells leave the blood and enter secondary lymphoid organs (lymph nodes, Peyer's patches) across specialized High Endothelial Venules (HEVs).
    - **Extravasation Steps:**
        - **Rolling:** L-selectin (CD62L) on B cells binds to peripheral node addressin (PNAd) on HEVs.
        - **Integrin Activation:** Chemokines CCL19/CCL21 and CXCL12 bound to the HEV luminal surface activate B-cell integrins (e.g., LFA-1 / CD11aCD18).
        - **Stable Adhesion & Transmigration:** LFA-1 binds firmly to ICAM-1 (CD54) and ICAM-2 (CD102) on HEVs, enabling paracellular or transcellular migration into the outer T-cell zone (paracortex).
        - **Follicular Homing:** Once in the paracortex, naive B cells respond to a gradient of CXCL13 (produced by follicular dendritic cells and follicular fibroblastic reticular cells). B cells express the chemokine receptor CXCR5, which drives their directed migration from the T-cell area into the primary follicles (the B-cell zone).
    - **Spleen Entry:** Naive B cells enter splenic white pulp through the marginal zone of the spleen, guided by CXCL13-CXCR5 gradients, bypassing HEV-dependent mechanisms.
    - **Spleen/Lymph Node Egress:** If naive B cells do not encounter their cognate antigen within several hours, they upregulate S1PR1 (CD363). They respond to the concentration gradient of sphingosine 1-phosphate (S1P), which is kept high in the lymph and blood and low in the parenchyma (due to S1P lyase). This pulls the B cells into the lymph node medullary sinus/efferent lymphatics or the splenic red pulp to return to the blood.

#### Receptors & Surface Markers
*   **Defining CD Markers:**
    - **CD19:** A 95 kD transmembrane glycoprotein expressed on B lineage cells from the pro-B stage to mature B cells (lost on terminally differentiated plasma cells). It acts as a crucial signaling component of the B-cell coreceptor complex.
    - **CD20:** A transmembrane protein expressed on B cells from the late pro-B stage until the plasma cell stage. It regulates calcium transport and is targeted by Rituximab.
    - **CD21 (Complement Receptor 2 / CR2):** A 145 kD receptor for the complement fragment C3d. It forms a complex with CD19 and CD81 on mature B cells, serving as the B-cell coreceptor to dramatically enhance BCR signaling. It is also the receptor for Epstein-Barr Virus (EBV).
    - **CD22 (Siglec-2):** A sialic acid-binding lectin expressed on mature B cells that contains ITIMs in its cytoplasmic tail, recruiting SHP-1 to act as an inhibitory receptor.
    - **CD23:** Low-affinity Fc receptor for IgE (FcεRII) expressed on activated B cells and FDCs.
    - **CD40:** A member of the TNF receptor superfamily expressed on B cells. It binds to CD154 (CD40L) on activated helper T cells, providing the critical costimulatory Signal 2 for T-dependent B-cell activation, germinal center formation, somatic hypermutation, and isotype switching.
    - **CD79a (Igα) & CD79b (Igβ):** Invariant heterodimer associated with membrane Ig, containing cytoplasmic ITAMs that mediate BCR signal transduction.
    - **CD10 (Neprilysin):** Zinc metalloendopeptidase marker for pre-B cells and germinal center B cells.
    - **CD138 (Syndecan-1):** Heparan sulfate proteoglycan marker highly expressed on plasma cells.
*   **Antigen Recognition Receptors:**
    - **Membrane Immunoglobulins (mIg):** Naive B cells co-express mIgM and mIgD with identical antigen specificity via alternative splicing of primary RNA transcripts.
    - Each mIg is composed of two identical heavy (H) chains and two identical light (L) chains (either κ or λ). H-chains have 1 variable (VH) domain and 3 or 4 constant (CH) domains. L-chains have 1 variable (VL) domain and 1 constant (CL) domain. Hypervariable loops (CDR1, CDR2, CDR3) on VH and VL assemble to form the antigen-binding cleft. Membrane Ig molecules have hydrophobic C-terminal transmembrane segments and short cytoplasmic tails (only 3 amino acids in mIgM/mIgD). They cannot signal on their own and must associate with Igα and Igβ.
*   **Co-stimulatory & Inhibitory Receptors:**
    - **B-Cell Coreceptor Complex (CD21/CD19/CD81):** CD21 binds C3d-opsonized antigens, which clusters CD19 next to the BCR. BCR-associated LYN phosphorylates the CD19 cytoplasmic tail, recruiting PI3-kinase. PI3K generates PIP3, which recruits and activates BTK and PLCγ2, lowering the threshold for B-cell activation by 100- to 1000-fold.
    - **CD40 (Costimulatory):** Binds CD154 (CD40L), activating TRAFs (TRAF2, TRAF3, TRAF5, TRAF6) to trigger canonical and non-canonical NF-κB, MAPK, and PI3K pathways.
    - **CD80 (B7-1) & CD86 (B7-2):** Expressed on activated B cells; bind CD28 on T cells to provide costimulation to CD4+ T helper cells.
    - **FcγRIIB (CD32) (Inhibitory):** Low-affinity Fc receptor for IgG. When antibody-antigen complexes cross-link FcγRIIB to the BCR (antibody feedback), the ITIM on the cytoplasmic tail of FcγRIIB is phosphorylated by LYN, recruiting the inositol phosphatase SHIP (SH2 domain-containing inositol phosphatase). SHIP hydrolyzes PIP3 to PIP2, depleting membrane docking sites for BTK, Akt, and PLCγ2, thus terminating BCR activation.
    - **CD22 (Inhibitory):** ITIMs recruit SHP-1 (SH2 domain-containing protein tyrosine phosphatase 1), which dephosphorylates active signaling intermediates (like Igα, Igβ, SYK, and PLCγ2).
*   **Cytokine & Chemokine Receptors:**
    - **CXCR5 (CD185):** Chemokine receptor for CXCL13, directing follicular homing.
    - **CXCR4 (CD184):** Receptor for CXCL12 (SDF-1), mediating plasma cell homing to bone marrow niches.
    - **BAFF Receptor (BAFF-R / CD268):** TNFR family member that binds BAFF (BLyS), activating non-canonical NF-κB to transmit crucial tonic survival signals in transitional and mature naive B cells.
    - **TACI (CD267) & BCMA (CD269):** Receptors for BAFF and APRIL expressed on activated B cells and plasma cells, promoting long-lived plasma cell survival and isotype switching.
    - **IL-4 Receptor (IL-4R):** Directs IgE class switching.
    - **IL-21 Receptor (IL-21R):** High expression on germinal center B cells; drives proliferation and plasma cell differentiation.
*   **Tissue Homing & Adhesion Molecules (Integrins/Selectins):**
    - **L-selectin (CD62L):** Rolling on HEVs.
    - **LFA-1 (CD11aCD18) & Mac-1 (CD11bCD18):** Adhesion and transmigration.
    - **alpha4beta7 Integrin:** Gut-homing receptor that binds to MAdCAM-1 on intestinal lamina propria venules and Peyer's patch HEVs.

#### Activation & Differentiation
*   **Primary Activation Signals (Signal 1, 2, 3):**
    - **Signal 1 (Antigen Ligation):** Polyvalent antigens (e.g., repeating polysaccharides, or clustered proteins) bind and cross-link membrane Ig receptors.
    - **Signal 2 (Costimulation):**
        - For **T-Dependent (TD) Protein Antigens:** Activated CD4+ T helper cells (specifically Tfh cells) express CD154 (CD40L) which binds to CD40 on the B cell.
        - For **T-Independent (TI) Non-Protein Antigens:** Polyvalent cross-linking of BCRs provides strong signals, supplemented by Toll-like receptors (TLRs) recognizing PAMPs (Signal 2) or complement fragments (C3d) binding CD21 (CR2).
    - **Signal 3 (Cytokines):** Tfh-derived or dendritic cell-derived cytokines (like IL-21, IL-4, IFN-γ, IL-10) bind to B-cell cytokine receptors to guide proliferation, somatic hypermutation, and heavy-chain class switching.
*   **Signal Transduction Cascades:**
    - **BCR Proximal Signaling:** Cross-linking clusters the BCR complexes into lipid rafts. This brings associated SRC-family tyrosine kinases (LYN, FYN, BLK) close to the cytoplasmic domains of Igα and Igβ, phosphorylating their ITAM tyrosine residues.
    - **SYK & Signalosome Assembly:** Phosphorylated ITAMs act as docking sites for the tandem SH2 domains of SYK (Spleen Tyrosine Kinase). Active SYK phosphorylates the scaffold adaptor protein SLP-65 (BLNK).
    - **Downstream Pathways:**
        - **Calcium - NFAT Pathway:** BTK (phosphorylated and activated by SYK/LYN and recruited to the membrane by PIP3) phosphorylates and activates PLCγ2 (phospholipase C γ2). PLCγ2 hydrolyzes membrane PIP2 into IP3 and DAG. Soluble IP3 binds to endoplasmic reticulum (ER) receptors, releasing intracellular calcium stores. Depleted ER calcium is sensed by STIM1, opening plasma membrane CRAC (ORAI1) channels. Extracellular calcium enters the cytosol, binds calmodulin, and activates the phosphatase calcineurin. Calcineurin dephosphorylates the transcription factor NFAT, which translocates to the nucleus.
        - **PKCβ - NF-κB Pathway:** Membrane-bound DAG recruits and activates PKCβ. PKCβ phosphorylates components of the CBM (CARMA1-BCL10-MALT1) complex, leading to IκB kinase (IKK) activation, phosphorylation and degradation of IκB, and nuclear translocation of NF-κB (inducing survival and activation genes).
        - **Ras - MAPK Pathway:** GEFs (like SOS, recruited by GRB2 to SLP-65) activate RAS. Active RAS-GTP initiates the Mitogen-Activated Protein (MAP) kinase cascade: RAF -> MEK -> ERK1/2. Concurrently, RAC-GTP activates JNK. Active ERK and JNK phosphorylate nuclear substrates, driving the formation of the AP-1 transcription factor (FOS-JUN heterodimer).
        - **PI3K - Akt Pathway:** BCR signaling recruits PI3-kinase, generating PIP3 to recruit Akt. Akt transmits survival signals (upregulating Bcl-2, Bcl-xL) and coordinates with mTOR to drive metabolic shifts.
*   **Polarization & Subsets:**
    - **Follicular (B-2) B Cells:** The largest population, residing in lymphoid follicles of secondary lymphoid organs. They express high CXCR5, co-express mIgM and mIgD, develop postnatally from bone marrow HSCs, and are highly dependent on T-cell help to undergo germinal center reactions, affinity maturation, class switching, and memory generation.
    - **Marginal Zone B Cells:** Reside in the splenic marginal zone, expressing high levels of IgM, CD21, and CD1c but low IgD. They develop postnatally, respond rapidly to blood-borne polysaccharide and lipid antigens (TI antigens) by differentiating into short-lived IgM-secreting plasma cells, and act as a first line of defense against encapsulated bacteremic pathogens.
    - **B-1 Lymphocytes:** Develop mainly from fetal liver precursors. They reside in mucosal tissues and pleural/peritoneal cavities. They express CD5, high IgM, and low IgD, show restricted BCR diversity (often lacking TdT-mediated N-nucleotide additions), self-renew in peripheral tissues, and produce "natural antibodies" (mainly IgM specific for common bacterial cell wall components like phosphorylcholine, without T-cell help).

#### Effector Functions & Secretory Profile
*   **Primary Effector Mechanisms:**
    - **Antibody Production:** B cells differentiate into antibody-secreting plasma cells.
        - **Germinal Center (GC) Reaction:** Activated B cells migrate into primary follicles, forming germinal centers. In the GC dark zone, B cells (centroblasts) undergo rapid proliferation and somatic hypermutation (SHM) of their Ig V-region genes, driven by the enzyme AID (Activation-induced cytidine deaminase). Centroblasts then transition to the light zone as centrocytes, where they capture antigen displayed on Follicular Dendritic Cells (FDCs). Centrocytes with mutated, high-affinity BCRs bind antigen, endocytose it, and present peptides to Tfh cells. High-affinity centrocytes receive survival signals from Tfh cells (via CD40-CD40L and IL-21) and survive, while low-affinity or self-reactive mutated centrocytes undergo apoptosis (affinity maturation).
        - **Heavy-Chain Class (Isotype) Switching:** Under the influence of Tfh CD40L and specific cytokines, AID deaminates cytosines to uracils in single-stranded DNA of target switch (S) regions upstream of constant (CH) genes. This creates double-stranded DNA breaks, leading to loop-out deletion of intervening CH genes and recombination of the VDJ exon to a downstream CH gene (isotype switching from IgM to IgG, IgA, or IgE).
        - **Plasmablast & Plasma Cell Differentiation:** GC B cells can commit to plasma cells (driven by BLIMP-1, IRF4, XBP-1). They shift from producing membrane-bound Ig (using TM and CY exons) to secreted Ig (using the secretory tail piece TP exon) via alternative RNA polyadenylation and splicing.
    - **Antigen Presentation (APC Function):** B cells endocytose BCR-bound protein antigens, process them in late endosomes/lysosomes, and present peptides on MHC Class II molecules to CD4+ T helper cells, receiving T-cell help in return.
*   **Key Cytokines Secreted:**
    - While B cells are primarily antibody producers, some activated subsets can secrete cytokines:
        - **IL-10:** Regulatory B cells (Bregs) produce IL-10 to suppress inflammatory T-cell responses.
        - **IL-6 and TNF-alpha:** Secreted by activated B cells to promote local lymphoid tissue organization and amplify inflammatory cascades.
*   **Target Cells & Pathogens:**
    - **Extracellular Bacteria (e.g., Streptococcus pneumoniae, Haemophilus influenzae, Neisseria meningitidis):** Neutralized and opsonized by B-cell derived antibodies (IgG, IgM) to facilitate phagocytosis or classical complement pathway lysis.
    - **Helminthic Parasites:** Targeted by IgE antibodies that coat parasites and activate eosinophils via FcεRI-mediated ADCC.
    - **Viruses:** Blocked from entering host cells by neutralizing antibodies (IgA at mucosal surfaces, IgG in circulation).
*   **Memory Generation & Lifespan:**
    - **Memory B Cells:** Generated during the germinal center reaction. They do not secrete antibodies but express high-affinity, class-switched membrane Ig and CD27. They circulate for decades, recirculating between lymph nodes, spleen, and blood, and respond rapidly to secondary antigen exposure by dividing and differentiating into high-affinity antibody-secreting cells.
    - **Long-Lived Plasma Cells (LLPCs):** GC-derived plasma cells migrate to specialized niches in the adult bone marrow (or mucosal lamina propria). They do not divide but persist for years, continuously secreting high-affinity antibodies into the blood, supported by bone marrow stromal cell survival factors (BAFF, APRIL, CXCL12 interacting with BCMA and CXCR4).

#### Pathologic Relevance
*   **Role in Hypersensitivity or Autoimmunity:**
    - **Type I Hypersensitivity (Allergic Disorders):** Inappropriate B-cell class switching to IgE in response to harmless environmental allergens, driven by allergen-specific Th2 cells secreting IL-4 and IL-13. IgE binds to FcεRI on mast cells and basophils, causing immediate degranulation upon allergen re-encounter.
    - **Type II Hypersensitivity:** Production of autoantibodies specific for fixed cell or tissue antigens, causing damage via opsonization/phagocytosis, complement activation, or functional interference (e.g., autoimmune hemolytic anemia, autoimmune thrombocytopenic purpura, myasthenia gravis, Graves' disease).
    - **Type III Hypersensitivity (Immune Complex-Mediated Diseases):** Excessive production of antibodies that bind soluble self or microbial antigens in the circulation. The resulting antigen-antibody immune complexes deposit in blood vessel walls, basement membranes, and capillaries (e.g., glomeruli, synovium), activating complement and recruiting neutrophils to cause systemic vasculitis, nephritis, and arthritis.
    - **Systemic Lupus Erythematosus (SLE):** The prototypic Type III hypersensitivity disease. Defective B-cell central or peripheral tolerance allows the persistence of autoreactive B-cell clones that produce high titers of antinuclear antibodies (ANAs), particularly anti-double-stranded DNA (anti-dsDNA) antibodies. These antibodies form circulating immune complexes that deposit in renal glomeruli (lupus nephritis), joint synovium (arthritis), and small blood vessels (vasculitis).
    - **Rheumatoid Arthritis (RA):** B cells produce rheumatoid factor (an autoantibody against the Fc portion of IgG) and anti-citrullinated protein antibodies (ACPAs), forming immune complexes that drive chronic joint inflammation.
*   **Microbial Evasion of this Cell Type:**
    - **Antigenic Variation:** Rapid mutation of surface epitopes (e.g., Influenza hemagglutinin, HIV gp120) to escape recognition by existing neutralizing antibodies.
    - **Polyclonal B-Cell Activation & Epstein-Barr Virus (EBV):** EBV infects B cells by binding CD21. It expresses the latent viral protein LMP1 (latent membrane protein 1), which mimics CD40 signaling by binding to tumor necrosis factor receptor-associated factors (TRAFs) in B cells, driving polyclonal B-cell proliferation and immortalization without T-cell help, which can progress to B-cell lymphomas.
    - **Encapsulated Bacteria (Evasion of Phagocytosis):** Pathogens like S. pneumoniae produce thick polysaccharide capsules that hide cell wall proteins, resisting phagocytosis unless targeted by specific capsular polysaccharide-specific B-cell antibodies.
    - **Antigenic Mimicry:** Pathogens express epitopes structurally homologous to self-antigens, driving cross-reactive antibody production that causes post-infectious autoimmune damage (e.g., Streptococcus pyogenes cell wall antigens cross-reacting with myocardial proteins, causing rheumatic fever).

#### Trivia & Edge Cases
*   **Buzzwords & Descriptors:**
    - **"Tonic Signaling":** Low-level, antigen-independent BCR signaling driven by assembly of the receptor complex alone, activating the PI3K-Akt pathway to promote the survival of developing and naive B cells.
    - **"Receptor Editing":** The somatic "second chance" mechanism where self-reactive immature B cells reactivate RAG genes to rearrange a new light chain and escape negative selection.
    - **"Antibody Feedback":** Downregulation of humoral responses when circulating IgG antibody levels are high, mediated by antibody-antigen complexes co-ligating the BCR with the inhibitory FcγRIIB receptor to recruit SHIP.
    - **"Conjugate Vaccines":** Vaccines where bacterial capsular polysaccharides are chemically linked to protein carriers (e.g., tetanus toxoid). Polysaccharide-specific B cells endocytose the conjugate, present the carrier peptides on MHC Class II, recruit Tfh helper T cells, and receive CD40-CD40L and cytokine signals, converting a T-independent polysaccharide response into a high-affinity T-dependent response with memory.
*   **Key Experimental Markers:**
    - **CD19, CD20:** Pan-B-cell surface markers.
    - **CD79a, CD79b (Igα, Igβ):** Invariant signaling heterodimer.
    - **CD21 (CR2):** High on mature B cells, complement receptor.
    - **CD10, CD43:** Expressed on early pro-B/pre-B progenitors.
    - **CD27:** Human memory B-cell marker.
    - **CD138 (Syndecan-1):** Plasma cell marker.
*   **Exceptions to the Rule:**
    - **Human vs. Mouse IL-7 Dependency:** While IL-7 is absolutely required for both B and T cell development in mice (IL-7 or IL-7Rα knockouts completely lack T and B cells), in humans, mutations in IL-7Rα or the common gamma chain (γc) cause T-SCID (complete absence of T cells) but mature B cells develop in normal or even elevated numbers. This indicates that IL-7 is not strictly required for human B-cell maturation in the bone marrow.
    - **B-1 Cell Development:** Conventional B-2 cells arise postnatally and are continually replenished from bone marrow stem cells. In contrast, B-1 cells develop primarily from fetal liver progenitors during embryonic life, reside in pleural and peritoneal cavities, self-renew in peripheral tissues, and produce natural antibodies independent of bone marrow lymphopoiesis in adult life.