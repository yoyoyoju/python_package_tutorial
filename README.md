# python_package_tutorial
python package tutorial

Follow the tutorial [here](https://packaging.python.org/tutorials/packaging-projects/).


## install it

Install the package for development with:

    pip install --editable /path/to/the/package
    pip install -e .    # in the root of the package


## use it

Import the package with:

    from example_pkg.submodule import hello
    hello.sayHello("me")

## run it

To run the `__main__.py` file:

    python -m example_pkg
