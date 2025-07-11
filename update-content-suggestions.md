### [LOGISTICS] adding user to linux systems

```
sudo useradd -m -s /bin/bash <userName>
sudo passwd <userName>
```

### Structured updates to online lessons
=======
#1.##CLI Components ###Command : space separated instruction line= command + options
#2.##II###7 : procedural programming (line after line)
#2##V###6 : example: `sudo du -hs * | sort -hr` and `sudo find / -type f -size +1G -exec ls -lh {} \;`
#2##V###10: tar, zip, gzip + compressed vs archived
#4##Git : Detailed git intro
#4##Git : Branching strategies
#4##Practical case : intro: mostly done with installation. Clarification: now 3 "system levels" (vscode-local, dev env, githubRepo/"origin") -> detail each role (mention `git fetch --all`)
#4##Practical case : 1: create repo with files (readme) to avoid issues of empty repo
#4##Practical case : 2: cloning from VScode GUI to avoid security issues due to private repo

#5##II###7 : `re`
#5##III###7 : `map()`, `filter()`, and `sorted()` + `itertools`
#5##III###8 : packing and unpacking
#5##VI : file open critical
#5##VI : `os` and `sys` manipualtion
#5##VII : when using notebook: check your kernel

#5.1
## **Error Handling**
1. **Using `try` and `except` Blocks**  
   - Catching and handling exceptions  
2. **The `finally` Statement**  
   - Ensuring cleanup operations  
3. **Handling Specific Errors**  
   - Common errors (`ValueError`, `FileNotFoundError`, `IndexError`, `KeyError`, `TypeError`, etc.)
======

### Potential content for future lessons
- [#5.1] 
	- Documentation
	- Error Handling
	- Unit tests
	- Debugger usage
- [#5.2] Workflow manager usage (snakemake)
- [#5.3] Object Oriented Programming
- Biostatistics
- Data analysis
	- numpy/cupy, pandas, seaborn
	- sklearn, pytorch/tensorflow
	- Machine learning

- Bioinformatics fundamentals
	- Sequence manipulation: alignment, tree, homologies (blast, clustalo, biopython)
	- Structure manipulation
	- Common plot types 
- Deep Learning
- Graph theory
	- basics
	- matrix representation
- Project Design & Modeling (UML,ERM,Mermaid, job DAG)
- Performance and optimisation
	- Threading
	- GPU usage
- Molecular Dynamic Simulations
- Metabolic modeling and engineering
- Best practices for using generative DL when programming (intuition vs revision)

### Additional documentation and cheat sheets
- Statistics Fundamentals: https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9
- Machine Learning: https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF
- Intro to protein structure prediction and design: https://www.youtube.com/watch?v=P_fHJIYENdI
- Pandas dataframe subsetting: https://pandas.pydata.org/docs/getting_started/intro_tutorials/03_subset_data.html
- Snakemake tutorial: https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html
- Regular expressions playground: https://regexr.com/

### Bonus
https://gource.io/
https://usegalaxy.org/
https://youtu.be/BxV14h0kFs0 (Tom Scott video on APIs)

### Exercices
- What's that sequence
- Get sequence programmatically from UniprotID
- Run MSA programmatically from fasta -> msa, tree, distmat
- install ssh connexion to mumin
