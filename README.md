# biocomp1

Project 1: Beginner - "Venom Component Profiling of a Well-Characterized Species"

Scientific Question: What are the major protein families in the venom of the Indian Cobra (Naja naja)?


Concept: This project teaches you the fundamentals: fetching data, running a basic similarity search, and functional annotation. It's the "Hello, World!" of toxinology.

Methodology:
Data Acquisition: Use Biopython's Entrez module to programmatically search UniProtKB/Swiss-Prot for all reviewed proteins associated with Naja naja and the keyword "venom". Save these as a FASTA file.
Functional Annotation: For each protein sequence you downloaded, use Python to send a request to the Pfam or InterPro web API to identify its functional domains. (Alternatively, you can download command-line versions of these tools).


Analysis & Visualization:
Parse the results from your annotation search.
Use pandas to count the occurrences of each toxin family (e.g., Three-finger toxin, Snake venom metalloproteinase, Phospholipase A2).
Use matplotlib or seaborn to create a pie or bar chart showing the relative abundance of each family.
Skills Showcased: Database querying (API usage), file parsing (FASTA), basic functional annotation, data aggregation (pandas), and scientific visualization (matplotlib).
