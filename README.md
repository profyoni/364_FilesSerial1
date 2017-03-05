# Bufferred vs Unbuffered Output

Write a program that outputs all primes under 10,000,000 to a file using unbuffered file stream
`outputStream = new PrintStream("primes1.txt");`, and manually flush the buffer after each prime number is output to demonstrate the effects of unbuffered output. Time the amount of time it takes for _only_ the file output: store the 10,000,000 primes and when all are collected output them all to file "primes1.txt". Include in your output file the start and end time and the time required to output the file in minutes, seconds and milliseconds in the following format: mm:ss:ms

Repeat the process (but do not repeat the code...remember DRY!) with a buffered file.
`outputStream = new PrintStream("primes2.txt");` without flushining the buffer at all. When the file is `close()` at the end of your operation it will flush and will flush throughout the running of your program.

##### As always, use best practices (including memo-ization) and conventions

