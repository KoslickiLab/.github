### Here we lists out data for shared dir



Last update: 2025.4.24

Shared folder in our servers:

1. CPU: `/data/shared_data`
2. GPU: `/data/shared_data` and `/scratch/shared_data_new`



Note:

1. there might be scripts inside the folder, so please take a look before deleting the folder and try to back them up



| Data source    | Description                                                  | Server                                           | Folder                                                       | Last update                                                  | Who                                                          |
| -------------- | ------------------------------------------------------------ | ------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| KEGG           | 1. KEGG KO sequences and sketches from its FTP data          | CPU                                              | /data/shared_data/cleaned_KEGG_FTP_2022_NOV                  | 2023.2.21                                                    | Shaopeng                                                     |
|                | 2. raw KEGG FTP data                                         | GPU                                              | /scratch/shared_data/KEGG_FTP                                | 2023.5.19                                                    | David                                                        |
|                | 3. KEGG KO hierarchy information                             | GPU                                              | /scratch/shared_data/KEGG_KO_hierarchy                       | 2023.5.19                                                    | David                                                        |
|                | 4. Sketching annotation                                      | CPU                                              | /data/shared_data/Kegg_sketching_annotation                  | 2023.1                                                       | David                                                        |
| GTDB           | 1. GTDB rep r207<br />2. GTDB rep r214<br />3. GTDB rep r207<br />4. GTDB all r220<br />5. GTDB all r226<br />6. GTDB rep version unkonwn | GPU<br />GPU<br />CPU<br />CPU<br />CPU<br />CPU | /scratch/shared_data/GTDB<br />/scratch/shared_data_new/GTDB<br />/data/shared_data/GTDB<br />/data/shared_data/GTDB_r220<br />/data/shared_data/GTDB_r226<br />/data/shared_data/GTDB_REP | 2023.5.19<br />2025.3.19<br />2024.9<br />2024.10<br />2025.4<br />2022.5 | David<br />David<br />Shaopeng<br />Shaopeng<br />Shaopeng<br />Adam |
|                | 2. Sourmash sketching for GTDB r207                          | GPU                                              | /scratch/shared_data/sourmash_data                           | 2023.5.19                                                    | David                                                        |
| LOGAN          | All ref genomes and k-mer sketches                           | GPU<br />GPU<br />CPU                            | /scratch/shared_data_new/Logan_yacht_data<br />/scratch/shared_data/LOGAN_YACHT_microbe (sig only)<br />/data/shared_data/LOGAN_YACHT_microbe (sig only) | 2025.3.28<br />2024.10.3<br />2024.10                        | David<br />Shaopeng<br />Shaopeng                            |
| GenBank        | genomes                                                      | CPU                                              | /data/shared_data/GenBank_genomes                            | 2022.4                                                       | Shaopeng                                                     |
| HMP            | Gut metagenomics<br />Skin metagenomics                      | CPU<br />CPU                                     | /data/shared_data/HMP_Gut_WGS_data<br />/data/shared_data/HMP_Skin_WGS_data | 2024.10<br />2023.10                                         | Shaopeng<br />Wei Wei                                        |
| BV-BRC         | Genomes                                                      | CPU                                              | /data/shared_data/BV-BRC_genomes_2024.9                      | 2024.9                                                       | Shaopeng                                                     |
| Metagenomic-KG | Graph and support files                                      | GPU<br />CPU<br />CPU                            | /scratch/shared_data_new/metagenomics_graph<br />/data/shared_data/MetagenomicKG (Graph file)<br />/data/shared_data/metagenomics_graph (all files) | 2024.3.12<br />2024.2<br />2023.9                            | Chunyu<br />Chunyu<br />Chunyu                               |
| RTX-KG2        | Local deployment of RTX-KG2 database                         | GPU                                              | /scratch/shared_data/neo4j-community-3.5.26                  | 2023.5.19                                                    | Chunyu                                                       |









