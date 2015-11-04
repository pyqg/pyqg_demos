[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/pyqg/pyqg_demos)

# pyqg_demos

A collection of [pyqg](https://github.com/pyqg/pyqg) demos that are executed on the [cloud](http://app.mybinder.org/2028216009/notebooks/index.ipynb).
# Contributing

The workflow for contributing to `pyqg_demos` is similar
to `pyqg`'s. First [fork the repository](https://help.github.com/articles/fork-a-repo/). 
Then clone it to your local machine

```{bash}
$ git clone git@github.com:USERNAME/pyqg_demos
```

and set you repository to track the upstream repository

```{bash}
$ cd pyqg_demos
$ git remote add upstream git://github.com/pyqg/pyqg_demos.git
```

Make sure to sync your local `master` branch with `upstream/master`

```{bash}
$ git fetch upstream
$ git rebase upstream/master
```

To implement a new example branch off of `master`
```{bash}
$ git checkout -b new_example
```

add the new example, test it, and commit you all your changes.
Finally push it to github

```{bash}
$ git push new_example
```
and submit a [pull request](https://help.github.com/articles/using-pull-requests/).

If the example is based on a paper or section of a book, please provide detailed reference
or link within the notebook.
