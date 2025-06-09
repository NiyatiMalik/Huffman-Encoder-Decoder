# 🗜️ Huffman Encoder-Decoder

## 📘 Overview

This is a simple C++ implementation of the **Huffman Coding** algorithm, used for **lossless data compression**. The program takes input text, builds a frequency-based binary tree, encodes the input into a compressed binary format, and can decode it back to the original text.

---

## ✨ Features

- Build a Huffman Tree based on character frequency
- Encode input text into binary Huffman code
- Decode Huffman-encoded binary back to the original text
- Command-line based interaction
- Demonstrates priority queues, trees, and maps in C++

---

## 🛠 Technologies

- **Language:** C++
- **Data Structures:** Priority Queue (Min-Heap), Binary Tree, Hash Map
- **Standard Libraries:** `<iostream>`, `<queue>`, `<unordered_map>`, `<string>`, etc.

---

## 🚀 How to Run

### 1. Compile

Use any C++ compiler 

```bash
g++ huffman.cpp -o huffman
```

### 2. Run
```bash
./huffman
```

The program will prompt you to enter the input text, and it will display:

- Character frequencies

- Huffman codes

- Encoded binary string

- Decoded output

