# Flye

####  Read Assembly
- **Why Perform Assembly?**: Once reads are cleaned and filtered, genome assembly is performed to reconstruct the entire genome or transcriptome from the sequencing reads. This process is especially crucial for de novo assemblies, where a reference genome is not available.

 **Tool (Long Reads)**: Flye (for assembling long reads)
  - **Installation**:
    ```bash
    conda install -c bioconda flye
    ```
  - **Usage**:
    ```bash
    flye --nano-raw input.fastq --out-dir output_directory
