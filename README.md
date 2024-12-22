NCBI human genome for use with datalab: GRCh38 major, pipeline ready, full analysis.
To extract and rename index files for BWA, run
```bash
tar --transform='s/GCA_000001405.15_GRCh38_full_analysis_set/genome_grch38/' -xvzf genome_grch38.fna.bwa_index.tar.gz
```

For more details, see  [NCBI README](https://ftp.ncbi.nlm.nih.gov/genomes/all/GCF/000/001/405/GCF_000001405.26_GRCh38/GRCh38_major_release_seqs_for_alignment_pipelines/README_analysis_sets.txt).
