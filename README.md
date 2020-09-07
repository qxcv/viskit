Mostly copy/pasted from [rllab](https://github.com/rll/rllab)'s viskit.

Added some features, like being able to split on multiple hyperparameters.

# Installation

Install this repository using pip:

```
pip install 'git+https://github.com/qxcv/viskit.git'
```

# Usage

```
viskit-frontend path/to/dir
```

This assumes the structure of dir is something like:

```
path/
    to/
        dir/
            exp1/
                progress.csv
                variant.json
            exp2/
                progress.csv
                variant.json
```

Note that this support wildcard, i.e.

```
python viskit/frontend.py path/to/dir/exp*
```
