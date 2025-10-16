# Opera Graeca Adnotata v0.2.0

This repository contains an open access and scalable annotated collection
of Greek texts, **Opera Graeca Adnotata** (base texts: 1,999 files
and 40,105,221 tokens) 🏋️❤️😃.

Because of the large corpus size, the data are made available on Zenodo.
Updates are given on:

* https://github.com/OperaGraecaAdnotata/OGA/

The original Greek texts
have been tokenized, sentence-segmented, and morphosyntactically
annotated using a standoff format (PAULA XML),
which allows for smooth expansion of the
corpus via addition of any kind of annotation layer.

The repository is organized as follows (further details within each folder):
1. `abbreviations` contains a file useful for tokenization.
2. `annotation_example` contains an unzipped example of the
annotation layers, which is useful for inspection (given that all other files
are zipped for space reasons).
3. `workspace/conllu` contains the texts morphosyntactically annotated in CoNLL-U format.
4. `workspace/ellipsis` contains the texts with ellipsis annotation (see https://aclanthology.org/2023.icnlsp-1.15/).
5. `workspace/oga/laula` contains the texts tokenized with references to the original
Greek files. This folder is useful only if you need to link tokens to the paratext of
the original Greek files.
6. `workspace/merge` contains the files of `original-Greek-files` after normalization.
7. `original-Greek-files` contains the original TEI XML texts.
8. `workspace/oga/oga_v0.2.0_{1..5}` contain the texts in the PAULA XML format
(divided into 5 directories). This is the data you want to query.
9. `graphannis` contains files in the format that ANNIS 4 understands. You
can download ANNIS 4.12.3 (or later version) and use the data in this folder 
to query the corpus on your desktop computer.
10. `tokenize` and `elision` contain files used for tokenization
11. `urn_cts` contains files with bibliographic information about the texts.
12. `work_chronology` contains a manually annotated file with
the alleged composition dates of Greek works, 
which continues to be updated (check the GitHub repository above).
13. `query` contains documentation to query the corpus.

## Citation

If you use OGA v0.2.0 or material within this repository, please cite it thus
(the following article describes an earlier version of OGA, i.e., v0.1.0, but
is still relevant):

```
Giuseppe G. A. Celano. Opera Graeca Adnotata: Building a 34M+ Token Multilayer Corpus for Ancient Greek. arXiv https://arxiv.org/abs/2404.00739.
```

```
@misc{celano2024operagraecaadnotatabuilding,
      title=         {Opera Graeca Adnotata: Building a 34M+ Token Multilayer Corpus for Ancient Greek}, 
      author=        {Giuseppe G. A. Celano},
      year=          {2024},
      eprint=        {2404.00739},
      archivePrefix= {arXiv},
      primaryClass=  {cs.CL},
      url=           {https://arxiv.org/abs/2404.00739}, 
}
```
Direct citation of the corpus is: 

```
Giuseppe G. A. Celano. 2024. Opera Graeca Adnotata (v0.2.0). Zenodo.
https://doi.org/10.5281/zenodo.14206061
```

```
@misc{celanoOGA020,
author =    {Giuseppe G. A. Celano},
title =     {Opera Graeca Adnotata},
year =      {2024},
publisher = {Zenodo},
version =   {v0.2.0},
doi =       {10.5281/zenodo.14206061},
url =       {https://doi.org/10.5281/zenodo.14206061}
}
```
## Contact
Dr. Giuseppe G. A. Celano<br/>
Universität Leipzig<br/>
Institute of Computer Science, NLP<br/>
Augustusplatz 10<br/>
04109 Leipzig<br/>
Deutschland<br/>
*mysurname* at informatik.uni-leipzig.de<br/>

## Funder

<a href="http://www.dfg.de/index.jsp" target="_blank">
<img src="https://upload.wikimedia.org/wikipedia/commons/8/86/DFG-logo-blau.svg" 
width="" height="40" alt=""/>
</a>

(Project number: 408121292)

## Licence

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" 
src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br/>
This work is licensed under a <a rel="license" 
href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a> (for more
details, look also at the repositories of the original texts mentioned above).
