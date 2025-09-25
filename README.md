# IPHS391 Fall 2025 Miniproject 1: Benchmarking Expert Chatbot Personas

Welcome to the repository for **IPHS391 Fall 2025 Miniproject 1: Benchmarking Expert Chatbot Personas**!  
This project is part of the IPHS391 course at Duke University and focuses on exploring, benchmarking, and analyzing expert chatbot personas in various conversational domains.

## Project Overview

The goal of this miniproject is to evaluate and compare the performance of different expert chatbot personas.  
We utilize benchmarking strategies to assess chatbot effectiveness, accuracy, and domain expertise.

## Features

- **Persona Definitions:** Scripts and configuration for defining expert chatbot personas.
- **Benchmarking Tools:** Automated tools and scripts to test chatbot responses across multiple domains.
- **Evaluation Metrics:** Code and documentation for quantitative and qualitative evaluation.
- **Results & Analysis:** Output files, visualizations, and summary reports of benchmarking experiments.

## Repository Structure

```
.
├── data/           # Datasets and prompt files used for benchmarking
├── scripts/        # Python/R scripts for running benchmarks and analyses
├── personas/       # Persona definitions and configuration files
├── results/        # Output, metrics, and evaluation summaries
├── notebooks/      # Jupyter or RMarkdown notebooks for data analysis
├── README.md       # Project documentation
└── ...
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/peterdunson/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   cd iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas
   ```

2. **Set up dependencies:**
   - Install Python (recommended: 3.8+)
   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run a benchmark:**
   - Example usage:
     ```bash
     python scripts/run_benchmark.py --persona personas/math_expert.json --dataset data/math_prompts.csv
     ```

## Contributing

Contributions are welcome!  
Please open an issue or submit a pull request with improvements, bug fixes, or new persona designs.

## License

This project is for academic use in IPHS391 at Duke University.  
For other uses, please contact the repository owner.

## Contact

Maintainer: [Peter Dunson](https://github.com/peterdunson)  
For questions, please use GitHub Issues or email via Duke directory.

---

*Created for IPHS391, Fall 2025 — Duke University*
