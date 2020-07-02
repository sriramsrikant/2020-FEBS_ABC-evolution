# 2020-FEBS_ABC-evolution
Collection of files and Jupyter lab notebooks written to extract ABC protein domains from proteomes. Performed for FEBS review.

### Content:
1. notebooks - Folder of Jupyter lab notebooks that contain all the sequence extraction, alignment, tree construction and plotting for the FEBS review.
2. RefSeq - Folder of proteomes (FASTA files) from UniProt to represent species across the tree of life and that are reference proteomes from the UniProt database.
3. Pfam - Folder of seed alignments and HMM profiles of Pfam families that are contained in known ABC proteins.
4. dictionary - Folder of CSV files that contain all the metadata from Pfam and UniProt databases for the relevant Pfam families and species proteomes that are saved in the corresponding folders.

### Python Packages Needed
Check the first code-cell in the python notebook for all python packages that are imported and used for the analysis.

### Dependencies
The python notebooks here depend on the following 3rd party binaries and their licences must be respected.
1. HMMER v3.3 (http://hmmer.org/)
2. EASEL 0.46 - installed with HMMER commandline tools (https://github.com/EddyRivasLab/easel)
3. FastTree 2.1.10 (No SSE3) (http://www.microbesonline.org/fasttree/)
