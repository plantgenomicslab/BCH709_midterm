Midterm exam
Your instructor has a GitHub repository containing a Python script (`gc_calculator.py`) that calculates GC content from a FASTA file. The script has multiple bugs. A test input file (`test_sequences.fa`) is provided in the repository.

**Repository URL:** `https://github.com/[instructor-username]/bch709-gc-calculator`

The expected behavior of the script:
```
python gc_calculator.py test_sequences.fa 10
```

Should output a tab-delimited table of all sequences with length >= 10 bp, showing the correct sequence ID, full sequence length, and GC content (%).


Tasks:

(A) Fork the repository to your own GitHub account and clone it to your local machine (or Pronghorn). Show the exact commands you used. (3 points)

(B) Run the script with the test input. Describe what happens and identify all bugs in the code. For each bug, explain what the code does wrong, what the correct behavior should be, and which line(s) you will change. (9 points)

(C) Fix all bugs, verify your corrected script produces the expected output, commit your changes with a descriptive commit message, push to your fork, and submit a pull request to the original repository. The pull request description must list each bug and how you fixed it. (8 points)


Submission: Provide the URL of your pull request.
