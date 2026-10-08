# UCSC Cell Browser Activity

## Assigned Gene and Disease

**Gene:** GALT (galactose-1-phosphate uridylyltransferase)

**Associated Disease:** Classic Galactosemia

This activity uses the same assigned disease gene from the previous genome and mutation activities. The UCSC Cell Browser was used to investigate the expression of **GALT** at the single-cell level and identify the cell types or clusters in which the gene is detectable.



## Organ/Tissue Choice and Dataset Information

The UCSC Cell Browser was used to identify a human single-cell dataset relevant to the assigned **GALT** gene and **classic galactosemia**. The dataset information, including the tissue, organism, study title, publication, and dataset ID, was obtained from the Dataset Information window in the UCSC Cell Browser.

**Dataset:** Normal and Inflamed Human Epidermis

**Dataset ID:** `human-epidermis`

**Organ/Tissue:** Skin/Epidermis

**Organism:** Human (*Homo sapiens*)

**Study:** *Transcriptional Programming of Normal and Inflamed Human Epidermis at Single-Cell Resolution*

**Publication:** Cheng et al. (2018), *Cell Reports*

**PubMed:** 30355494

**Study Accession:** EGAS00001002927

**Dataset URL:**  
https://cells.ucsc.edu/?ds=human-epidermis&gene=GALT



### Screenshot 1: Dataset
*Description: The dataset used for the analysis, showing the available study information and data characteristics.*
* [View screenshot 1 (Dataset)](screenshots/01_dataset.png)
* 
**Figure 1. Dataset information for the Normal and Inflamed Human Epidermis single-cell dataset in the UCSC Cell Browser.**

The dataset contains single-cell RNA-sequencing profiles from human epidermal tissue. The dataset was selected because it provides cell-level gene-expression information that can be used to examine the distribution of GALT expression across different epidermal cell populations.



## Why This Dataset Was Selected?

The Normal and Inflamed Human Epidermis dataset was selected because it contains human skin cells and several annotated epidermal cell populations that can be examined for **GALT** expression. Although classic galactosemia primarily results from impaired galactose metabolism, examining GALT expression at the single-cell level provides information about where the gene is detectable in the cells represented by this dataset.

The dataset is also useful for comparing GALT expression among different cell clusters, including basal, spinous, follicular, WNT1, melanocyte, channel, and immune populations.



# Understanding the Cell Map

The UCSC Cell Browser was used to examine the cell map of the Normal and Inflamed Human Epidermis dataset. The cell map displays individual cells according to their molecular similarity and provides annotated clusters representing different cell populations.

## Cell Map Observations

### a. What type of visualization is being shown (UMAP, t-SNE, or another layout)?

The cell map uses a **UMAP (Uniform Manifold Approximation and Projection)** embedding. UMAP is used to visualize relationships among individual cells based on their molecular profiles.

### b. What does one dot represent?

Each dot represents one measured cell in the single-cell dataset. Cells located close to one another generally have more similar molecular profiles.

### c. What do the clusters represent in this particular dataset?

The clusters represent different cell types or cell states identified from the human epidermis dataset. The labeled populations include **basal1, basal2, spinous, follicular, mitotic, WNT1, channel, melanocyte, and immune** cells.



# Assigned Gene Expression

The assigned gene **GALT** was searched using the Gene tab in the UCSC Cell Browser. After selecting GALT, the cell map was recolored according to GALT expression, and the expression legend showed the distribution of expression values across the cells.

### a. Assigned gene symbol:

My assigned gene is **GALT (galactose-1-phosphate uridylyltransferase)**.

### b. Dataset used:

The dataset used is **Normal and Inflamed Human Epidermis**.

### c. Is expression widespread, restricted, or low/undetected?

GALT expression appears **relatively widespread but generally low or undetected in many cells**. The expression legend shows that approximately **77.1% of cells have a value of 0**, while the remaining cells show detectable GALT expression at different levels.

Unlike a gene with expression concentrated in only one cell type, the GALT expression map shows detectable signal across several epidermal cell clusters.

### d. Which cluster(s) appear to contain cells with stronger expression?

The GALT expression map shows detectable expression across several clusters, with visible expression in populations such as the **basal1, basal2, spinous, follicular, and other epidermal clusters**. The expression is therefore not limited to a single cell population.

### e. Which cluster(s) appear to contain little or no detectable expression?

Many cells across the dataset show little or no detectable GALT expression. The expression legend indicates that the largest proportion of cells, approximately **77.1%**, has an expression value of 0.

### Screenshot 2: Gene Expression
*Description: The gene expression results showing the expression pattern of the selected gene in the analyzed dataset.*
* [View screenshot 2 (Gene Expression)](screenshots/02_gene_expression.png)

**Figure 2. Expression of the human GALT gene across cells in the Normal and Inflamed Human Epidermis dataset.**

Figure 2 presents the distribution of GALT expression across the cell map after the gene was selected in the UCSC Cell Browser. Most cells show zero or low expression, while detectable expression is distributed across several cell populations.


# Cell-Type/Cluster Expression of GALT

The cell-type distribution of **GALT** expression was examined using the annotated cell map in the UCSC Cell Browser. The map was viewed with the cell-type/cluster labels visible to determine whether GALT expression was concentrated in a particular cell population.

### a. Cell type/cluster with the strongest visible expression:

The **basal1 and basal2 regions** show visible GALT expression, although detectable expression is also present in other cell populations.

### b. Another cell type/cluster with detectable expression:

The **spinous and follicular clusters** also show detectable GALT expression in the cell map.

### c. Cell type/cluster with relatively low or undetected expression:

Several cells in the other clusters show low or undetected GALT expression. The immune, WNT1, channel, and melanocyte populations contain many cells with low or zero values.

### d. Is the expression pattern broad or cell-type restricted?

The GALT expression pattern appears **relatively broad rather than strongly cell-type restricted** in this dataset. Although some clusters show visible expression, GALT is not limited to a single cell type.

### e. Possible biological explanation:

The observed pattern is consistent with the role of GALT as a metabolic enzyme involved in galactose metabolism. GALT participates in the Leloir pathway and catalyzes the conversion of galactose-1-phosphate and UDP-glucose into UDP-galactose and glucose-1-phosphate. Therefore, GALT may be expressed in multiple cell types because galactose metabolism is a cellular metabolic process rather than a function specific to only one cell type.

### Screenshot 3: Cell Types
*Description: The cell types identified in the dataset, representing the different cellular populations included in the analysis.*
* [View screenshot 3 (Cell Types)](screenshots/03_cell_types.png)
  
**Figure 3. GALT gene-expression map showing cell-type/cluster annotations in the Normal and Inflamed Human Epidermis dataset.**

Figure 3 shows the GALT expression pattern together with the annotated cell populations. Detectable GALT expression can be observed across multiple epidermal clusters rather than being restricted to one cell type.


# Selected Cells and Gene-Expression Comparison

The **basal1** region was examined more closely while GALT remained active in the Gene tab of the UCSC Cell Browser.

In the submitted screenshot, one cell from the basal1 region was selected.

### a. Which cells/cluster did you select?

I selected a cell from the **basal1 cluster**. The screenshot shows **1 cell selected** from the basal1 region.

### b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?

The selected cell is located within the basal1 cluster, where GALT expression is detectable. However, because only one cell was selected in the screenshot, the result should not be interpreted as a comparison of the entire basal1 population.

### c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?

The expression plot provides a way to examine the distribution of GALT expression values among selected cells and comparison cells. The cell map mainly shows where cells are located, whereas an expression plot can provide a clearer view of the actual expression-value distribution.



# Marker Genes of the Basal1 Cluster

The basal1 cluster was examined using the **Cluster Markers** function in the UCSC Cell Browser. The displayed marker table identified several genes associated with the basal1 cluster.

The marker genes visible in the table included:

1. **COL17A1**
2. **KRT15**
3. **DST**
4. **TGFBI**
5. **KRT14**
6. **S100A6**

### a. Cluster/cell type examined:

The cluster examined was the **basal1 cluster**.

### b. Marker gene 1:

The first marker gene recorded was **COL17A1**.

### c. Marker gene 2:

The second marker gene recorded was **KRT15**.

### d. Marker gene 3:

The third marker gene recorded was **DST**.

### e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.

No. The assigned disease gene **GALT** does not appear to behave as a strongly cell-type-restricted marker in this dataset. Although detectable expression can be observed in several cell populations, the expression is not limited to the basal1 cluster. This differs from a typical cell-type marker whose expression is strongly concentrated in one specific cell population.

### Screenshot 4: Expression Plot
*Description: The expression plot illustrating the level and distribution of gene expression across the analyzed cell types.*
* [View screenshot 4 (Expression Plot)](screenshots/04_expression_plot.png)

**Figure 4. Marker-gene information for the basal1 cluster in the Normal and Inflamed Human Epidermis dataset.**

Figure 4 presents the marker-gene table generated for the basal1 cluster in the UCSC Cell Browser. The displayed marker genes include **COL17A1, KRT15, DST, TGFBI, KRT14, and S100A6**, which were identified as genes associated with the basal1 cluster.



# Comparison of the Assigned Disease Gene and a Marker Gene

The assigned disease gene **GALT**, associated with classic galactosemia, was compared with **COL17A1**, a marker gene identified from the basal1 cluster.

### a. Assigned disease gene:

The assigned disease gene is **GALT (galactose-1-phosphate uridylyltransferase)**, which is associated with **classic galactosemia**.

### b. Marker gene:

The marker gene selected for comparison is **COL17A1**, which was identified from the marker-gene table for the basal1 cluster.

### c. Which gene shows a more cell-type-restricted expression pattern?

**COL17A1** is more cell-type-associated in this analysis because it was identified as a marker of the basal1 cluster. In contrast, GALT expression is detectable across several cell populations in the dataset.

### d. Which gene appears more broadly expressed?

**GALT** appears more broadly expressed in the cell map because detectable GALT expression is observed across multiple clusters rather than being limited to the basal1 population.

### e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?

The comparison shows that a disease-associated gene and a cell-type marker gene can have different expression patterns. GALT is a disease-associated gene involved in galactose metabolism, but it does not necessarily need to be restricted to one cell type. In contrast, COL17A1 was identified as a marker associated with the basal1 cluster. Therefore, being associated with a disease does not automatically mean that a gene functions as a cell-type marker.



# Comparison of GALT and COL17A1 Expression

The expression patterns of the assigned disease gene **GALT** and the basal1 marker gene **COL17A1** were compared to examine their relationship with cell populations in the dataset.

| Comparison | Assigned Disease Gene (*GALT*) | Basal1 Marker Gene (*COL17A1*) |
|---|---|---|
| Role in this activity | Assigned disease gene associated with classic galactosemia | Marker gene identified from the basal1 cluster |
| Main biological role | Galactose metabolism through the Leloir pathway | Associated with basal cell identity and epidermal structure |
| Expression pattern observed | Detectable across multiple cell clusters | Identified as a marker of the basal1 cluster |
| Cell-type restriction | Relatively broad | More cell-type associated |
| Overall observed pattern | Broad/low expression across the dataset | More associated with basal1 cells |

Based on the observed cell map, **GALT** showed a broader expression pattern than the basal1 marker gene **COL17A1**. GALT expression was detectable in several cell populations, while COL17A1 was identified as a marker associated with the basal1 cluster. This comparison demonstrates that a disease-associated metabolic gene does not necessarily have the same expression pattern as a cell-type marker.


# Connecting the Cell Browser Result to the Previous Genome Activity

The results from the previous genome and mutation activities were connected with the current UCSC Cell Browser analysis to trace **GALT** from its chromosome location and gene structure to a disease-associated variant, gene expression, and the relevant cell populations.

The previous activities examined the genomic location and structure of GALT and the disease-associated variant **NM_000155.4:c.563A>G (p.Gln188Arg)**, while the current Cell Browser activity examined where GALT is expressed in the Normal and Inflamed Human Epidermis dataset.

### Chromosome location → Gene structure → Disease-associated variant → Gene expression → Cell type/tissue

**Chromosome 9 (9p13.3) → GALT gene → c.563A>G (p.Gln188Arg; Q188R) → GALT expression across multiple epidermal cell populations → human epidermis**

### 1. On which chromosome is your assigned gene located?

The assigned gene **GALT** is located on **chromosome 9**, specifically at **9p13.3**. GALT is a protein-coding gene that encodes galactose-1-phosphate uridylyltransferase.

### 2. What disease-associated variant did you examine previously?

The disease-associated variant examined previously was:

**NM_000155.4:c.563A>G (p.Gln188Arg)**

This is a missense variant in which adenine (A) is replaced by guanine (G) at coding position 563. The nucleotide change results in a predicted amino-acid substitution from glutamine (Q) to arginine (R) at position 188.

### 3. In the current Cell Browser dataset, which cell type(s) express the gene?

In the Normal and Inflamed Human Epidermis dataset, GALT expression was detectable across several cell populations, including basal1, basal2, spinous, follicular, and other clusters. A large proportion of cells showed zero expression, but the detectable expression was not restricted to a single cell type.

### 4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3–5 sentences.

Yes. The observed expression pattern is biologically reasonable because GALT encodes galactose-1-phosphate uridylyltransferase, an enzyme involved in the Leloir pathway of galactose metabolism. Unlike a gene whose function is specific to one cell type, a metabolic enzyme may be expressed in multiple types of cells because cells require metabolic pathways for normal cellular functions. GALT deficiency causes classic galactosemia because impaired GALT activity disrupts galactose metabolism and can result in the accumulation of galactose-related metabolites. Therefore, the broad but generally low expression pattern observed in the epidermal dataset is consistent with GALT being a metabolic gene rather than a cell-type-specific marker.

### 5. Can this single Cell Browser dataset prove that the gene causes the disease? Explain why or why not.

No. A single Cell Browser dataset cannot prove that **GALT causes classic galactosemia** because the dataset mainly provides information about gene expression across cells. The detection of GALT expression shows where the gene is expressed in the selected tissue, but expression alone does not establish disease causation. Genetic, clinical, biochemical, and functional evidence is required to establish that pathogenic GALT variants cause classic galactosemia.



# Reflection

### 1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?

The UCSC Cell Browser showed me how **GALT expression varies among individual cells and cell types** in the human epidermis dataset. In comparison, the UCSC Genome Browser helped me examine the genomic location, gene structure, and sequence information of GALT. Using both browsers allowed me to understand GALT from both the genomic and cell-expression perspectives.

### 2. Why can the same gene have different expression levels among different cell types?

The same gene can have different expression levels because different cell types perform different functions and therefore regulate genes differently. A gene may be highly expressed in cells where its function is particularly important, while its expression may be low or undetected in other cells. This regulation allows cells to maintain their specific functions.

### 3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?

Zero or very low expression in single-cell data does not always mean that the gene is completely absent or inactive in that cell type. The transcript may be present at a level below the detection limit, or the RNA molecule may not have been captured during the experiment. Therefore, zero or low expression values should be interpreted carefully.

### 4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?

Combining genomic location, genetic variants, and cell-specific gene expression provides a more complete understanding of a disease-associated gene. Genomic information shows where the gene and variant are located, while mutation analysis shows how a sequence change may affect the protein. Cell-specific expression provides information about the cells in which the gene is detectable. Together, these results help connect a genetic variant with its possible biological and cellular consequences.

### 5. What was the most interesting observation you made about your assigned gene?

What interested me most was that **GALT was not strongly restricted to one cell type in the human epidermis dataset**. Instead, detectable expression was distributed across several cell populations, while most cells showed zero or low expression. This helped me understand that a disease-associated gene does not necessarily behave like a cell-type marker. The result also made sense because GALT functions as a metabolic enzyme involved in galactose metabolism rather than as a gene with a function limited to one specific cell type.



# References

1. Cheng, J. B., Sedgewick, A. J., Finnegan, A. I., Harirchian, P., Lee, J., Kwon, S., Fassett, M. S., Golovato, J., Gray, M., Ghadially, R., Liao, W., Perez White, B. E., Mauro, T. M., Mully, T., Kim, E. A., Sbitany, H., Neuhaus, I. M., Grekin, R. C., Yu, S. S., Gray, J. W., Purdom, E., Paus, R., Vaske, C. J., Benz, S. C., Song, J. S., & Cho, R. J. (2018). Transcriptional programming of normal and inflamed human epidermis at single-cell resolution. *Cell Reports, 25*(4), 871–883. https://doi.org/10.1016/j.celrep.2018.09.006

2. National Center for Biotechnology Information. (2026). *GALT galactose-1-phosphate uridylyltransferase [Homo sapiens]*. NCBI Gene. https://www.ncbi.nlm.nih.gov/gene/2592

3. Berry, G. T. (2021). Classic galactosemia and clinical variant galactosemia. In M. P. Adam, S. Bick, G. M. Mirzaa, et al. (Eds.), *GeneReviews®*. University of Washington, Seattle. https://www.ncbi.nlm.nih.gov/books/NBK1518/

4. UCSC Cell Browser. (n.d.). *Normal and Inflamed Human Epiderm
