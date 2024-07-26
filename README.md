# devilWASTE Study - Quality Control and Data Analysis Artifacts

This repository contains the QIIME2 artifacts and scripts used in the quality control and data analysis of the devilWASTE study (title: 'Microbial Ecology and Metabolism of Emerging Adulthood: Gut Microbiome Insights from a College Freshman Cohort'), which examines the gut microbiome composition and function in a cohort of college freshmen during an academic year. These files are provided to enhance transparency and reproducibility of our methods, in line with the feedback from reviewers.

## Contents

### Quality Control Artifacts

1. **Demultiplexed Sequence Quality Visualizations**
   - `demux_seqs_run1.qzv`
   - `demux_seqs_run2.qzv`
   - `demux_seqs_run3.qzv`
   
   These files provide quality plots of the demultiplexed sequences for each of the three sequencing runs. They allow assessment of base quality scores across all reads.

2. **Denoising Statistics**
   - `denoising_stats_run1.qzv`
   - `denoising_stats_run2.qzv`
   - `denoising_stats_run3.qzv`
   
   These files summarize the denoising process for each run, including the number of reads that passed each filtering step.

3. **Merged Feature Table Summary**
   - `merged_table.qzv`
   
   This visualization provides an overview of the merged feature table, including the number of features observed in each sample and the overall distribution of feature counts.

4. **Merged Representative Sequences Summary**
   - `merged_rep_seqs.qzv`
   
   This file provides a summary of the representative sequences from the merged sequencing runs.

### Scripts and Batch Files

5. **Quality Control and Analysis Scripts**
   - `devilWASTE_quality_control_and_analysis.ipynb`
   
   This Jupyter notebook includes the scripts used for quality control, denoising, and merging of sequencing data using QIIME2.

## Usage

To view the QIIME2 visualizations, you can use the `qiime tools view` command. For example:

```bash
qiime tools view demux_seqs_run1.qzv
qiime tools view denoising_stats_run1.qzv
qiime tools view merged_table.qzv
qiime tools view merged_rep_seqs.qzv
```

### License
This repository is licensed under the MIT License.

### Contact
For any questions or further information, please contact aemohr@asu.edu.
