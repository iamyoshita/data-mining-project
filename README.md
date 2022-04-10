# data-mining-project

SubmitPMIDList.py is the code for annotating based on pmid.

Had to compress the txt file from pubmed as it was >25mb.

Converted the 10000 abstracts from txt to csv file "woundabstracts.csv". So the first cell in jupyter can be commented. (don't comment the libraries)

must execute "conda install -c conda-forge spacy-model-en_core_web_sm" to install spacy package.

Tried using gensim and checked similary of "wound" with different proteins,genes. Then checked the similarity between those proteins and genes.

try1 is the jupyter file. The red marked text in the output are not errors but just time log. 


I tried with just 10k abstracts for now. And the parameters must be tuned.

todo: try with bigrams also. use phrases library for that
