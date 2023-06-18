Accessing, exploring and using the publicly available databases and national sequence archives for clinical microbiologists
============================================================================================================================


Course-specific information:

Part 1
========
- <https://www.ncbi.nlm.nih.gov/>

### BLASTN KPC-2 nucleotide sequence (AY034847.1) against KPC-3 carrying plasmid (CP074540.1)
- <https://blast.ncbi.nlm.nih.gov/Blast.cgi?PROGRAM=blastn&PAGE_TYPE=BlastSearch&BLAST_SPEC=&LINK_LOC=blasttab&LAST_PAGE=tblastn>
- click the "Align two or more sequences" box.
- enter AY034847.1 in the "Enter Query Sequence" window and CP074540.1 in the "Enter Query Sequence" window.

### TBLASTN KPC-2 protein sequence (AAK70220.1) against KPC-3 carrying plasmid (CP074540.1)
- <https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=Translations&PROGRAM=tblastn&BLAST_PROGRAMS=tblastn&PAGE_TYPE=BlastSearch&BLAST_SPEC=blast2seq&DATABASE=n/a&QUERY=&SUBJECTS=>
- click the "Align two or more sequences" box.
- enter AAK70220.1 in the "Enter Query Sequence" window and CP074540.1 in the "Enter Query Sequence" window.

### TBLASTN KPC-2 protein sequence (AAK70220.1) against KPC-2 carrying plasmid (MN842292.1)
- <https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=Translations&PROGRAM=tblastn&BLAST_PROGRAMS=tblastn&PAGE_TYPE=BlastSearch&BLAST_SPEC=blast2seq&DATABASE=n/a&QUERY=&SUBJECTS=>
- click the "Align two or more sequences" box.
- enter AAK70220.1 in the "Enter Query Sequence" window and MN842292.1 in the "Enter Query Sequence" window.
- Note multiple hits; links out to GenBank display

### Compare KPC-2 (AAK70220.1) to KPC-8 (ACI95258.1)
- <https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE=Proteins&PROGRAM=blastp&BLAST_PROGRAMS=blastp&PAGE_TYPE=BlastSearch&BLAST_SPEC=blast2seq&DATABASE=n/a&QUERY=&SUBJECTS=>
- GenBank page for KPC-8: 
- <https://www.ncbi.nlm.nih.gov/search/all/?term=ACI95258.1>
- <https://www.ncbi.nlm.nih.gov/protein/WP_063860797.1>
- Identical Proteins page:
- <https://www.ncbi.nlm.nih.gov/ipg/WP_063860797.1>

### Additional Microbial Related Resources
- NCBI SARS-CoV-2 Resources: <https://www.ncbi.nlm.nih.gov/sars-cov-2/>
- NCBI Virus: https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/
- NCBI Outreach Events (videos that cover many NCBI resources: <https://ncbiinsights.ncbi.nlm.nih.gov/ncbi-outreach-events/>

Part 2
=======

- <https://www.ncbi.nlm.nih.gov/pathogens/>

### Isolates Browser Exercises

- <https://www.ncbi.nlm.nih.gov/pathogens/>
- How would you find the recent blaVIM Pseudomonas outbreak?
<https://www.ncbi.nlm.nih.gov/pathogens/>

### Searching AMR Data, Isolates Browser

- [AMR\_genotypes\_core:blaKPC-2](https://www.ncbi.nlm.nih.gov/pathogens/isolates/#AMR_genotypes_core:blaKPC-2)
- [AMR\_genotypes\_core:blaKPC\*](https://www.ncbi.nlm.nih.gov/pathogens/isolates/#AMR_genotypes_core:blaKPC*)
- [AST_phenotypes:\*penem=R AND NOT AMR\_genotypes:bla\*](https://www.ncbi.nlm.nih.gov/pathogens/isolates/#AST_phenotypes:*penem=R%20AND%20NOT%20AMR_genotypes:bla*)

### Searching AMR data, MicroBIGG-E

- <https://www.ncbi.nlm.nih.gov/pathogens/microbigge/>
- [genes\_on\_contig:blaTEM-1 AND genes\_on\_contig:blaKPC-4](https://www.ncbi.nlm.nih.gov/pathogens/microbigge/#genes_on_contig:blaTEM-1%20AND%20genes_on_contig:blaKPC-4)
- [subclass:QUINOLONE AND subtype:POINT](https://www.ncbi.nlm.nih.gov/pathogens/microbigge/#subclass:QUINOLONE%20AND%20subtype:POINT)

### Exercise

- Can you find unnamed/uncharacterized blaKPC alleles? 
    - https://www.ncbi.nlm.nih.gov/pathogens/microbigge
    - Are they full length?

- Find enoki mushroom isolates in the isolates browser
    - <https://www.ncbi.nlm.nih.gov/pathogens/isolates>
    - Are there clinical cases linked?
    - What does the metadata look like (esp. isolation source, IFSAC category, collection date)?

## Additional Resources

- [NCBI Pathogen Detection Documentation](https://www.ncbi.nlm.nih.gov/pathogens/pathogens_help/)
- [NCBI Minute: Introduction to NCBI Pathogen Detection and antimicrobial resistance data in Google BigQuery](https://ncbiinsights.ncbi.nlm.nih.gov/event/ncbi-pathogen-detection-in-cloud-03-2023/) - YouTube Video about accessing Pathogen Detection data on Google Cloud.
- Our [How To page](https://www.ncbi.nlm.nih.gov/pathogens/docs/HowTo/) - Short PDFs with screen shots for how to do some simple tasks with our interface


## Questions or comments

Please email us at pd-help @ ncbi.nlm.nih.gov

-----------------------------------------------------------------------------------------------
This work was supported in part by the National Center for Biotechnology Information of the National Library of Medicine (NLM), National Institutes of Health, as well in part by the National Institute of Allergy and Infectious Diseases,
National Institutes of Health

