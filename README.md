# sincronizacao-de-threads

🇧🇷 Português | 🇺🇸 [English](README.en.md)

> Demonstração de multithreading e sincronização em Java: mescla múltiplos arquivos em um só, tratando a condição de corrida na escrita.

## Visão geral

Projeto educacional que ilustra **concorrência em Java**. Várias threads leem arquivos de texto diferentes em paralelo e escrevem em um único arquivo de saída. O ponto central é a **condição de corrida na escrita compartilhada**, resolvida com um método `synchronized` que garante escrita exclusiva por vez.

## Conceitos demonstrados

- Criação de threads (uma por arquivo de entrada) com `Runnable`.
- **Seção crítica sincronizada** para escrita no arquivo compartilhado.
- I/O com `BufferedReader`/`BufferedWriter`.

## Stack

Java SE 8+ (threads, `synchronized`, java.io).

## Como executar

```bash
javac MergeFilesWithThreads.java FileMerger.java
java MergeFilesWithThreads
```

> Requer os arquivos de entrada `frases1.txt`, `frases2.txt`, `frases3.txt`.

## Estado do projeto

Completo e funcional.

## Licença

Este projeto ainda não declara uma licença; até que uma seja adicionada, todos os direitos são reservados ao autor.
