# Tay_Sachs_Disease
CRISPR-PE pegRNA design for Tay Sachs Disease
Hi, 


Tay sachs is a neurological disease which contains mutations of HEXA gene and Beta- hexosaminidase enzyme is encoding by this gene. Many different mutations are shown by HEXA gene such as insertion, deletion and etc. In this study, i'm focusing on CRISPR-Prime Editing guide RNA (pegRNA) designing for 5 different closer mutations in HEXA gene. These mutations are c492T>C [VCV001093316.1], c496del [VCV000984491.1] ,c.497G>A [VCV000093192.5]  , c499T>G [VCV000992196.1], c508C>T [VCV000003925.7] and c509G>A[VCV000003900.6]. Firstly, I aimed to same pegRNA spacer zone to use all pegRNA sequences for these pathogenic mutations but distance of c590G>A between c492T>C mutations was a restrictive factor for this situation. Therefore, similarity between pegRNA spacer sequences was determined approximately %90. Also, i used biopyhton tools as Bio.Seq, py3Dmol and SeqIO. Finally, i planned to all these CRISPR systems delivering by Lentiviral vectors and Vector map is given in figure. 


Contents of this work:
1) Upload and read sequence of HEXA gene with fasta file format. 
2) Determine of HEXA gene length and frequency of nucleotides.
3) Shown of target mutations zone. 
4) Design of CRISPR pegRNA sequences.
5) Calculate of AT and GC content ratio.
6) Visualizing of Beta- hexoaminidase enzyme with 3D structure. 


![image](https://user-images.githubusercontent.com/93882749/156577882-302ad591-e205-453c-92cf-0afa5681e0ef.png)
