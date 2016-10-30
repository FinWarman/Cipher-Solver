# Cipher-Solver
A program to automatically solve Caeser and Affine shift ciphers given text inputs.

This works by first trying every possible key for the chosen cipher, then analysing every output to see which contains the greatest number of English words, sorting them in order of how many words they contain and presenting you with the most English-like output.

Dictionary files (enaff.aff, endic.dic) must be in directory that excutable is launched from.
