---
aliases:
  - NOD-Like Receptors
  - NLR
  - Inflammasome
  - NLRP3 Inflammasome
  - NOD1
  - NOD2
  - Cryopyrin
molecule_class: Pattern Recognition Receptors (PRRs)
cellular_expression:
  - Macrophages
  - Dendritic cells
  - Neutrophils
  - Monocytes
  - Epithelial cells
  - Paneth cells
  - Phagocytes
primary_ligand: Pathogen-Associated Molecular Patterns (PAMPs) and Damage-Associated Molecular Patterns (DAMPs)
signaling_motif: Caspase Recruitment and Activation Domain (CARD) / Pyrin (PYD) / NACHT (NOD) domain
date: 2026-09-06
draft: false
---

### NOD-Like Receptors (NLRs) and The Inflammasome
#### Structure & Genetics
*   **Molecular Structure & Subunits:**
    - NOD-like receptors (NLRs) are a family of more than 20 structurally homologous cytosolic proteins. A typical NLR monomer contains three primary functional domains:
        1. *C-Terminal Domain:* Composed of multiple leucine-rich repeats (LRRs) that act as the sensor to detect specific pathogen-associated molecular patterns (PAMPs), damage-associated molecular patterns (DAMPs), or downstream intracellular physiological changes.
        2. *Central Domain:* Known as the NOD (nucleotide oligomerization domain) or NACHT domain, which is essential for self-oligomerization and nucleotide-binding (ATP-dependent conformation changes).
        3. *N-Terminal Domain:* The effector domain responsible for initiating downstream signaling complexes. Based on these N-terminal effector domains, the NLR family is classified into distinct subfamilies:
            - **NLRA subfamily:** Employs an N-terminal transactivating (TA) domain. The prototype is CIITA (Class II MHC Transcription Activator), which regulates MHC class II gene expression.
            - **NLRB subfamily:** Employs an N-terminal BIR (baculovirus inhibition of apoptosis protein repeat) domain. An example is NAIP (neuronal apoptosis inhibitory protein).
            - **NLRC subfamily:** Employs an N-terminal CARD (caspase recruitment and activation domain) that recruits other CARD-containing proteins to initiate signaling or activate caspases. Examples include NOD1, NOD2, and NLRC4.
            - **NLRP subfamily:** Employs an N-terminal pyrin (PYD) domain. Examples include NLRP1 through NLRP10.
    - *The Canonical Inflammasome:* A multiprotein enzymatic platform assembled in the cytosol in response to infection or cellular stress. Canonical inflammasomes are composed of three essential structural units:
        1. *A Sensor:* Often an NLR protein (e.g., NLRP3, NLRC4, NLRP1, pyrin) or a non-NLR protein (such as the cytosolic DNA sensor AIM2).
        2. *An Adaptor:* Apoptosis-associated speck-like protein containing a CARD (ASC). ASC contains an N-terminal PYD (which binds the sensor's PYD via homotypic interactions) and a C-terminal CARD. Upon sensor activation, ASC polymerizes into high-molecular-weight filaments that aggregate into a single cytosolic cluster (the "ASC speck" or ASC focus) via a self-propagating, prion-like mechanism.
        3. *An Effector Enzyme (Procaspase-1):* The CARD domain of ASC recruits the CARD-containing zymogen procaspase-1. This clustering brings procaspase-1 molecules into close proximity, triggering auto-proteolytic cleavage and activation into active caspase-1.
    - *The Non-Canonical Inflammasome:* Assembles independently of the ASC-caspase-1 pathway. In humans, cytosolic caspases 4 and 5 (and caspase-11 in rodents) act directly as receptors that bind cytoplasmic Gram-negative bacterial lipopolysaccharide (LPS) with high affinity. This direct binding induces caspase oligomerization and activation.
*   **Gene Locus & Rearrangement:**
    - NLRs, ASC, and caspase components are germline-encoded pattern recognition receptors of the innate immune system. They do not undergo somatic recombination, gene rearrangement, or V(D)J recombination.
*   **Associated Chaperone Proteins:**
    - N/A (The sources do not specify obligate chaperone proteins unique to NLR synthesis or trafficking, unlike endosomal TLRs which require UNC93B).
*   **Polymorphisms & Isotypes:**
    - *NOD2 Polymorphisms:* Specific loss-of-function polymorphisms in the NOD2 gene (e.g., mutations affecting LRR-mediated ligand sensing) are strongly associated with increased susceptibility to Crohn's disease (a chronic inflammatory bowel disease). These variants impair mucosal innate defense, allowing commensal gut bacteria to invade the intestinal wall and trigger unregulated Th1/Th17 chronic inflammation.
    - *NLRP3 mutations:* Dominant germline gain-of-function mutations in the NLRP3 gene (also known as cryopyrin) cause Cryopyrin-Associated Periodic Syndromes (CAPS). CAPS represents a clinical spectrum of autoinflammatory syndromes including Familial Cold Autoinflammatory Syndrome (FCAS), Muckle-Wells syndrome, and Neonatal-Onset Multisystem Inflammatory Disease (NOMID). Somatic mutations in myeloid lineages also cause CAPS.
    - *MEFV mutations:* Inherited mutations in the MEFV gene, which encodes the non-NLR sensor pyrin, cause Familial Mediterranean Fever (FMF).
    - *NLRC4 mutations:* Gain-of-function mutations in NLRC4 lead to excessive IL-18 production and cause Autoinflammation with Infantile Enterocolitis (AIFEC) or Familial Cold Autoinflammatory Syndrome 4 (FCAS4).

#### Expression & Binding
*   **Cells Expressing this Molecule:**
    - NLRs and inflammasome components are widely expressed in phagocytes (macrophages, monocytes, and neutrophils), classical and plasmacytoid dendritic cells, and mucosal barrier epithelial cells.
    - NOD2 is highly expressed in intestinal Paneth cells located at the base of the crypts of Lieberkühn in the small bowel.
*   **Primary Ligands / Antigens:**
    - *NOD1:* Recognizes a glycosylated tripeptide containing diaminopimelic acid (DAP), derived mainly from the peptidoglycan cell walls of Gram-negative bacteria.
    - *NOD2:* Recognizes muramyl dipeptide (MDP), a peptidoglycan constituent present in both Gram-positive and Gram-negative bacteria.
    - *NLRP3:* Activated by a structurally diverse range of PAMPs and DAMPs. NLRP3 does not bind these ligands directly; instead, it senses downstream cytoplasmic stress or physiological alterations, including:
        - Extracellular ATP (released from damaged mitochondria or cells, which acts via cell-surface P2X7 receptors to trigger K+ efflux).
        - Environmentally or endogenously derived crystalline substances: monosodium urate (uric acid) crystals in gout, calcium pyrophosphate crystals in pseudogout, inhaled silica and asbestos (which cause lysosomal membrane damage, releasing reactive oxygen species (ROS) into the cytosol), cholesterol crystals in atherosclerosis, free fatty acids and lipids in obesity-associated metabolic syndrome/type 2 diabetes, and β-amyloid in Alzheimer's disease.
        - Bacterial pore-forming toxins (e.g., streptolysin O, staphylococcal toxins) that cause ion leakage.
        - Microbial components: bacterial DNA-RNA hybrids, influenza virus, lipopeptides (sensed via NLRP7).
        - Intracellular physiological triggers: marked reduction in cytosolic potassium ion (K+) concentration (K+ efflux), cytosolic reactive oxygen species (ROS) generated during cell injury, and lysosomal membrane disruption.
    - *NLRC4:* Recognizes cytosolic flagellin and structural components of the bacterial Type III secretion system (T3SS), which pathogenic bacteria use to deliver toxins.
    - *NLRP1:* Recognizes the anthrax lethal toxin.
    - *AIM2:* Directly binds cytosolic double-stranded DNA (dsDNA) released from intracellular replicating microbes or damaged host cells.
    - *Pyrin:* Senses post-translational modifications (specifically inactivation) of host Rho-family GTPases mediated by various bacterial virulence toxins.
*   **Binding Kinetics & Affinity:**
    - NLRs bind their specific PAMPs/DAMPs with fixed, germline-determined affinities. No affinity maturation occurs. NLRP3 activation is characterized by indirect sensing of intracellular cellular distress (stress kinetics), where multiple varied cellular injuries converge on K+ efflux and ROS generation to trigger NLRP3 oligomerization.
*   **Co-receptors Required for Binding:**
    - *NAIP5:* Functions as the direct sensor for flagellin in the NLRC4 inflammasome, physically associating with NLRC4 to initiate oligomerization.
    - *ASC:* Acts as the obligate structural linker and co-receptor for PYD-containing sensors (NLRP3, AIM2, pyrin, NLRP1) to recruit procaspase-1.
    - *CD14 / TLR priming:* Priming of the NLRP3 inflammasome requires initial cell-surface pattern recognition (such as LPS binding CD14/TLR4) to upregulate transcription of NLRP3 and pro-IL-1β.
*   **Role as a Transplant, Blood Group, or Tumor Antigen:**
    - NLRs and inflammasomes are intracellular proteins and do not serve as polymorphic blood group or transplant antigens. However, sterile tissue necrosis during allograft ischemia and reperfusion releases endogenous DAMPs (such as extracellular ATP, HMGB1, and HSPs) that ligate TLRs and trigger the NLRP3 inflammasome. This drives massive local IL-1β release and neutrophil recruitment, which primes dendritic cells and promotes alloreactive host T-cell responses, accelerating transplant rejection.

#### Signal Transduction
*   **Intracellular Signaling Motifs:**
    - Toll/Interleukin-1 Receptor (TIR) domains (found in IL-1R and TLRs, sharing signaling intermediates with NLR pathways).
    - Caspase Recruitment and Activation Domain (CARD) in NOD1, NOD2, and NLRC4.
    - Pyrin Domain (PYD) in NLRP3, AIM2, and pyrin.
    - NACHT/NOD domain, which binds ATP and coordinates conformational changes for self-oligomerization.
*   **Associated Kinases & Adaptor Proteins:**
    - **RIP2 (RIPK2):** A serine-threonine kinase containing a CARD domain. Homotypic CARD-CARD interactions with ligated NOD1 or NOD2 recruit RIP2 to form a macromolecular signaling complex (the "NOD signalosome").
    - **TRAF6:** An E3 ubiquitin ligase recruited downstream of RIP2 or TLRs. It catalyzes the assembly of Lys63 (K63)-linked polyubiquitin chains on NEMO/IKKγ, activating the IκB kinase (IKK) complex.
    - **ASC:** The PYD-CARD adaptor that bridges PYD-sensors to procaspase-1.
    - **Caspase-1:** The cysteine protease effector of canonical inflammasomes. It is recruited as the inactive zymogen procaspase-1 and undergoes proximity-induced auto-proteolytic cleavage into active caspase-1.
    - **Caspase-4, Caspase-5 (humans) / Caspase-11 (rodents):** Inflammasome caspases that directly bind cytosolic LPS via their CARD domains to execute non-canonical inflammasome activation.
*   **Downstream Transcription Factors Activated:**
    - **NF-κB (p50/p65):** Activated via the NOD1/2-RIP2-TRAF6 pathway. RIP2 activates the IKK complex (IKKα, IKKβ, NEMO), which phosphorylates IκBα, targeting it for Lys48 polyubiquitination and proteasomal degradation. Active NF-κB translocates to the nucleus to transcribe inflammatory cytokines (TNF, IL-6) and antimicrobials (defensins). NF-κB is also the essential "Signal 1" (priming signal) for the NLRP3 inflammasome, driving transcription of the inactive precursors pro-IL-1β and pro-IL-18, as well as NLRP3 itself.
    - **AP-1 (JUN/FOS):** Co-activated with NF-κB via RIP2-dependent MAP kinase pathways (JNK, p38) to drive the transcription of inflammatory genes.

#### Functional Outcomes
*   **Cellular Response to Ligation:**
    - *NOD1 and NOD2 Ligation:* Drives NF-κB-dependent inflammation. In the small bowel, NOD2 ligation in Paneth cells specifically stimulates the synthesis and secretion of antimicrobial α-defensins (cryptidins). Defensins insert into and disrupt microbial phospholipid membranes to limit luminal bacterial load near the epithelial barrier. NOD2 also stimulates autophagy (via ATG16L1 and IRGM) and type I interferon production.
    - *Canonical Inflammasome Activation (Active Caspase-1):*
        1. *Cytokine Processing:* Active caspase-1 (a cysteine protease that cleaves substrates after aspartate residues) proteolytically cleaves the inactive 33-kD cytoplasmic precursor pro-IL-1β into the biologically active 17-kD mature IL-1β. It similarly cleaves the inactive precursor pro-IL-18 into mature IL-18.
        2. *Gasdermin D Cleavage:* Caspase-1 cleaves the cytosolic protein gasdermin D, releasing its autoinhibitory C-terminal domain. The resulting active N-terminal fragment (gasdermin-N) oligomerizes and inserts into the host cell plasma membrane, forming large, symmetrical pores.
        3. *Cytokine Secretion:* Because IL-1β and IL-18 lack hydrophobic signal sequences to enter the classical secretory pathway (endoplasmic reticulum/Golgi), they are released from the cytosol directly through the gasdermin-N membrane pores.
    - *Pyroptosis:* The insertion of thousands of gasdermin-N pores into the plasma membrane allows a rapid, uncontrolled influx of water and extracellular ions into the cytosol, while intracellular potassium (K+) effluxes out. This results in severe cell swelling, osmotic lysis, and loss of plasma membrane integrity. This highly inflammatory form of programmed cell death is called pyroptosis. It occurs readily in macrophages and dendritic cells, releasing massive amounts of active IL-1β, IL-18, TNF, IL-6, and chemokines (IL-8/CXCL8) to amplify local inflammation. Pyroptosis also deprives intracellular pathogens of their replicative niche and exposes them to extracellular killing.
    - *Non-Canonical Inflammasome Activation:* Direct cytosolic LPS binding activates Caspase-4/5/11, which cleaves gasdermin D to form gasdermin-N pores and execute pyroptosis. This potassium efflux through Caspase-4/5/11-generated gasdermin pores secondarily activates the NLRP3-ASC-caspase-1 canonical inflammasome, driving the processing and release of mature IL-1β and IL-18.
*   **Role in Immune Cascade:**
    - **Interleukin-1β (IL-1β):** Secreted by pyroptotic cells or through gasdermin pores. IL-1β binds to CD121a (IL-1R1) on local endothelial cells to upregulate adhesion molecules (E-selectin, ICAM-1, VCAM-1) and stimulate chemokine (CXCL8) production, recruiting neutrophils and monocytes to the infection site. Systemically, IL-1β travels to the hypothalamus to induce prostaglandin E2 synthesis, resetting the thermal set-point to cause fever. It also acts on the liver to stimulate the synthesis of acute-phase proteins (C-reactive protein, PTX3, serum amyloid P) and acts on T lymphocytes to promote helper Th17 cell differentiation.
    - **Interleukin-18 (IL-18):** Binds to CD218a/b (IL-18R) on NK cells and T cells. It acts synergistically with IL-12 to stimulate high-level synthesis of interferon-gamma (IFN-γ) by NK cells and T cells, driving Th1 polarization and classical (M1) macrophage activation (upregulating iNOS and NADPH oxidase to produce nitric oxide and ROS).
*   **Regulation & Down-modulation:**
    - **IL-1 Receptor Antagonist (IL-1RA):** A soluble protein synthesized and secreted by macrophages. IL-1RA acts as a competitive antagonist that binds to CD121a (IL-1R1) on target cells without recruiting the accessory protein IL-1RAP, thereby blocking IL-1α and IL-1β signaling.
    - **Autophagy (ATG16L1, IRGM):** Down-modulates inflammasome activity by sequestering and degrading assembled NLRP3 complexes, ASC specks, and damaged mitochondria (preventing mitochondrial ROS generation and mitochondrial DNA release into the cytosol).
    - **Plasma Carboxypeptidases:** Rapidly cleave the C-terminal arginine residues of the complement anaphylatoxins C3a and C5a (which prime innate cells) to produce C3a des-Arg and C5a des-Arg, reducing their pro-priming activity by 90%.
    - **IL-10 and TGF-β:** Cytokines produced by regulatory T cells (Tregs) and homeostatic gut macrophages that act via their respective receptors to suppress NF-κB activation and downstream transcription of NLRP3 and pro-IL-1β.

#### Clinical & Pharmacologic Relevance
*   **Associated Immunodeficiencies (if mutated):**
    - *MyD88 and IRAK4 Deficiencies:* Prevent the priming of pro-IL-1β and NLRP3 expression. Children present with recurrent, life-threatening invasive pyogenic bacterial infections (Streptococcus pneumoniae, Neisseria meningitidis). A diagnostic hallmark is the *complete absence of fever* or elevated CRP in the setting of severe bacterial sepsis due to the loss of MyD88-dependent pyrogenic cytokine transcription.
    - *IL-1RA Deficiency (DIRA):* Autosomal recessive loss-of-function mutations in the IL1RN gene cause Deficiency of Interleukin-1 Receptor Antagonist (DIRA). In the absence of IL-1RA feedback, patients experience unopposed, spontaneous IL-1 signaling, presenting with high fevers, neutrophilic skin rashes, and sterile bone inflammation (osteomyelitis).
    - *NOD2 Loss-of-Function:* Associated with increased susceptibility to Crohn's disease due to impaired mucosal barrier defense and defensin production.
    - *UNC93B, TLR3, TRIF, TBK1, and TRAF3 mutations:* Autosomal recessive or dominant-negative mutations abolish endosomal TLR3/7/8/9 and TRIF-dependent Type I IFN production, presenting as isolated, recurrent Herpes Simplex Virus (HSV) encephalitis in the brain.
*   **Targeted Biologic Therapies (Monoclonal Antibodies):**
    - **Anakinra:** A recombinant human IL-1 receptor antagonist (IL-1RA) that competitively blocks both IL-1α and IL-1β binding. Approved for the treatment of severe gout, rheumatoid arthritis, CAPS, and DIRA.
    - **Canakinumab:** A high-affinity human monoclonal antibody that specifically neutralizes soluble IL-1β. Used to treat CAPS, systemic juvenile idiopathic arthritis, and severe gout, and in clinical trials to reduce cardiovascular events in atherosclerosis.
    - **Rilonacept:** A soluble decoy receptor (IL-1 trap) composed of the ligand-binding domains of IL-1R1 and IL-1RAP fused to the Fc portion of IgG1, which binds and neutralizes IL-1. Used to treat CAPS.
    - **Emapalumab:** An anti-IFN-γ neutralizing antibody used to treat Hemophagocytic Lymphohistiocytosis (HLH), which can complicate severe autoinflammatory syndromes.
*   **Pathogen Sabotage or Mimicry:**
    - *Phagolysosomal escape:* Listeria monocytogenes produces the hemolysin protein listeriolysin O to lyse the phagosome membrane, escaping into the host cell cytoplasm to replicate, avoiding endosomal TLR detection but exposing its flagellin to NLRC4.
    - *Inhibition of Phagolysosome Fusion:* Mycobacterium tuberculosis and Legionella pneumophila survive inside macrophages by preventing phagosome-lysosome fusion.
    - *ROS Scavenging:* Catalase-positive pathogens (such as Staphylococcus aureus) produce catalase to degrade hydrogen peroxide, reducing the cytosolic ROS levels that would otherwise trigger NLRP3 inflammasome assembly.
    - *Decoy Cytokine Receptors:* Poxviruses and other DNA viruses encode soluble decoy receptors for TNF and IL-1, or express viral homologs of IL-10 (e.g., EBV-derived viral IL-10) to actively suppress local host endothelial activation and inflammasome-driven leukocyte recruitment.

#### Trivia & Edge Cases
*   **Buzzwords & Descriptors:**
    - "Autoinflammatory syndromes" vs "Autoimmune diseases" (autoinflammatory diseases are disorders of innate immunity characterized by spontaneous, cytokine-driven inflammation without self-reactive T cells or autoantibodies).
    - "ASC specks / ASC focus" (highly aggregated cytosolic ASC filaments recruited to a single point during inflammasome activation).
    - "NOD signalosome" (conformation-changed NOD CARD recruiting RIP2).
    - "Pyroptosis" (gasdermin D-mediated osmotic cell death of macrophages and DCs).
    - "Missing self-recognition" (NK cell activation, though unrelated to NLRs, NLR-activated IL-18/IL-12 primes NK cell IFN-gamma production).
    - "DAP and MDP" (peptidoglycan ligands for NOD1 and NOD2).
*   **Exceptions to the Rule:**
    - *Blau Syndrome vs Crohn's Disease:* Gain-of-function mutations in the NOD2 gene lead to Blau syndrome (a systemic autoinflammatory disease characterized by granulomatous uveitis, arthritis, and neutrophilic skin lesions). Conversely, loss-of-function polymorphisms in the NOD2 gene reduce mucosal defense and increase susceptibility to Crohn's disease (localized intestinal mucosal inflammation).
    - *NLRC4 Gain of Function and Enterocolitis (AIFEC):* Germline gain-of-function mutations in NLRC4 lead to massive, unregulated IL-18 production by intestinal epithelial cells. This causes severe early-onset enterocolitis (AIFEC) and predisposes infants to life-threatening Hemophagocytic Lymphohistiocytosis (HLH) due to IL-18-driven IFN-γ hyperproduction by NK cells and CTLs.
    - *Pyroptosis Selectivity:* Pyroptosis occurs readily in macrophages and dendritic cells, but does *not* occur in neutrophils, despite neutrophils expressing high baseline levels of caspase-1 and gasdermin D. This physiological exception protects recruited neutrophils from premature osmotic lysis, allowing them to execute their full bactericidal functions (respiratory burst, degranulation, and NET formation) at the site of infection.
    - *Non-canonical Inflammasome Species Difference:* Rodent cells rely on Caspase-11 to directly sense cytosolic LPS and drive pyroptosis, whereas human cells utilize Caspase-4 and Caspase-5 to execute this non-canonical pathway.
    - *NLRA (CIITA) No Effector Function:* While other NLRs function as cytoplasmic sensors of PAMPs/DAMPs, the NLRA member CIITA (Class II transactivator) contains an N-terminal transactivating domain and NACHT/LRR domains, but functions exclusively as a master nuclear transcription factor that coordinates the expression of MHC class II genes. Autosomal recessive mutations in CIITA cause Bare Lymphocyte Syndrome Type II (MHC Class II Deficiency).