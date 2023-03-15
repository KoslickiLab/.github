## Note for shared folder in CPU and GPU server

Last update: 2023.3.15

Location for both server: `/data/shared_data`



1 for the CPU server, 2 for the GPU server

| Data source | Description                                                  | Server | Folder                    | Last update | Who      |
| ----------- | ------------------------------------------------------------ | ------ | ------------------------- | ----------- | -------- |
| KEGG        | 1. KEGG KO sequences and sketches from its FTP data          | 1      | cleaned_KEGG_FTP_2022_NOV | 2023.2.21   | Shaopeng |
|             | 2. raw KEGG FTP data                                         | both   | KEGG_FTP                  | 2023.2.17   | David    |
|             | 3. KEGG KO hierarchy information                             | 2      | KEGG_KO_hierarchy         |             | Chunyu   |
| GTDB        | 1. GTDB rep genomes r207                                     | both   | GTDB                      |             |          |
|             | 2. Sourmash official sketching for GTDB                      | 2      | sourmash_data             |             |          |
| HMP         | Human Microbiome Project gut metagenomic sequences           | 1      | HMP_Gut_WGS_data/         |             | Shaopeng |
| Pathogen-KG | Collection of pathogen-related database and gene-related database (unfinished) | both   | metagenomics_graph/       |             | Chunyu   |
|             | Downloading PATRIC database (will merge to folder above)     | 2      | PATRIC/                   |             | Shaopeng |
| RTX-KG2     | Local deployment of RTX-KG2 database                         | 2      | neo4j-community-3.5.26    |             | Chunyu   |

