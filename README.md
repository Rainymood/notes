# Notes

## Setup

```
conda create --name notes -y
conda activate notes
conda install ipykernel
pip install -r requirements.txt
```

## Usage (windows)

Build the docs

```
make html
```

And find the docs at `docs/_build/html/index.html`

Or you can build and open at the same time

```
make html && start msedge file:///C:/Users/JanMeppe/Documents/Snappet/notes/docs/_build/html/index.html
```

## Links

* https://docs.readthedocs.io/en/stable/guides/jupyter.html