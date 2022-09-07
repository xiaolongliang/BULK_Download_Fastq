# Bulk download raw FASTQ file from ENA database
## Usage
- Input  
The Input file explained in **example.md**
- Run    
```shell
sh DownFASTQfromENA_GeneralizeFiles.sh filereport_read_run_PRJNA624020_tsv SraRunTable 20
```
> filereport_read_run_PRJNA624020_tsv: Fq list  
> SraRunTable: BREED information    
> 20: CPU   

- Output   
This script will bulk download Fastq and generalize Fq based on BREED
