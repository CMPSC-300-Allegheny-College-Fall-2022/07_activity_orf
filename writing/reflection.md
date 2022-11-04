# Bioinformatics (CS300) Activity: Open Reading Frame Finder

## What is your name?

Add Your Name Here

## Date: 3 November 2022

### Steps and Questions

* Locate the Python program (`src/orf_finder.py`) and a FASTA data file (`src/fleckOrchid fasta.txt`) in your repository.

* Run the `orf_finder.py` code using the FASTA data file (which is found in the directory `data/`. The command to run the code __from__ the `src/` directory while loading a data file from the `data/` directory is; `./orf_finder.py ../data/fleckOrchid_fasta.txt`.

    + Reflection Question:  What does the stand-alone program do?

```
TODO
```

* Using your favorite code editor, open the python code and locate line 11 (`threshold = 100`). Change this value to `50`, save your program and run it again.

    + Reflection Question: What does changing the threshold value appear to do?

```
TODO
```

* Try experimenting this `threshold` parameter by changing it  to other values. You will notice that the number of outputs changes.

    + Reflection Question: What threshold value did you use to find only five (5) potential ORF’s? Can you explain how this threshold has control over the number of output sequences?

```
TODO
```

    + Reflection Question: What are the sequences that the program is returning?

```
TODO
```

* Set threshold = 100 and save. Note: if your program becomes corrupt, you have a backup of the program and data file in src/backUp/. You could copy this file over the corrupt file to regain working code.

* Go to NCBI’s ORF finder at https://www.ncbi.nlm.nih.gov/orffinder/

* Use your favorite editor to open the FASTA data file. Copy and paste the DNA code from into the ORG finder tool at NCBI and use the SUBMIT button to determine the open reading frames.

* As you wait for your results to appear consider the below questions.

    + Reflection Question: Briefly compare and contrast the facility and utility in the using script-based tools, as opposed to using web-based tools.

```
TODO
```

    + Reflection Question: Using NCBI’s tool, how many open reading frames did you find using this online tool?

```
TODO
```

    + Reflection Question: Using how many open reading frames did you find using the Python tool?
		```
		TODO
		```

    + Reflection Question: Check and compare the results of the python tool and the online tool. Do any of the outputs match?

```
TODO
```

    + Reflection Question: Which sequences were found by both tools?

```
TODO
```

    + Reflection Question: Why are there any differences between the tool and the web tool in terms of results?

```
TODO
```

* Choose an ORF that was found by the online tools Copy and paste the protein sequence into Blast’s protein search tool (BlastP) found at link: https://blast.ncbi.nlm.nih.gov/Blast.cgi

    + Reflection Question: What is the name of a protein you found by using BlastP? What function can you argue that it has?

```
TODO
```

    + Reflection Question: Name two or three organisms which have similar proteins (or at least turn-up in your results).

```
TODO
```

    + Reflection Question: In terms of E-values for the results you used to determine the protein’s function, are you convinced that this protein is a match in the organisms you mentioned?

```
TODO
```

    + Reflection Question: What major differences do you find in the quality of the results from the stand-alone and online tools?

```
TODO
```

(Did you remember to add your names to the top of this document?)
