# Custom Implementation of Speculative Jacobi Decoding on Lumina-mGPT

This repository contains a custom implementation of Speculative Jacobi Decoding (SJD) on the Lumina-mGPT model. The implementation involves modifications to the `modeling_chameleon.py` and `transformers/generation/utils.py` files to incorporate the SJD functionality.

## Overview

Speculative Jacobi Decoding (SJD) is a technique used to improve the efficiency of decoding in AR visual generation models. This repository provides a custom implementation of SJD specifically tailored for the Lumina-mGPT model. The implementation involves replacing the original `modeling_chameleon.py` and `transformers/generation/utils.py` files with modified versions that include the SJD functionality.

## Prerequisites

Before using this repository, you must have the following:

- **Lumina-mGPT**: Ensure that you have installed Lumina-mGPT correctly. You can find the installation instructions [here](https://github.com/Alpha-VLLM/Lumina-mGPT).

## Usage

After completing the installation steps, you can use the Lumina-mGPT model with the custom SJD implementation. The `_sample` function in `utils.py` is specifically designed to handle the SJD logic, enhancing the decoding process.



## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.