
# jupyter_ascending

[![Build Status](https://travis-ci.org//jupyter_ascending.svg?branch=master)](https://travis-ci.org//jupyter_ascending)
[![codecov](https://codecov.io/gh//jupyter_ascending/branch/master/graph/badge.svg)](https://codecov.io/gh//jupyter_ascending)


Sync Jupyter Notebooks from any editor

![Jupyter Ascending](./media/simple_jupyter_ascending.gif)

## Installation

```
$ pip install jupyter_ascending
$ # It is possible you won't need to run the following commands on newer version of jupyter notebook,
$ # but it's recommended that you do anyway, because installing extensions is hard.
$ jupyter nbextension install --py --sys-prefix jupyter_ascending
$ jupyter nbextension     enable jupyter_ascending --sys-prefix --py
$ jupyter serverextension enable jupyter_ascending --sys-prefix --py
```

You can confirm it's installed by checking:
```
$ jupyter nbextension     list
$ jupyter serverextension list
```

## Usage in Vim

To use in vim, see: [jupyter_ascending.vim](https://github.com/untitled-ai/jupyter_ascending.vim)

