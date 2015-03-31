# Phylogenetics
Aphonopelma sp. (american tarantula) phylogeny

###Sequence Alignment of Raw Data
-Sequence data in Fasta format downloaded from NCBI Blast: nucleotide search of Aphonopelma. All 1245 sequences were obtained. File renamed to Aphonopelma_Raw_Fasta_1245seq.fasta. Also created a copy in .txt format. 
-Raw data contains 1245 sequences
-all sequence lengths >= 900bp


#Downloaded but Need to instal ClustalW
-Online versions restrict number of sequences and file size

##To do:
####ClustalW2 Alignment Parameters
#####Pairwise Alignment
*Fast Alignment* (uses Wilbur & Lipman method): for alignments containing >100 sequences of length >1000 bp.

|Settings             | Value    |
|:--------------------|:---------|
|KTUP                 | 1        |
|Window lenght        | 5        |
|Score Type           | Percent  |
|TopDiag              | 5        |
|PairGap              | 3        |
(Default Settings)

#####Multiple Alignment

|Settings             | Value    |
|:--------------------|:---------|
|DNA Weight Matix     | IUB      |
|Gap Open             | 10       |
|Gap Extension        | 0.20     |
|Gap Distances        | 5        |
|No End Gap           | no       |
|Iteration            |none      |
|Num Iteration        |1         |
|Clustering           |NJ        |
|Output Format        |Nexus     |
|Output Order         |aligned   |

