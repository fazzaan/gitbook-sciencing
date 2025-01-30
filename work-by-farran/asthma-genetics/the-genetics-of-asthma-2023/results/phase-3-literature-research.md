# Phase 3 – Literature research

## Key findings

_**Figure 3**:_

* _Name: Host-pathogen interaction of human coronaviruses interferon induction_
* _Last Modified: 20221118124334_
* _Organism: Homo sapiens_

<figure><img src="../../../.gitbook/assets/image (7).png" alt=""><figcaption><p>Figure 3. Pathway WP4880: IFN-I inducing JAK-STAT cascade, in ‘Host-pathogen interaction of human coronaviruses’. (WikiPathways, 2021)</p></figcaption></figure>

All four genes are components of the JAK-STAT cascade, instigated by Type‑I IFNs (interferons, a type of cytokine). The JAK‑STAT cascade is the innate antiviral immune response, activated by cytokines and growth factors, and is necessary for essential cell functions including proliferation, differentiation, migration, apoptosis and cell survival (Harrison, 2012). STAT1 & STAT2 form a complex, activating OAS proteins (_Fig. 3_). Each OAS is found in different cellular & subcellular locations and sequence-matches different viral RNAs, whose presence activates them. Of the cells that asthma primarily affects, these genes are especially expressed in macrophages and neutrophils (monocytes, T lymphocytes), alongside the key airway tissue cells of the airway epithelium (HAEC of this study) and the bronchiolar smooth muscle (_lamina propria_). Within cells, all are in cytoplasm and are varyingly distributed between cytosol, nucleoplasm and plasma membrane.

See _Table 2_ below.

_**Table 2**: Distribution of study genes throughout key cells and cellular components in asthma._

&#x20;Information collated from Human Protein Atlas (2023a, 2023b, 2023c, 2023d).

<figure><img src="../../../.gitbook/assets/image (9).png" alt=""><figcaption><p><em><strong>Table 2</strong>: Distribution of study genes throughout key cells and cellular components in asthma.</em></p></figcaption></figure>



## _STAT_ genes

_STAT_ genes produce transcription factor (TF) proteins, ‘Signal Transducer and Activators of Transcription’. They regulate cell growth, survival and differentiation (Mitchell and John, 2005). Except for STAT6, all are JAK-activated (Hu _et al._, 2021) and only appear alongside JAK.

Dysregulation of the JAK-STAT pathway is well-documented in oncology, STAT proteins are known to be involved in tumour surveillance amongst other things (Wang _et al._, 2004; Antov _et al._, 2003; Kaplan _et al._, 1998), demonstrating its importance as an interferon-signalling mediator through the cell membrane to immune response.

### STAT2

Type‑I IFNs (IFNα, IFNβ), bind to cell-surface IFN receptors that activate JAK (Janus kinase) and TYK (Tyrosine kinase), which activate STAT1 & STAT2 by phosphorylation & dimerization.

STAT2 cannot bind to DNA, but forms a TF complex with STAT1 & IRF9 (ISGF3G) that enters the nucleus and binds to ISRE (Interferon-Stimulated Response Element), activating ISG (Interferon-Stimulated Genes) transcription which instates the cell’s antiviral mode: OAS protein activation (_Fig. 4_).

<figure><img src="../../../.gitbook/assets/image (10).png" alt=""><figcaption><p>Figure 4: Detail of JAK-STAT cascade in WP4880, showing STAT1, STAT2, OAS1, OAS2 &#x26; OAS3. (WikiPathways, 2021)</p></figcaption></figure>

STAT2 modulates phosphorylation, regulating mitochondrial fission, and can _self_-regulate via negative feedback by recruiting USP18 (Ubiquitin-Specific Peptidase 18) to block the type‑I IFN receptor’s second subunit (IFNAR2), inhibiting its response (Arimoto _et al._, 2017).

STAT inhibitors, such as STATβ and STATγ (C‑terminally truncated isoforms of STAT proteins), act by competing with full‑form STATα proteins for binding sites, although no STATβ has been identified for STAT2 (Mitchell and John, 2005).

C‑terminally truncated STAT proteins (STATβ, STATγ) inhibit STAT function by competing with full‑form STATα proteins for binding sites. No STATβ has been identified for STAT2 (Mitchell and John, 2005).

## _OAS_ genes

All OAS proteins are in immune cells and cytosol. Each confer antiviral protection against different sets of viruses.

OAS1 is protoplasmic, OAS3 is especially expressed in lymphatic endothelial cells and adipocytes; OAS1 & OAS2 expression clusters in the innate immune response macrophages. OAS2 provides a different kind of antiviral protection, thus has a different expression profile (Human Protein Atlas 2023a, 2023b, 2023c).

&#x20;

### **Macrophages**

Macrophages are responsible for killing antigens directly, and presenting them to the immune system to assist adaptive immunity. Inside macrophages, OAS1 and OAS3 negatively regulate expression of chemokines and IFN-responsive genes, demonstrated by gene-knockout variant experimentation (Lee _et al._, 2019).

Excessive macrophage activity seems problematic: one study showed that, when alveolar macrophages (AM) were removed, Th2‑type inflammation & airway remodelling were suppressed in asthmatic mice whilst lung function worsened in normal mice (Lee _et al._, 2015). Macrophages cluster when the immune system is activated by viral challenge, increasing inflammation and eventually triggering airway remodelling in asthmatics. This presents a therapeutic target opportunity.

&#x20;

### **OAS-RNase pathway**

Viral dsRNA binds to and activates OAS proteins, which synthesize 2‑5As (2′‑5′‑oligoadenylates) from ATP, releasing pyrophosphate. The 2‑5As bind to monomeric RNaseL (latent RNase, RNA degrader) and activate it by dimerization, which cleaves all RNA it finds: viral RNA and the cell’s own, preventing the virus from replicating and synthesizing proteins  (Human Protein Atlas 2023a, 2023b, 2023c). The RNaseL-cleaved chunks of RNA lead to cytosolic cytochrome c release, triggering apoptosis (Siddiqui _et al._, 2015).

Overreactive OAS response to viral challenge can trigger cytokine storms and destabilize the immune response (Pasrija and Naime, 2021), leading to apoptosis. One pathway is via activation of RIG‑1, in which degraded RNA fragments increase IFN production and activate the NF‑κB (_nuclear factor kappa-light-chain-enhancer of activated B cells_) pathway \[KEGG hsa04064] (KEGG, 2023), thereby increasing cytokine production & inflammation and driving apoptosis (Ronni _et al._, 1997); indeed, NF‑κB is already implicated in asthma, alongside other overlapping inflammatory diseases (Pai and Thomas, 2008; Liu _et al._, 2017).

RNaseL activation and RNA fragments lead to cell apoptosis. OAS proteins can mediate an antiviral effect via another pathway independent of RNaseL, suggesting the possibility of antiviral effects without cell destruction.

### **RNaseL independence**

OAS-RNaseL pathway deficiency can cause excessive cytokine production and inflammation dysregulation: interfering with this may be harmful (Lee _et al._, 2023). However, RNaseL-deficient organisms have shown viral challenge resistance, via OAS1 proteins travelling between cells (Madden _et al._, 2019; Kristiansen _et al._, 2010). Produced by a virally infected cell, OAS1 proteins are released as paracrine agents and taken up by neighbouring cells. They then reduce viral replication: a recent study (Torices _et al._, 2023) exploring the OAS gene family cited several papers from 1997-2006 regarding the observed effects of non‑RNaseL antiviral activity, yet none of them contain insight as to how this pathway operates. Alongside other recent papers regarding this, it seems this is presently unknown. This ability is supported by the discovery that only OAS3 is sufficient for RNaseL activation (via 2‑5A production), yet in OAS3 knockout trials, OAS1 and OAS2 still showed antiviral activity despite not activating RNaseL. (However, excessive upregulation of OAS1 appeared to produce enough 2‑5A to activate RNaseL.) (Li _et al._, 2016)

Some viruses escape antiviral effects by degrading 2‑5A, inhibiting RNaseL activation (Drappier and Michiels, 2015): these effects are usually bad for health, but could provide a model method for regulating excessive asthmatic response to other triggers.
