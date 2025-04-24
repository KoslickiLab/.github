# Shaopeng Liu's Documents on Servers

### All files in CPU server 172.29.195.30:

Total size: `5T`

1. `/scratch2/sml6467/temp`: this folder hosts separate analysis in MKG projects, keep it:
   1. `assign_gtdb_id_for_genomes`: GDTB-tk run notes, this is covered in the MKG readme
   2. `AMR`: trial run for AMR annotation
   3. `subsample_kg`: subsample MKG 
2. `/scratch2/sml6467/project/archive`: old projects
   1. `20210130_CAMISIM_errorfree_simulation`: CAMISIM error free simulation
   2. `20210705_point_mutation_ecoli_permutation_ANI_JI`: how point mutation affect ANI and JI
   3. `20210525_Assembly_exploration`: part of exploration for MDM 
3. `/scratch2/sml6467/project`: 
   1. `kegg_functional_profile_HMP`: benchmark analysis for the `fmh-funcprofiler` manuscript.
   2. `ers_benchmark6_on_human_genome`: ERS-mer benchmark
   3. `fmh_vs_syncmer`: FMH_syncmer manuscript benchmark 





### All file in GPU server 10.136.74.2:

Total size: `200G`

1. `/home/grads/sml6467`: this folder is almost empty except those default config folders. Please keep it there if Shaopeng is going to use this server in the future, o.w. can remove it.
2. `/scratch/sml6467.zip`: this zip back up was made in 2023.5 by Professor. It's out of date and can be removed.
3. `/scratch/sml6467` : this is the main working dir, please **DO NOT delete files here unless** you're sure those files are not further needed. 
4. Here lists important folders:
   1. `/scratch/sml6467/projects`:
      1. `check_generic_drugs_RTX_KG2`: manual annotation for generic drugs in RTX-KG2
      2. `compare_shortbred_lefse`: benchmark test for abundance differential analysis tools `shortbred` and `lefse`. Some scripts seems missing here, I do remember the conclusion that we decided to use `lefse` in our `fmh-funcprofiler` project.
      3. `pilot_twin_KO_dif_DEG`: compare KO degs for twin data. Some scripts seems missing here. The conclusion then was: I didn't find significant signals so didn't go further with this idea.
      4. `MKG_benchmark`: **benchmark analysis for the MKG manuscript**
      5. `fmh_sync_repro`: benchmark analysis for the fmh-vs-syncmer manuscript
   2. `/scratch/sml6467/github`:
      1. `Koslicki_lab_metagenomic_analysis`: analytical results for all projects.



### Github repository in KoslickiLab

Here lists repos solely by Shaopeng. 

| Name                                                         | Status   | Note                                                         |
| ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| [CMASH-reproducibles](https://github.com/KoslickiLab/CMASH-reproducibles) | Finished | Reprodicible analysis for the CMash manuscript               |
| [Koslicki_lab_metagenomic_analysis](https://github.com/ShaopengLiu1/Koslicki_lab_metagenomic_analysis) | Finished | Here are some small analytical tasks for metagenomics        |
| [Strobemer_extension](https://github.com/KoslickiLab/Strobemer_extension) | Wait     | Benchmark analysis for Strobemer + k-mer trunction. It's promising, now wait for further results from the project below. |
| [FMH_vs_syncmer_reproducible](https://github.com/KoslickiLab/FMH_vs_syncmer_reproducible) | Wait     | This is the repo for [an arXiv article](https://www.biorxiv.org/content/10.1101/2023.11.09.566463v1.full). The results here are important for the seed analysis above. **I'm trying to finish this work**. |
| [CMash_Rust_implementation](https://github.com/KoslickiLab/CMash_Rust_implementation) | Archive  | A plan to implement CMash by Rust for speeding purpose. But now we shifts to `FracMinHash` so this wouldn't be further tried. |
| **[Microbial_dark_matter_explore](https://github.com/KoslickiLab/Microbial_dark_matter_explore)** | Archive  | A plan to pursue MDM by sketching-based methods. **I didn't make it in my thesis, but this would worth pursuing**. |




