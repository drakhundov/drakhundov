# Hello

Welcome. Most of the work here grows out of a fondness for mathematics, and it deliberately spans several disciplines: benchmarking large language models, retrieval systems, machine learning from first principles, algorithms and data structures, operating-system internals in C, real-time scheduling, and processor design in Verilog.

I'm based in Istanbul, Türkiye, completing my degree in Computer Engineering at **Istanbul Technical University**, and previously interned at **Baykar** in AI software development. I'm glad to discuss any of this work in English, Turkish or Russian.

## 🧠 Machine learning & LLMs

| Project | What it is |
|---|---|
| [qwen3.5-quant-bench](https://github.com/drakhundov/qwen3.5-quant-bench) | Benchmarks fp16 vs AWQ quantization of Qwen3.5-2B on MME-RealWorld with vLLM, judging latency (TTFT/TPOT, tail percentiles), memory and accuracy together. GPTQ pending a public checkpoint |
| [rag-api](https://github.com/drakhundov/rag-api) | RAG engine for chatting with PDFs: OCR for scanned pages, query translation (multi-query, HyDE, decomposition, step-back), heuristic routing and reciprocal rank fusion, on LangChain + Chroma with a Chainlit UI |
| [ml-suite](https://github.com/drakhundov/ml-suite) | Classic ML from scratch in NumPy: linear/polynomial regression (gradient descent & least squares), one-vs-all logistic regression, KNN, k-means and naive Bayes, with experiment notebooks |
| [llm-tooling](https://github.com/drakhundov/llm-tooling) | Minimal ReAct-style agent: a decorator turns typed Python functions into tool specs, and the LLM calls them (calculator, time, weather) via JSON actions |

## ⚙️ Systems & hardware

| Project | What it is |
|---|---|
| [basic-cpu](https://github.com/drakhundov/basic-cpu) | 16-bit CPU in Verilog: 8 registers, 16-function ALU with flags, ROM/RAM and a 12-state one-hot control unit, with per-module testbenches |
| [rtss](https://github.com/drakhundov/rtss) | Real-time scheduling emulator in C++: table-driven, cyclic executive, RM, DM, EDF and LLF, tested with GoogleTest |
| [minifs](https://github.com/drakhundov/minifs) | A small file system in C, with superblock, inodes, bitmap block allocation, directories and path resolution |
| [unix](https://github.com/drakhundov/unix) | Classic Unix utilities rewritten in C (`cat`, `cp`, `grep`, `sort`, `tail`, `wc`), following *The C Programming Language* |
| [signal-translator](https://github.com/drakhundov/signal-translator) | Line coding and modulation schemes (NRZ, Manchester, AMI, ASK/FSK/PSK, PCM, Delta, AM/FM/PM) with a CLI |

## 📐 Algorithms & data structures

| Project | What it is |
|---|---|
| [algo-analysis](https://github.com/drakhundov/algo-analysis) | Sorting (quick, merge, radix, counting, bucket and more) and selection (quickselect, median-of-medians) algorithms in C++, with a benchmarking harness |
| [Red-Black-Tree](https://github.com/drakhundov/Red-Black-Tree) | Red-black tree in C++ with both iterative and recursive insertion and deletion, rotations and fix-ups, with GoogleTest property tests for the red-black invariants |
| [Binary-Search-Tree](https://github.com/drakhundov/Binary-Search-Tree) | Binary search tree in C++ with iterative and recursive insertion and deletion and rotations, tested with GoogleTest |
| [Heap](https://github.com/drakhundov/Heap) | Binary min/max heap in C++ with sift-up/sift-down and heapsort |
| [freebase-search](https://github.com/drakhundov/freebase-search) | Shortest-path (BFS) search between entities in the Freebase knowledge graph, written in Haskell |

## 🛠️ Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?logo=huggingface&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Verilog](https://img.shields.io/badge/Verilog-555555)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?logo=haskell&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

## 📫 Get in touch

[![Email](https://img.shields.io/badge/Email-abdul.akhundzada%40outlook.com-0078D4?logo=microsoftoutlook&logoColor=white)](mailto:abdul.akhundzada@outlook.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Abdul%20Akhundzada-0A66C2)](https://www.linkedin.com/in/abdul-akhundzadeh)
