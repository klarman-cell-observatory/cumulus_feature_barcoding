# Cumulus Tool on Feature Barcoding

A fast C++ tool to extract feature-count matrix from sequence reads in FASTQ files. It is used by Cumulus for feature-count matrix generation of cell hashing, nucleus hashing, CITE-Seq and Perturb-seq protocols, using either 10x Genomics V2 or V3 chemistry.

## Installation

The installation has been tested on Debian and Ubuntu Linux.

1. Install dependency packages:

```
sudo apt install build-essential git libboost-iostreams-dev
```

2. Check out this repository via Git:

```
git clone https://github.com/klarman-cell-observatory/cumulus_feature_barcoding.git
```

3. Enter the directory and compile:

```
cd cumulus_feature_barcoding
make all
```

4. Now you'll have an executable named ``generate_count_matrix_ADTs`` inside your folder. Type 

```
./generate_count_matrix_ADTs
```

to see its usage.

## Usage