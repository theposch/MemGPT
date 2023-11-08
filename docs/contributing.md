# Contributing

## Installing from source
You can install MemGPT from source with:
```sh
git clone git@github.com:cpacker/MemGPT.git
cd MemGPT
pip install -e .
pip install -r requirements-dev.txt
```

We recommend installing pre-commit to ensure proper formatting during development:
```sh
pre-commit install
pre-commit run --all-files
```

### Formatting
We welcome pull requests! Please run the formatter before submitting a pull request:
```sh
black . -l 140
```
