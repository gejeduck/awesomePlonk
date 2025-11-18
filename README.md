# Plonk_TH

An educational, from-scratch Python implementation of the **PLONK
zero-knowledge proving system**, based on the specification from the
[PLONK paper (ePrint 2019/953)](https://eprint.iacr.org/2019/953),
starting from page 27.\
This repository includes both the core implementation and an
accompanying tutorial.

> **Note:**\
> This project is for **learning and experimentation only**. It is **not
> secure**, **not efficient**, and **not intended for production use**.

## 📁 Repository Structure

    .
    ├── setup.py                # Trusted setup phase
    ├── prover.py               # Prover algorithm
    ├── verifier.py             # Verifier algorithm
    ├── plonk.py                # Example: runs setup + prover + verifier
    ├── plonk_tutorial.ipynb    # WIP educational notebook
    └── README.md

## 🚀 Usage

Run the example proving and verification flow:

``` bash
python plonk.py
```

This executes:

1.  The setup phase\
2.  The prover's algorithm\
3.  The verifier's algorithm

Using a small example constraint system for demonstration.

## 📘 Tutorial Notebook

The file `plonk_tutorial.ipynb` contains:

-   Detailed explanations of each phase of PLONK\
-   Polynomial commitments\
-   Gate constraints and wiring\
-   Quotient polynomial construction\
-   Round-by-round transcript\
-   Prover--verifier flow

> The tutorial is **work in progress** and will continue to be expanded.

## 📊 PLONK Protocol Rounds

### **Round 1**

![Round 1](https://www.maya-zk.com/plonk-round1/round1.jpg)

### **Round 2**

![Round 2](https://www.maya-zk.com/plonk-round2/round2.png)

### **Round 3**

![Round 3](https://www.maya-zk.com/plonk-round3/round3.jpg)

### **Round 4**

![Round 4](https://www.maya-zk.com/plonk-round4/round4.jpg)

### **Round 5**

![Round 5](https://www.maya-zk.com/plonk-round5/round5.jpg)

## 🧠 Project Goals

-   Provide a simple, readable PLONK implementation for educational
    purposes\
-   Help learners understand polynomial IOPs and modern zk-protocols\
-   Offer a foundation for experimentation with PLONK components

## 🤝 Contributing

Contributions, critiques, and suggestions are welcome!

You can:

-   Open an issue\
-   Submit a pull request\
-   Propose improvements to the tutorial or implementation

## 📄 License

This project is provided for educational use.\
If a license file is added, please refer to it for details.
