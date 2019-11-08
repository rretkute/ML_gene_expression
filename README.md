# ML_gene_expression
Mathematica notebook to compare methods of machine learning for ribosom density on mRNA prediction (without redundant nucleotide features).

The outcome of "Growth and division in mathematics and medicine: A collaborative incubator" workshop
https://www.homepages.ucl.ac.uk/~ucakwat/gd.html

#### Data 
Dao Duc K, Song YS. The impact of ribosomal interference, codon usage, and exit tunnel interactions on translation elongation rate variation. PLoS Genet. 2018 Jan 16;14(1):e1007166. doi: 10.1371/journal.pgen.1007166 https://journals.plos.org/plosgenetics/article?id=10.1371/journal.pgen.1007166

#### Methods 
Tunney R, McGlincy NJ, Graham ME, Naddaf N, Pachter L, Lareau LF. Accurate design of translational output by a neural network model of ribosome distribution. Nat Struct Mol Biol. 2018 Jul;25(7):577-582. doi: 10.1038/s41594-018-0080-2. https://www.nature.com/articles/s41594-018-0080-2

#### Results
Number of genes for training n=567, number of genes for testing m=283. 

| Method  | "NeuralNetwork"  |"LinearRegression"   | "RandomForest" |  "NearestNeighbors"  |
|---|---|---|---|---|
|  Pearson correlation |  0.496767 |  0.43612 | 0.392796  |  0.307008 |

