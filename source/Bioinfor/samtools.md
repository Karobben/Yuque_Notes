---
title: "samtools"
description: "samtools"
url: samtools
---

# samtools

# Quick start
```bash
samtools tview sorted.bam Trinity.fasta   -p "ID:35" -d T > result

samtools tview sorted.bam ../../2-Trinity/Trinity.fasta   -p "comp0_c0_seq1:35" -d H > 123.html
```
```
*.bam file *.fasta file  -p  posation, fasta name and star posation of the fasta :
```
# Sorting by bam files
```bash
samtools sort bwa.bam -o bwa.sorted.bam > bwa.sorted.bam
```

# Index
```bash
samtools faidx genome.fna
```

---
github: [https://github.com/Karobben](https://github.com/Karobben)
blog: [Karobben.github.io](http://Karobben.github.io)
R 语言画图索引: [https://karobben.github.io/R/R-index.html](https://karobben.github.io/R/R-index.html)
