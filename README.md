# 🧬 DNA to Protein Converter 🧬

This C++ program converts a DNA sequence into its corresponding protein sequence. DNA serves as the template for protein synthesis through transcription and translation, where sequences of nucleotides are transcribed into complementary mRNA sequences and then translated into sequences of amino acids. This program automates the process of translating DNA sequences into proteins, adhering to the genetic code.

## Requirements

- C++ compiler (supporting C++11 or later)
- Standard C++ libraries

## Usage

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/dna-to-protein-converter.git
    ```

2. **Compile the Program:**

    ```bash
    g++ -std=c++11 TheCentralDogma.cpp -o dna_to_protein

3. **Run the Program:**

    ```bash
    ./dna_to_protein

4. **Enter the DNA Sequence:**

    Enter the DNA sequence when prompted.

5. **View the Output:**

    The program will display the corresponding protein sequence.


## Explanation

The DNA sequence is transcribed into mRNA, following base pairing rules (A-U, T-A, G-C, C-G). The mRNA sequence is then divided into codons, each consisting of three nucleotides. Each codon corresponds to a specific amino acid or a stop signal. This program follows the standard genetic code to translate DNA sequences into proteins.

## Acknowledgments

- Inspired by the genetic code and the process of protein synthesis.
- Built with a passion for molecular biology and programming.
