# sincronizacao-de-threads

🇺🇸 English | 🇧🇷 [Português](README.md)

> A Java multithreading and synchronization demo: merges multiple files into one, handling the write-side race condition.

## Overview

An educational project illustrating **concurrency in Java**. Several threads read different text files in parallel and write into a single output file. The key point is the **race condition on the shared write**, solved with a `synchronized` method that guarantees exclusive writing one thread at a time.

## Concepts demonstrated

- Thread creation (one per input file) with `Runnable`.
- **Synchronized critical section** for writing to the shared file.
- I/O with `BufferedReader`/`BufferedWriter`.

## Stack

Java SE 8+ (threads, `synchronized`, java.io).

## Running

```bash
javac MergeFilesWithThreads.java FileMerger.java
java MergeFilesWithThreads
```

> Requires input files `frases1.txt`, `frases2.txt`, `frases3.txt`.

## Project status

Complete and functional.

## License

This project does not yet declare a license. Until one is added, all rights are reserved by the author.
