## Accessing the Dataset and Notebook

To access the dataset and utilize the Jupyter Notebook, follow these instructions:

### 1. Cloning the Repository

Ensure Git LFS is installed on your local system before cloning the repository:

```bash
git clone --recurse-submodules <repository-url>
```

### 2. Pulling Changes

After cloning, navigate to the repository directory and configure Git LFS:

```bash
cd <repository-directory>
git lfs install
```

To pull the dataset files and updates:

```bash
git pull
```

### 3. Fetching Large Files

To exclusively fetch the dataset files:

```bash
git lfs pull
```
