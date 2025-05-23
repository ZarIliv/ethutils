*If you are looking for the version used in our [EMSE 2024 paper](https://arxiv.org/abs/2303.10517), do `git checkout emse2024`.*

# ethutils: Utilities for the Analysis of Ethereum Smart Contracts

## Installation on GNU/Linux and Unix

Before continuing, ensure that `python3` is installed.

```bash
git clone https://github.com/gsalzer/ethutils.git # clone git repository
cd ethutils
python3 -m venv venv                              # set up a virtual environment for Python
source venv/bin/activate                          # ... and activate it
pip install cbor2                                 # install dependencies
```

## Installation via setup-venv.sh on GNU/Linux and Unix

Before continuing, ensure that `python3` is installed.

```bash
git clone https://github.com/gsalzer/ethutils.git # clone git repository
cd ethutils
./setup-venv.sh                                   # set up a virtual environment for Python, install poetry and install the tools
```

## Use this package in other projects

```bash
pip install https://github.com/gsalzer/ethutils.git@<COMMIT_HASH>#egg=ethutils                    # install the repository from GitHub
```

## Contents of the repository

* [Documentation and code samples](doc)
* [Python scripts for manipulating bytecodes](ethutils)
* [Bash script for the rule-based classification of Solidity function headers](headers)
