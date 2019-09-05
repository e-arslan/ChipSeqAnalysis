# Paper

* **Title**: Functional Dissection of the Enhancer Repertoire in Human Embryonic Stem Cells
* **Authors**: Barakat et al.
* **Tags**: Normalization, Pooling
* **Year**: 2018
* **Rating**: 4/10

#### Novel Points
* Authors use a combination of chromatin immunoprecipitation and a massively parallel reporter assay to identify functional enhancers in primed and naive human embryonic stem cells.

* We find that TF binding is linked with enhancer activity, in line with recent reports (Kwasnieski et al., 2014; Ernst et al., 2016; Kheradpour et al., 2013), but that no individual TF, histone mark or combination thereof could unequivocally predict enhancer activity.

* Our study identified a previously unrecognized group of functional enhancers that are active in ESCs but are associated with generic cell processes. This extended enhancer module is characterized by reduced binding of pluripotency- associated TFs and histone marks. This reduced binding might have placed these regions below the detection threshold in pre- vious ChIP-seq-based studies that lacked a functional readout.
#### How can I use for my further analysis?

* Most enhancers studied to date lie within distal elements or in- tronic sequences. However, some sequences detected by ChIP- STARR-seq lie near TSSs (n = 3,283 active enhancers within 500bp of a TSS).

#### Data Analysis
* motif enrichment analysis using CentriMo (http://meme-suite.org/) 

* We used GREAT, version 3.0.0 (McLean et al., 2010) to assign regulatory elements identified in ChIP-STARR-seq to their putative target genes, using the following settings: basal plus extension, proximal 5kb upstream and 1kb downstream, plus distal up to 100kb.

* We used LOLA (Sheffield and Bock, 2016) to determine the relative over-representation of ChIP-seq peaks related transcrip- tion factor binding and other elements of known regulatory function. 

* We also used the Enrichr API (January 2018 version) (Chen et al., 2013) to test genes linked to enhancers of interest for sig- nificant enrichment in numerous functional categories. 

#### Available data
http://www.medical-epigenomics.org/papers/barakat2018/


#### Learned biological concepts
* Enhancer function requires transcription factor (TF) binding and corre- lates with histone modifications.
* Human embryonic stem cells (ESCs) 
* with self-transcribing active regulatory region sequencing (STARR-seq) compact, non-mammalian genomes can be quantitatively screened for enhancer activity by cloning randomly sheared DNA between a minimal-promoter-driven GFP open reading frame and a downstream polyA sequence.
