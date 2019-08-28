# ChipSeqAnalysis

Transcription of DNA to RNA is regulated by the Chromatine Immuno Precipitation binding of elements. 

These can be Transcription Factors, that bind temporarily to start transcription, but also chemical modification of the histones (molecular structures that coil the DNA) by methylation, acetylation, etc. 

![Examples](Images/IntAnalysis_ChIPSeq_Transcription.png)


* Some experiments can be analyzed with the MACS2 algorithm. This version can detect narrow (like transcription factors) or broad (like histone modifications).

* Yet another algorithm is RSEG; it is especially designed for histone modification detection. In R2 this used to analyse the histone modification patterns. To distinguish between specific histone modifications (e.g. acetylation vs methylation), R2 allows you to assess the same region in two profiles.