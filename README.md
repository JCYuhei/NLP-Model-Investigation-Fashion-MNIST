# NLP-Model-Investigation-Fashion-MNIST
Investigating and evaluating the use of different models on the Fashion-MNIST dataset. Understanding their drawbacks and flaws and how data representation affects the results produced by alternative models. 

## Running the Coursework | Installation and Download

1. Open the coursework.ipynb file 
2. Run the first cell (installation cell) to install the required packages
3. Run the notebook from the top (restart and run all)

Fashion-MNIST is downloaded automatically by Torchvision on the first run. (If download is failing, it could be a windows protected folder issue). Subsequent runs reuse the downloaded files and do not download again.

## Experiment Commands

## Hardware

- Operating system: Windows 10 Pro
- CPU: AMD Ryzen 7 5800X — 8 cores, 16 threads
- RAM: 32 GB
- GPU: NVIDIA GeForce RTX 4060 Ti — 8 GB VRAM

## Approximate runtimes

## Saved split/subset indices

- Source Training set: 50,000 images
- Validation set: 10,000 images
- Test set: 10,000 images
- CPU-friendly training subset: 10,000 images selected from source training set
- Both training sets and validation set are stratified using Seed = 0
- Indices and seed is stored in splits/indices.npz

## Seeds

## Configurations and Experiment IDs

## Acknowledgement of external codes, libraries checkpoints and assistance