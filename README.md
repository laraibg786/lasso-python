# ![LASSO](./docs/lasso-logo.png) LASSO Python Library

![test-main](https://github.com/open-lasso-python/lasso-python/actions/workflows/ci-cd.yml/badge.svg?branch=main)
![test-dev](https://github.com/open-lasso-python/lasso-python/actions/workflows/ci-cd.yml/badge.svg?branch=develop)

This Python library is designed for general-purpose usage in the field of Computer Aided Engineering (CAE).
Its name originates from the original initiator and donator of the project, [LASSO GmbH](https://www.lasso.de/en).
The library is now maintained by an open-source community.

* * *

## 📦 Module Overview

* [lasso.dyna](https://open-lasso-python.github.io/lasso-python/dyna/)
* [lasso.dimred](https://open-lasso-python.github.io/lasso-python/dimred/)
* [lasso.femzip](https://open-lasso-python.github.io/lasso-python/femzip/)
* [lasso.diffcrash](https://open-lasso-python.github.io/lasso-python/diffcrash/)

For further information, please read the [📚 Documentation](https://open-lasso-python.github.io/lasso-python/)

* * *

## 📥 Installation

```shell
python -m pip install lasso-python
```

* * *

## 👥 Community

Join our open-source community on
[![Discord](./docs/icon-discord.png)](https://discord.gg/jYUgTsEWtN)

* * *

## 🛠️ Development

For development, install [poetry](https://python-poetry.org/) and [task](https://taskfile.dev/):

```shell
python -m pip install poetry
python -m pip instal go-task-bin
```

`task` can also be installed using following command on unix-based system

```shell
sh -c "$(curl --location https://taskfile.dev/install.sh)" \
        -- -d -b ~/.local/bin
```

Then by simply running the command `task` you can find a variety of available
commands such as `task setup` to install all dependencies or `task test` to
run the test suite.

Happy Coding 🥳🎉
