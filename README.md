# Coding Challenges Series

This repository series contains solutions to various coding challenges from [CodingChallenges.fyi](https://codingchallenges.fyi/). Each project is a custom implementation based on the requirements of a specific challenge, designed to address specific problems and create efficient, functional tools.

## Table of Contents

1. [Word Count Utility (wc)](#1-word-count-utility-wc)
2. [JSON Parser](#2-json-parser)
3. [Compression Tool (cccmp)](#3-compression-tool-cccmp)
4. [Load Balancer (cc-load-balancer)](#4-load-balancer-cc-load-balancer)
5. [Command-Line Sorting Utility (cc-sort)](#5-command-line-sorting-utility-cc-sort)
6. [Command-Line Calculator (cccalc)](#6-command-line-calculator-cccalc)
7. [Custom Redis Server CLI (cc-redis)](#7-custom-redis-server-cli-cc-redis)
8. [Command-Line Grep Utility (cc-grep)](#8-command-line-grep-utility-cc-grep)

## Challenges

### 1. Word Count Utility (wc)

- **Repository**: [https://github.com/nullsploit01/cc-wc](https://github.com/nullsploit01/cc-wc)
- **Challenge**: [wc Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-wc)
- **Description**:  
  The Word Count Utility (wc) is a custom implementation of the classic Unix `wc` command. This utility counts the bytes, words, lines, and characters in a given text file or standard input. It supports input from both files and standard input through piping.

### 2. JSON Parser

- **Repository**: [https://github.com/nullsploit01/cc-json-parser](https://github.com/nullsploit01/cc-json-parser)
- **Challenge**: [JSON Parser Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-json)
- **Description**:  
  This project is a custom JSON parser designed to validate JSON files for syntax and structural correctness. The parser also runs predefined tests on JSON datasets to ensure that the files conform to expectations.

### 3. Compression Tool (cccmp)

- **Repository**: [https://github.com/nullsploit01/cc-compressor](https://github.com/nullsploit01/cc-compressor)
- **Challenge**: [Huffman Compression Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-huffman/)
- **Description**:  
  CCCMP is a custom implementation of a compression and decompression tool based on Huffman coding. The tool is designed to efficiently compress and decompress files up to 100MB in size, featuring a command-line interface for easy operation.

### 4. Load Balancer (cc-load-balancer)

- **Repository**: [https://github.com/nullsploit01/cc-load-balancer](https://github.com/nullsploit01/cc-load-balancer)
- **Challenge**: [Load Balancer Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-load-balancer)
- **Description**:  
  This project is a custom implementation of a load balancer that efficiently distributes incoming network traffic across a number of backend servers. It checks the health of backend servers, balances the load based on their real-time status, and ensures high availability and reliability of the hosted applications. The implementation leverages Docker for easy deployment of multiple server instances and includes a command-line interface for managing configurations.

### 5. Command-Line Sorting Utility (cc-sort)

- **Repository**: [https://github.com/nullsploit01/cc-sort](https://github.com/nullsploit01/cc-sort)
- **Challenge**: [Sorting Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-sort)
- **Description**:  
  CC-Sort is a versatile command-line sorting utility that supports a variety of algorithms including Radix, Merge, Quick, Heap, and Random. Designed to handle both unique and non-unique sorting tasks, it provides options to sort data from files in a customizable manner, supporting large datasets efficiently. The tool's flexibility makes it suitable for a range of applications from educational purposes to practical data processing tasks.

### 6. Command-Line Calculator (cccalc)

- **Repository**: [https://github.com/nullsploit01/cc-calculator](https://github.com/nullsploit01/cc-calculator)
- **Challenge**: [Calculator Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-calculator)
- **Description**:  
  CCCalc is a command-line calculator that parses and evaluates complex arithmetic expressions accurately. Designed to process expressions involving basic operations like addition, subtraction, multiplication, and division, it handles nested operations and maintains correct order of operations. This tool is ideal for users who need a reliable and quick way to perform calculations through a CLI.

### 7. Custom Redis Server CLI (cc-redis)

- **Repository**: [https://github.com/nullsploit01/cc-redis](https://github.com/nullsploit01/cc-redis)
- **Challenge**: [Redis Server Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-redis/)
- **Description**:  
  CC-Redis is a custom CLI tool designed for managing and interacting with a Redis server. It supports an interactive mode similar to `redis-cli` and provides core commands like `SET`, `GET`, `DEL`, `PING`, and `ECHO`. The server communicates using the RESP protocol, ensuring compatibility with standard Redis clients, and supports custom configurations for port and host settings. CC-Redis is optimized for high throughput, achieving over 200,000 requests per second in benchmark tests for `SET` and `GET` commands.

### 8. Command-Line Grep Utility (cc-grep)

- **Repository**: [https://github.com/nullsploit01/cc-grep](https://github.com/nullsploit01/cc-grep)
- **Challenge**: [Grep Challenge on CodingChallenges.fyi](https://codingchallenges.fyi/challenges/challenge-grep)
- **Description**:  
  CC-Grep is a command-line utility designed to search for patterns in files, similar to the classic `grep` command. This tool includes options for case-insensitive search, recursive directory traversal, and inverted match to display lines that do not contain the specified pattern. It supports powerful and flexible search capabilities, making it ideal for command-line users needing efficient text searching across files and directories.
