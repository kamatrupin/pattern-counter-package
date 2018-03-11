# pattern-counter-package
The package contains executable and input files to demonstrate execution of the PatternCounter

Try following commands - 

Pattern 1: Counts occurrences of each unique word in the document
java -jar PatternCounter.jar Input.txt 1

Pattern 2: Counts occurrences of each unique number in the document
java -jar PatternCounter.jar Input.txt 2

Pattern 3: Counts occurrences of each unique phrase of three consecutive words in the document
java -jar PatternCounter.jar Input.txt 3

Unsupported pattern
java -jar PatternCounter.jar Input.txt 4

Insufficient Input in the file
java -jar PatternCounter.jar InsufficientInput.txt 1
