---
aliases:
  - T lymphocytes
  - T cells
  - Thymocytes
defining_cd_markers:
  - CD3
  - CD4
  - CD8
  - CD2
  - CD5
  - CD28
  - CD45
  - CD25
  - CD127
cell_lineage:
  - Lymphoid lineage
primary_location:
  - Secondary lymphoid organs
  - Blood
  - Lymph
  - Thymus (maturation)
key_transcription_factors:
  - NOTCH1
  - GATA3
  - T-bet
  - RORgammat
  - FoxP3
  - Bcl-6
tissue_homing_receptors:
  - CCR7
  - CD62L (L-selectin)
  - LFA-1 (CD11aCD18)
  - VLA-4 (CD49dCD29)
  - CXCR3
  - CCR5
  - CCR6
date: 2026-09-06
draft: false
---

### T Cell

#### Origin & Maturation
*   **Lineage & Precursors:** Committed lymphoid progenitors that arise from pluripotent hematopoietic stem cells (HSCs) in the fetal liver and adult bone marrow migrate through the blood to seed the thymus. Commitment to the T-cell lineage is driven by NOTCH1 signaling (Notch receptors on lymphoid progenitors interact with Notch ligands on thymic stromal cells) and the transcription factor GATA3.
*   **Site of Development & Maturation:** The thymus is the primary generative lymphoid organ where T cells mature. Progenitors from bone marrow enter the thymus at the corticomedullary junction and migrate as Double-Negative (DN) thymocytes (lacking CD4 and CD8 expression) through distinct developmental stages (DN1: CD44+ CD25-; DN2: CD44+ CD25+; DN3: CD44- CD25+; DN4: CD44- CD25-). Rearrangement of the TCR beta chain locus occurs at the DN3 stage. If productive, the rearranged beta chain pairs with the invariant surrogate pre-T alpha (pTα) chain and CD3 signaling proteins to form the pre-TCR complex (first checkpoint). Successful pre-TCR signaling drives rapid proliferation, halts further beta-chain rearrangement (allelic exclusion), and promotes transition to the Double-Positive (DP) stage (expressing both CD4 and CD8). At the DP stage, the TCR alpha chain rearranges to form a complete alpha-beta TCR complex, ready for selection.
*   **Key Transcription Factors for Differentiation:**
    - **GATA3** and **NOTCH1** for initial lineage commitment.
    - **Kruppel-like factor 2 (KLF2)** for maintaining the naive T-cell phenotype and promoting S1PR1 expression.
    - **T-bet** (encoded by TBX21) for Th1 subset differentiation.
    - **GATA-3** for Th2 subset differentiation.
    - **RORgammat** (encoded by RORC) and **STAT3** for Th17 subset differentiation.
    - **FoxP3** for Regulatory T cell (Treg) differentiation.
    - **Bcl-6** for T follicular helper (Tfh) cell differentiation.
    - **TOX** for the CD8+ T cell exhaustion program.
    - **TCF1** (TCF7) for maintaining stem-like properties in progenitor-exhausted CD8+ T cells and memory precursor CD8+ T cells.
*   **Selection & Tolerance Mechanisms:**
    - **Positive Selection (Cortex):** DP thymocytes are tested for their ability to recognize self-peptide-MHC complexes presented by cortical thymic epithelial cells (cTECs). Those with low-to-moderate avidity recognition survive and differentiate into Single-Positive (SP) cells. Cells recognizing MHC Class I downregulate CD4 and become CD8+ SP cells. Cells recognizing MHC Class II downregulate CD8 and become CD4+ SP cells. Cells failing to recognize self-MHC receive no survival signals and die by apoptosis (death by neglect, accounting for >90% of DP thymocytes).
    - **Negative Selection (Medulla):** SP thymocytes are tested for autoreactivity. Those whose TCRs bind self-peptide-MHC complexes with high avidity presented by medullary thymic epithelial cells (mTECs) or thymic dendritic cells are deleted via apoptosis (clonal deletion mediated by the pro-apoptotic BH3-only protein BIM).
    - **Central Tolerance and AIRE:** mTECs express the Autoimmune Regulator (AIRE) protein, which drives ectopic transcription of peripheral tissue-restricted antigens (TRAs) in the thymus. A subset of mTECs differentiate into "thymomimetic cells" that transcriptionally resemble various peripheral tissue lineages (such as tuft-like, muscle-like, or keratinocyte-like cells; the latter degenerate to form Hassall's corpuscles). This expression allows deletion of self-reactive T cells or their diversion into the immunosuppressive Regulatory T cell (Treg) lineage (expressing FoxP3).
    - **Peripheral Tolerance:** Autoreactive T cells that escape central tolerance are regulated in the periphery by:
      - **Anergy:** Functional unresponsiveness induced when T cells recognize self-antigen on resting APCs in the absence of costimulation (B7-CD28 binding), characterized by down-regulation of TCR signaling or up-regulation of the E3 ubiquitin ligase CBL-b, which targets CD3 and ZAP70 for degradation.
      - **Suppression:** Active suppression of self-reactive T cells by Tregs via cell-contact mechanisms (e.g., CTLA-4 removing B7-1/B7-2 from APCs by trans-endocytosis) or secretion of inhibitory cytokines (IL-10, TGF-beta).
      - **Deletion:** High-avidity self-antigen exposure triggers apoptosis via the mitochondrial pathway (mediated by BIM) or the death receptor pathway (FAS-FASL interactions).
*   **Circulation & Extravasation Dynamics:**
    - **Naive T-cell Recirculation:** Continuous migration from the blood through high endothelial venules (HEVs) of secondary lymphoid organs (lymph nodes, mucosal tissues), back into the lymphatics, and into the blood. Naive T cells express high levels of **L-selectin (CD62L)**, which binds to **peripheral node addressin (PNAd)** on HEVs, mediating initial rolling. The chemokine receptor **CCR7** on naive T cells binds **CCL19** and **CCL21** displayed on HEVs, activating the integrin **LFA-1 (CD11aCD18)** to a high-affinity state. LFA-1 binds firmly to **ICAM-1** on HEVs, allowing transmigration into the paracortex.
    - **Lymph Node Egress:** Mediated by a gradient of the lipid chemoattractant **sphingosine 1-phosphate (S1P)**. Blood and lymph contain high S1P levels, while lymphoid tissues contain low levels. Naive T cells express **S1PR1 (CD363)**, which directs them toward the lymph-filled medullary sinus and efferent lymphatics. Activation by antigen suppresses S1PR1 expression transiently (via CD69 binding to S1PR1), retaining the T cell in the node for proliferation and differentiation. Effector T cells lose CD69 expression, re-express S1PR1, and exit the node.
    - **Effector T-cell Homing to Sites of Inflammation:** Effector T cells downregulate CD62L and CCR7, but upregulate ligands for **E-selectin** and **P-selectin** (e.g., PSGL-1/CD162) and integrins **VLA-4 (CD49dCD29)** and **LFA-1**. Local inflammatory cytokines (TNF, IL-1) upregulate VCAM-1 (ligand for VLA-4) and ICAM-1 (ligand for LFA-1) on endothelial cells. Effector T cells also express chemokine receptors matching inflammatory chemokines (e.g., CXCR3 and CCR5 on Th1 cells, binding CXCL9/CXCL10; CCR3/CCR4/CCR8 on Th2 cells; CCR6 on Th17 cells, binding CCL20). These molecules drive effector cell recruitment to inflamed tissues.
    - **Specialized Gut Homing:** Driven by the integrin **alpha4beta7** binding to **MAdCAM-1** and the chemokine receptor **CCR9** binding to **CCL25** on lamina propria venules.

#### Receptors & Surface Markers
*   **Defining CD Markers:**
    - **CD3:** Multi-subunit signaling complex associated with TCR, composed of CD3γε, CD3δε heterodimers, and a CD3ζζ homodimer. It contains Immunoreceptor Tyrosine-based Activation Motifs (ITAMs) in cytoplasmic tails (one per CD3γ, CD3δ, CD3ε; three per ζ chain).
    - **CD4:** Monomer containing four extracellular Ig-like domains, expressed on helper MHC Class II-restricted T cells. It binds to the nonpolymorphic beta2 domain of MHC Class II molecules and associates intracellularly with the tyrosine kinase **LCK**.
    - **CD8:** Heterodimer of disulfide-linked alpha and beta chains (or homodimer of alpha chains), expressed on cytotoxic MHC Class I-restricted T cells. It binds to the nonpolymorphic alpha3 domain of MHC Class I molecules and associates intracellularly with **LCK**.
    - **CD2 (LFA-2):** Adhesion and signaling molecule that binds to CD58 (LFA-3), facilitating CTL/NK-mediated lysis and T-cell activation.
    - **CD5:** Scavenger receptor family member that modulates TCR signaling.
    - **CD28:** Primary costimulatory receptor that binds to **B7-1 (CD80)** and **B7-2 (CD86)** on APCs.
    - **CD45 (LCA):** Protein tyrosine phosphatase that dephosphorylates LCK to regulate its activation. Naive cells express the **CD45RA** isoform; activated/memory cells express the **CD45RO** isoform.
    - **CD25:** IL-2 receptor alpha chain, expressed on activated T cells and constitutively on Tregs, forming the high-affinity trimeric IL-2Rαβγc complex.
    - **CD127 (IL-7Rα):** Receptor alpha chain for IL-7, expressed on naive and memory T cells to promote survival, downregulated on effector T cells.
*   **Antigen Recognition Receptors:**
    - **alpha-beta TCR (αβ TCR):** Heterodimer of transmembrane alpha and beta chains, covalently linked by a disulfide bond, expressed on MHC-restricted T cells. Each chain has one variable (V) domain and one constant (C) domain. The Vα and Vβ domains form the antigen-binding site, containing three hypervariable loops (complementarity-determining regions, CDR1, CDR2, CDR3) that recognize peptide-MHC complexes.
    - **gamma-delta TCR (γδ TCR):** Heterodimer of gamma and delta chains, expressed on a smaller population of T cells (mostly in mucosa and epithelia) that recognize nonpeptide antigens without MHC restriction.
*   **Co-stimulatory & Inhibitory Receptors:**
    - **CD28 (Costimulatory):** Binds CD80 (B7-1) and CD86 (B7-2) on APCs, providing crucial Signal 2 that promotes survival (via Bcl-xL), proliferation (via IL-2 secretion), and metabolic reprogramming.
    - **ICOS (CD278) (Costimulatory):** Binds ICOS-L (CD275) on B cells and APCs, essential for T follicular helper (Tfh) cell differentiation and germinal center reactions.
    - **CTLA-4 (CD152) (Inhibitory):** Binds CD80/CD86 with higher affinity than CD28, acting as a competitive antagonist. It also mediates trans-endocytosis of B7-1/B7-2 molecules, removing them from the APC membrane to prevent CD28 engagement. Expressed on activated T cells and constitutively on Tregs.
    - **PD-1 (CD279) (Inhibitory):** Programmed cell death protein 1, binds to **PD-L1 (CD274)** and **PD-L2 (CD273)**. Its cytoplasmic tail contains an ITIM and an Immunoreceptor Tyrosine-based Switch Motif (ITSM), which recruit the tyrosine phosphatase **SHP2** to dephosphorylate TCR and CD28 proximal signaling intermediates. High expression is a hallmark of T-cell exhaustion.
*   **Cytokine & Chemokine Receptors:**
    - **IL-2R:** Formed by combinations of IL-2Rα (CD25), IL-2Rβ (CD122), and the common gamma chain (γc, CD132). Naive cells express the intermediate-affinity dimeric βγc complex. Activated cells and Tregs express the high-affinity trimeric αβγc complex.
    - **IL-7R:** Dimer of IL-7Rα (CD127) and γc (CD132), essential for naive and memory T-cell survival and S1PR1 expression.
    - **CCR7:** Chemokine receptor for CCL19 and CCL21, directing naive T-cell homing and entry into lymph nodes.
    - **CXCR5:** Chemokine receptor for CXCL13, directing Tfh cells into B-cell follicles.
    - **CXCR3 / CCR5:** Chemokine receptors on Th1 cells, directing them to inflamed tissues.
    - **CCR3 / CCR4 / CCR8:** Chemokine receptors on Th2 cells, directing them to mucosal allergy sites.
    - **CCR6:** Chemokine receptor on Th17 cells, directing them to fungal/bacterial infection sites.
*   **Tissue Homing & Adhesion Molecules (Integrins/Selectins):**
    - **CD62L (L-selectin):** Selectin on naive T cells that binds PNAd on HEVs for rolling.
    - **CD162 (PSGL-1):** Ligand for E-selectin (CD62E) and P-selectin (CD62P) on inflamed endothelium.
    - **LFA-1 (CD11aCD18):** Integrin on naive and activated T cells that binds ICAM-1 (CD54) and ICAM-2 (CD102).
    - **VLA-4 (CD49dCD29):** Integrin on activated/effector T cells that binds VCAM-1 (CD106) on inflamed endothelium.
    - **alpha4beta7:** Integrin on gut-homing T cells that binds MAdCAM-1.
    - **alphaEbeta7 (CD103):** Integrin expressed on intraepithelial lymphocytes (IELs) that binds to E-cadherin on epithelial cells, retaining T cells within epithelial barriers.

#### Activation & Differentiation
*   **Primary Activation Signals (Signal 1, 2, 3):**
    - **Signal 1 (Antigen Recognition):** TCR recognizes a specific peptide-MHC complex presented by an APC. CD4 or CD8 coreceptors bind concurrently to nonpolymorphic regions of the MHC molecule, bringing the associated kinase LCK close to the CD3 and ζ signaling chains.
    - **Signal 2 (Costimulation):** CD28 on T cells binds to B7-1 (CD80) or B7-2 (CD86) on professional APCs. This signal synergizes with Signal 1, promoting survival (Bcl-xL), proliferation (secretion of IL-2), and metabolic activation. Absence of Signal 2 results in clonal anergy or apoptosis.
    - **Signal 3 (Cytokines / Polarization):** Cytokines produced by APCs or the local environment drive differentiation into distinct CD4+ helper subsets:
      - **IL-12** and **IFN-γ** drive **Th1** differentiation.
      - **IL-4** drives **Th2** differentiation.
      - **IL-6, IL-1, IL-23,** and **TGF-β** drive **Th17** differentiation.
      - **TGF-β** and **IL-2** drive inducible **Treg** differentiation.
      - **IL-6** and **IL-21** drive **Tfh** differentiation.
*   **Signal Transduction Cascades:**
    - **TCR Proximal Signaling:** Antigen recognition clusters TCRs and coreceptors, bringing CD4/CD8-associated **LCK** in proximity to CD3 and ζ cytoplasmic tails. LCK phosphorylates the tyrosine residues within the ITAMs of CD3 γ, δ, ε, and ζ chains. Tyrosine-phosphorylated ζ chain ITAMs act as docking sites for **ZAP70**, which binds via its tandem SH2 domains. ZAP70 is subsequently phosphorylated and activated by adjacent LCK.
    - **Signalosome Assembly:** Active ZAP70 phosphorylates the scaffold adaptors **LAT** and **SLP76**. Tyrosine-phosphorylated LAT recruits GADS, GRB2, and the enzyme **PLCγ1** (phospholipase C γ1) to form the TCR signalosome.
    - **Calcium - NFAT Pathway:** PLCγ1 is activated by **ITK** (which is recruited to the membrane by PIP3 generated by PI3K). Active PLCγ1 hydrolyzes membrane PIP2 to yield soluble **IP3** (inositol 1,4,5-trisphosphate) and membrane-bound **DAG** (diacylglycerol). IP3 binds to receptors on the endoplasmic reticulum (ER), depleting ER calcium stores. This depletion is sensed by **STIM1**, which oligomerizes and induces the opening of the **CRAC (ORAI1)** channels on the plasma membrane, driving a massive influx of extracellular calcium into the cytosol. Elevated calcium binds to calmodulin, activating the phosphatase **calcineurin**. Calcineurin dephosphorylates the transcription factor **NFAT**, exposing its nuclear localization signal. NFAT translocates to the nucleus to regulate gene transcription, including the IL-2 gene.
    - **PKCθ - NF-κB Pathway:** Membrane-bound DAG recruits **PKCθ** (protein kinase C θ) and RAS-GRP. PKCθ activates the CARMA1-BCL10-MALT1 (CBM) complex, which phosphorylates and activates the IκB kinase (IKK) complex. IKK phosphorylates IκB, targeting it for ubiquitin-mediated degradation and releasing **NF-κB** to translocate into the nucleus.
    - **Ras - MAPK Pathway:** SOS (recruited to the membrane by the LAT-GRB2 complex) and RAS-GRP act as GTP/GDP exchange factors to activate **RAS**. Active RAS-GTP initiates the Mitogen-Activated Protein (MAP) kinase cascade: **RAF** -> **MEK1** -> **ERK1/2**. Active ERK translocates to the nucleus and phosphorylates ELK, promoting transcription of **FOS**. A parallel RAC-dependent pathway activates **JNK**, which phosphorylates **JUN**. FOS and JUN heterodimerize to form the **AP-1** transcription factor.
    - **PI3K - Akt Pathway:** TCR and CD28 signaling recruit and activate **PI3-kinase**, which phosphorylates membrane PIP2 to **PIP3**. PIP3 recruits PH-domain containing proteins, including PDK1 and the serine/threonine kinase **Akt**. PDK1 phosphorylates and activates Akt, which transmits powerful anti-apoptotic survival signals and drives metabolic reprogramming toward aerobic glycolysis.
*   **Polarization & Subsets:**
    - **Th1 Subset:** Induced by IL-12 and IFN-γ. Regulated by the master transcription factor **T-bet** (along with STAT4 and STAT1). Produces **IFN-γ**. Promotes classical macrophage activation (M1) and delayed-type hypersensitivity (DTH) reactions. Coordinates defense against intracellular pathogens (mycobacteria, viruses, protozoa).
    - **Th2 Subset:** Induced by IL-4. Regulated by the master transcription factor **GATA-3** (along with STAT6). Produces **IL-4, IL-5, and IL-13**. Promotes IgE class switching (IL-4), eosinophil activation and recruitment (IL-5), alternative macrophage activation (M2) for tissue repair (IL-4/IL-13), and intestinal peristalsis and mucus secretion (IL-4/IL-13). Coordinates defense against helminthic parasites.
    - **Th17 Subset:** Induced by IL-6, IL-1, IL-23, and TGF-β. Regulated by the master transcription factor **RORgammat** (along with STAT3). Produces **IL-17 (IL-17A, IL-17F) and IL-22**. Promotes neutrophil recruitment and activation (via chemokines induced by IL-17) and antimicrobial peptide production (defensins) in epithelia (via IL-17/IL-22). Coordinates defense against extracellular bacteria and fungi.
    - **T follicular helper (Tfh) Subset:** Induced by IL-6 and IL-21. Regulated by the master transcription factor **Bcl-6** (along with STAT3). Expresses **CXCR5 and ICOS**. Produces **IL-21** (and IL-4). Migrates to B-cell follicles to coordinate B-cell activation, heavy-chain class switching, affinity maturation, and memory B-cell/long-lived plasma cell generation in germinal centers.
    - **Regulatory T (Treg) Subset:** Generated in the thymus (tTregs) or induced in the periphery (pTregs) by TGF-β and IL-2. Regulated by the master transcription factor **FoxP3** (along with STAT5). Expresses high levels of CD25 and CTLA-4. Produces **IL-10 and TGF-β**. Suppresses the activation and function of self-reactive and potentially pathogenic lymphocytes.

#### Effector Functions & Secretory Profile
*   **Primary Effector Mechanisms:**
    - **CD4+ Helper Effector Functions:** Helper T cells act predominantly by secreting cytokines that activate other cell types or by expressing surface ligands (such as CD40L/CD154).
      - **Macrophage Activation:** Th1 cells express CD40L and secrete IFN-γ. CD40L binds CD40 on macrophages, and IFN-γ binds the IFN-γ receptor, cooperatively driving **classical macrophage activation (M1)**. Activated macrophages upregulate reactive oxygen species (ROS), nitric oxide (NO), and lysosomal enzymes, dramatically enhancing their ability to kill phagocytosed microbes.
      - **B Cell Help:** Tfh cells express CD40L and ICOS and secrete IL-21. CD40L binds CD40 on B cells, and IL-21 acts on B cells to stimulate proliferation, somatic hypermutation, heavy-chain class switching, and germinal center reactions.
    - **CD8+ CTL Effector Functions:** CD8+ CTLs kill infected or tumor cells directly. Upon antigen recognition on the target cell, the CTL cytoskeleton reorganizes, aligning its microtubule organizing center and cytoplasmic granules toward the point of contact (the **immunologic synapse**). The synapse consists of a central SMAC (containing TCR, CD3, CD8, LCK, and PKCθ) and a peripheral SMAC (containing the integrin LFA-1 bound to ICAM-1, sealing the synapse). Granules undergo exocytosis into the synaptic space, releasing:
      - **Perforin:** A membrane-disrupting protein homologous to C9 that polymerizes to form pores in the target cell membrane or induces endocytosis of granule proteins into the target cell, subsequently facilitating the release of granzymes from endosomes into the target cell cytosol.
      - **Granzymes:** Serine proteases (granzymes A, B, H, K, M). Granzyme B cleaves substrates after aspartate residues, directly cleaving and activating executioner caspases (caspase-3) and the BH3-only protein BID to trigger apoptotic cell death. Granzyme K promotes local inflammation.
      - **Granulysin:** A protein that disrupts lipid-poor microbial membranes, facilitating the delivery of granzymes into intracellular bacteria and fungi to kill them.
      - **Serglycin:** A sulfated proteoglycan that stabilizes perforin and granzymes in their inactive state within granules.
      - **FAS - FASL Pathway:** Activated CTLs express **FAS ligand (FAS-L)**, which binds to **FAS (CD95)** on target cells. This ligation recruits initiator caspase-8, activating executioner caspases and inducing apoptosis independent of granule exocytosis.
*   **Key Cytokines Secreted:**
    - **IFN-γ:** Secreted by Th1 and CD8+ cells. Activates macrophages (M1), upregulates MHC Class I and II and TAP expression on APCs, and promotes Th1 differentiation while inhibiting Th2 and Th17 pathways.
    - **IL-2:** Secreted by newly activated naive T cells. Promotes clonal expansion and survival of T cells, essential for Treg maintenance.
    - **IL-4:** Secreted by Th2 and Tfh cells. Induces IgE class switching in B cells, drives Th2 differentiation, and promotes alternative macrophage activation (M2).
    - **IL-5:** Secreted by Th2 cells. Activates and recruits eosinophils.
    - **IL-13:** Secreted by Th2 cells. Stimulates mucus production and gut peristalsis, coordinates M2 macrophage activation.
    - **IL-17 (IL-17A, IL-17F):** Secreted by Th17 cells. Induces tissue cells to secrete chemokines (CXCL1, CXCL8) that recruit and activate neutrophils.
    - **IL-22:** Secreted by Th17 cells. Promotes epithelial barrier integrity and antimicrobial peptide secretion.
    - **IL-21:** Secreted by Tfh and Th17 cells. Amplifies Th17 and Tfh subsets, drives germinal center B-cell reactions.
    - **IL-10 / TGF-β:** Secreted by Tregs. Suppresses inflammation and T-cell activation.
*   **Target Cells & Pathogens:**
    - **Intracellular Pathogens (Mycobacteria, Listeria, viruses, Leishmania):** Targeted by Th1 cells (activating macrophages) and CD8+ CTLs (killing infected cells).
    - **Extracellular Bacteria & Fungi (Candida):** Targeted by Th17 cells (recruiting neutrophils to clear pathogens and protect epithelia).
    - **Helminthic Parasites:** Targeted by Th2 cells (eosinophil-mediated killing, IgE neutralization, mucus-mediated clearance).
    - **Tumor Cells:** Targeted by CD8+ CTLs (via perforin/granzymes and FAS-FASL).
*   **Memory Generation & Lifespan:** Following the clearance of antigen, the T-cell response undergoes contraction (homeostasis), wherein 90%–95% of antigen-specific effector cells die by apoptosis (due to deprivation of antigen and survival cytokines, triggering BIM-mediated mitochondrial pathway). A small pool (5%–10%) of antigen-specific cells survive as **Memory T cells**, which persist for decades. Memory cells express high levels of the anti-apoptotic protein **Bcl-2** and the IL-7 receptor CD127, allowing low-level homeostatic proliferation driven by **IL-7** and **IL-15**. Memory T cells are heterogeneous:
    - **Stem cell-like memory T cells (TSCM):** Express CD45RA, CD62L, CCR7, CD95, and TCF1. They reside in secondary lymphoid organs, possess high self-renewal capacity, and can differentiate into all other memory and effector populations.
    - **Central Memory T cells (TCM):** Express CD62L and CCR7. They reside in and recirculate through secondary lymphoid organs, proliferatively expanding rapidly upon re-exposure to antigen.
    - **Effector Memory T cells (TEM):** Lack CD62L and CCR7. They home to and reside in peripheral tissues, producing cytokines immediately upon antigen re-encounter.
    - **Tissue-Resident Memory T cells (TRM):** Reside permanently within epithelial barriers (skin, gut, lungs) and mucosal tissues, expressing CD103 (binds E-cadherin) and CD69 to prevent egress.

#### Pathologic Relevance
*   **Role in Hypersensitivity or Autoimmunity:**
    - **Type I Hypersensitivity (Allergy/Asthma):** Defective regulation leading to inappropriate Th2 activation against harmless environmental antigens. Secretion of IL-4 drives IgE class switching in B cells, binding to FcεRI on mast cells and basophils. Re-exposure cross-links IgE, causing immediate degranulation (histamine, leukotrienes) and late-phase eosinophilic inflammation (driven by IL-5).
    - **Type IV Hypersensitivity (Delayed-Type Hypersensitivity/DTH):** Tissue injury mediated by T lymphocytes.
      - **Cytokine-Mediated DTH:** CD4+ Th1 and Th17 cells react to tissue antigens (self or persistent foreign), secreting IFN-γ and IL-17, recruiting and classically activating macrophages and neutrophils that release ROS, NO, and lysosomal enzymes, causing tissue destruction. Chronic Th1 activation against persistent pathogens (such as M. tuberculosis) yields **granulomatous inflammation** (formation of granulomas containing epithelioid macrophages, multinucleate giant cells, and T cells). Delayed-type hypersensitivity is exemplified by the tuberculin skin test.
      - **T-cell-mediated Cytotoxicity:** CD8+ CTLs directly destroy target tissue cells (e.g., islet β cells in type 1 diabetes, or myelin-producing cells in multiple sclerosis).
    - **Autoimmune Diseases:**
      - **Multiple Sclerosis (MS):** Autoreactive Th1 and Th17 cells react to myelin antigens (e.g., myelin basic protein), recruiting macrophages that destroy the myelin sheath in the central nervous system.
      - **Rheumatoid Arthritis (RA):** Autoreactive Th1 and Th17 cells react to joint antigens (e.g., citrullinated self-proteins), producing cytokines (IFN-γ, IL-17) that recruit macrophages and neutrophils, activating osteoclasts to destroy cartilage and bone.
      - **Type 1 Diabetes (T1D):** Autoreactive CD4+ Th1 cells and CD8+ CTLs destroy insulin-producing β cells in the pancreatic islets, a lesion known as **insulitis**.
      - **Celiac Disease:** CD4+ T cells in the lamina propria recognize deamidated gliadin peptides (produced by TG2 and presented by HLA-DQ2/DQ8), producing IFN-γ and damaging the intestinal epithelium.
      - **Psoriasis:** Th17 cells producing IL-17/IL-22 drive chronic inflammation and hyperproliferation of keratinocytes.
*   **Microbial Evasion of this Cell Type:**
    - **Antigenic Variation:** Rapid mutation of V regions or hypervariable loops of microbial proteins (e.g., HIV, Influenza) to escape TCR recognition.
    - **Inhibition of MHC Class I Presentation:**
      - Blocking TAP transport of cytosolic peptides into the ER (e.g., Herpes Simplex Virus ICP47 protein).
      - Retaining MHC Class I molecules in the ER (e.g., Human Cytomegalovirus US3).
      - Targeting MHC Class I for lysosomal degradation (e.g., HIV Nef).
    - **Inhibition of MHC Class II Presentation:** Inhibiting CIITA-dependent transcription or MHC-II loading in endosomes.
    - **Inactivation of Phagocytes:** Escaping the phagolysosome into the cytoplasm (e.g., Listeria monocytogenes using hemolysin) to avoid classical macrophage killing, or producing catalase/superoxide dismutase to neutralize ROS.
    - **Production of Immunosuppressive Cytokines:** Epstein-Barr Virus (EBV) encodes a viral homolog of **IL-10** that inhibits macrophage activation and Th1 differentiation.
    - **Superantigens:** Microbial toxins (e.g., Staphylococcal enterotoxins, Toxic Shock Syndrome Toxin-1/TSST-1) that bind simultaneously to the nonpolymorphic Vβ domain of the TCR and the MHC Class II molecule on APCs outside the normal peptide-binding cleft. This cross-links and polyclonally activates up to 20% of all T cells, driving a massive, systemic release of cytokines (IFN-γ, TNF, IL-1, IL-2) that results in a sepsis-like systemic inflammatory response syndrome.
    - **T-cell Exhaustion:** Persistent antigen exposure during chronic viral infections (e.g., HIV, HCV) or in the tumor microenvironment drives high, stable expression of inhibitory receptors (PD-1, CTLA-4, LAG-3, TIM-3), mediated by the transcription factor **TOX** and chromatin remodeling. This results in progressive loss of effector functions (cytokine production, proliferation, target killing), preventing microbial clearance.

#### Trivia & Edge Cases
*   **Buzzwords & Descriptors:**
    - **"Horror Autotoxicus":** Coined by Paul Ehrlich to describe the body's fear of self-toxicity (autoimmunity).
    - **"Tonic Signaling":** Low-level, antigen-independent TCR signaling driven by self-peptide-MHC interactions, essential for naive T-cell survival and homeostatic maintenance.
    - **"Lethal Hit":** The rapid, unidirectional delivery of perforin and granzymes from a CTL's granules into the synaptic space of a target cell, committing it to apoptosis.
    - **"Death by Neglect":** The apoptotic death of DP thymocytes that fail to recognize self-peptide-MHC complexes during positive selection in the cortex.
    - **"Mendelian Susceptibility to Mycobacterial Disease (MSMD)":** Inborn errors in IFN-γ, IFN-γR, IL-12, IL-12R, or STAT1 signaling, rendering patients highly susceptible to weakly virulent environmental mycobacteria and Salmonella.
    - **"Insulitis":** The characteristic lymphocytic infiltration (CD4+ and CD8+ T cells) and destruction of pancreatic islet β cells seen in early-stage type 1 diabetes.
*   **Key Experimental Markers:**
    - **CD3:** Pan-T-cell marker.
    - **CD4 and CD8:** Standard markers to distinguish helper and cytotoxic lineages.
    - **CD45RA vs CD45RO:** Distinguishes naive (RA) and memory/activated (RO) populations.
    - **CD62L (L-selectin) and CCR7:** High on naive (and TCM) cells, low on effector (and TEM) cells.
    - **CD25 (high) and FoxP3:** Definitive phenotypic markers for Regulatory T cells (Tregs).
    - **CD69 and CD103:** Definitive markers for Tissue-Resident Memory T cells (TRMs).
    - **PD-1 and TOX:** High, stable expression indicates exhausted T cells.
*   **Exceptions to the Rule:**
    - **IL-7 Signaling Dependency in Humans vs. Mice:** While IL-7/IL-7R signaling is absolutely required for both B and T cell development in mice (IL-7Rα-deficient mice lack all B and T lymphocytes), in humans, mutations in **IL7RA** cause T-SCID (complete absence of T cells) but mature B cells develop in normal numbers.
    - **Mucosa-Associated Invariant T (MAIT) Cells:** A subset of T cells expressing an invariant TCR α chain (Vα7.2 rearranged to Jα33/Jα20/Jα12 in humans). Unlike conventional T cells, MAIT cells do not recognize peptides on MHC; instead, they recognize bacterial and fungal riboflavin (vitamin B2) metabolites presented by the nonpolymorphic MHC Class I-like molecule **MR1**. Most are CD8+, express CD95/FAS, reside abundantly in the liver (up to 40% of hepatic T cells) and mucosa, and secrete IFN-γ and TNF upon activation.
    - **Natural Killer T (NKT) Cells:** T cells expressing αβ TCRs of limited diversity that recognize glycolipid antigens presented by the nonpolymorphic MHC Class I-like molecule **CD1** (specifically CD1d), rather than peptide-MHC. They secrete cytokines to activate or suppress innate and adaptive responses.
    - **gamma-delta (γδ) T Cells:** T cells expressing γδ heterodimeric TCRs. They develop in the thymus but reside predominantly in epithelial barriers and mucosa. They have limited diversity, recognize nonpeptide antigens (such as alkyl amines and phosphorylated metabolites) directly without MHC-associated presentation, and do not require CD4 or CD8 coreceptors.