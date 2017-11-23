# ODL course material

This is the repository for course material (input and output) for the ODL training at KTH in Stockholm, December 2017.

## Installing ODL

Check out the [online instructions](https://odlgroup.github.io/odl/getting_started/installing.html). Use the `conda` variant if possible, it has proven to be least troublesome. If you find any errors or experience issues, please get back to us ([@kohr-h](https://github.com/kohr-h) or [@adler-j](https://github.com/adler-j)).

## Jupyter Notebooks

Part of the material will be published as [Jupyter notebooks](http://jupyter.org/). If you're familiar with Mathematica notebooks, you won't be surprised.

To install the notebook software, you can either use `conda`:

    conda install notebook

or `pip`:

    pip install notebook

You can then start the software by running

    jupyter notebook

in a terminal. Sometimes one gets `OSError: [Errno 99] Cannot assign requested address`. In this case an explicit IP has to be given, which should be the equivalent to `localhost` in your case:

    jupyter notebook --ip=127.0.0.1

The notebooks can also be viewed online as static HTML pages. This works (somewhat) on GitHub directly, but better with [nbviewer](https://nbviewer.jupyter.org/). Just copy the URL of the notebook into the text field at that page.
