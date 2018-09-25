



##dir
1. enhancer : download from the rick Master transtription 2013 
2. gene_body : download form ensemble [gff file](ftp://ftp.ensembl.org/pub/release-93/gtf/mus_musculus/Mus_musculus.GRCm38.93.gtf.gz) gene长度大于3、5、10、30、50kb，TSS下游1kb, TTS上游1k
3. insulator : CTCF binding site(下载Bing Ren cis-regulatory 2012 nature) 去掉 TSS, enhancer
4. TSS : gene长度大于3、5、10、30、50kb，TSS上下游1kb
5. TTS : gene长度大于3、5、10、30、50kb，TTS上下游1kb
6. pre_f : the difine before

##file
	final_gene_element3k.bed 选出长度大于3K的基因
	final_gene_element5k.bed 选出长度大于5K的基因 
	final_gene_element10k.bed 选出长度大于10K的基因
	final_gene_element30k.bed 选出长度大于30K的基因
	final_gene_element50k.bed 选出长度大于50K的基因

	promoter.bed 所有基因的promoter

##gene 类别和数目

	Coding genes	22,628 (incl 265 readthrough)
	Non coding genes	15,695
	Small non coding genes	5,531
	Long non coding genes	9,602 (incl 65 readthrough)
	Misc non coding genes	562
	Pseudogenes	12,763 (incl 5 readthrough)
	Gene transcripts	136,630

