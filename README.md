# Sudi

A speech tagging model using Xdecoding and Markov model trained on simple files and tested on the Brown Corpus dataset.

## Overview

Sudi is a Part-of-Speech (POS) tagging system that combines Xdecoding with a Markov model to achieve accurate word tagging. The system is trained on simple text files and validated against the Brown Corpus dataset.

## Features

- Xdecoding-based POS tagging
- Markov model integration
- Training on custom text files
- Testing against Brown Corpus dataset
- Support for multiple text formats

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sudi.git
cd sudi
```

2. Ensure you have Java installed on your system (version 8 or higher)

## Usage

### Training Data

The project includes several training datasets:
- Simple training data:
  - `simple-train-sentences.txt` and `simple-train-tags.txt`
  - `simple-train-sentences2.txt` and `simple-train-tags2.txt`
- Brown Corpus data:
  - `brown-train-sentences.txt` and `brown-train-tags.txt`

### Running the Model

To run the HMM-based POS tagger:

```bash
javac HMM.java
java HMM
```

## Project Structure

```
sudi/
├── HMM.java              # Main implementation file
├── simple-train-sentences.txt    # Simple training sentences
├── simple-train-tags.txt        # Simple training tags
├── simple-train-sentences2.txt  # Additional simple training sentences
├── simple-train-tags2.txt      # Additional simple training tags
├── brown-train-sentences.txt   # Brown Corpus sentences
├── brown-train-tags.txt       # Brown Corpus tags
├── .gitignore
├── .gitattributes
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
