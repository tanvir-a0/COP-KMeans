# COP-KMeans Algorithm Implementation

This repository contains the implementation of the **COP-KMeans** algorithm for constrained clustering. It includes examples of regular clustering and COP-KMeans clustering with must-link and cannot-link constraints.

## Installation

First, clone this repository:

```sh
git clone https://github.com/tanvir-a0/COP-KMeans.git
cd COP-KMeans
```

Then, install the required dependencies:

```sh
pip install -r requirements.txt
```

## Files Overview

- `example_1_with_regular_clustering.py` - Demonstrates regular clustering without constraints.
- `example_1_with_cop_k_means_clustering.py` - Implements the same example but with the COP-KMeans clustering algorithm.
- `example_2_with_cop_k_means_clustering.py` - A real-world example of COP-KMeans clustering using must-link and cannot-link constraints.
- `example_3_with_cop_k_means_clustering.py` - Another real-world example of COP-KMeans clustering using must-link and cannot-link constraints but with more complexity.

## Running the Examples

To run the scripts, use the following commands:

```sh
python example_1_with_regular_clustering.py
```

```sh
python example_1_with_cop_k_means_clustering.py
```

```sh
python example_2_with_cop_k_means_clustering.py
```

```sh
python example_3_with_cop_k_means_clustering.py
```

## Explanation of Constraints

In **COP-KMeans**, we define relationships between data points:

- **Must-link constraints**: These points should be in the same cluster.
- **Cannot-link constraints**: These points should not be in the same cluster.

In the real-world examples, these constraints represent relationships among workers forming groups based on their bonding.

---

For any queries or contributions, feel free to open an issue or create a pull request.
