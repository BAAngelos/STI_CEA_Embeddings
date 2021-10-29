# STI_CEA_Embeddings
Several files that create a subset of the T2D dataset and run a CEA approach on them

###### The only important file is "T2D; subprocess 1 and 2 aswell as evaluating results.ipynb"

it creates all other dataset e.g. "complete_tables" and "embeddingCorrespondence"
    For that it asumes the entity-level T2D files to be in directory:
    \data\Tables\Goldstandard\tables_instance\
    
First create complete_tables then out of those you can create embeddingsCorrespondence

This file also generates the baseline results, the embeddings result aswell as evaluating them for the T2D datasets
