markdown# MapReduce DNA Sequence Analysis

Hadoop MapReduce program for counting DNA sequence patterns in Java.

## Features
- Counts occurrences of 2-mers, 3-mers and 4-mers in DNA sequences
- Processes each line independently
- Input: E. coli DNA sequence

## How to Run

Compile:
javac WordCount.java
jar cf wordcount.jar WordCount*.class
Run on Hadoop:
hadoop jar wordcount.jar WordCount input/ output/

## Input
- `input/ecoli.txt` - E. coli DNA sequence file

## Output
- `output.txt` - Contains occurrence counts for all 2-mers, 3-mers and 4-mers

## Technologies
Java, Hadoop, MapReduce
