# pypackage

Example pip package hosted on Github.

Install the latest with

    pip install git+ssh://git@github.com/awheelergs/pypackage.git

Install a tagged version with

    pip install git+ssh://git@github.com/awheelergs/pypackage.git@0.1.0

Test by

     import pypackage
     pypackage.test()

Update any ``requirements.txt` from

    pypackage=0.1.0

with either

    git+ssh://git@github.com/awheelergs/pypackage.git

or

    git+ssh://git@github.com/awheelergs/pypackage.git@0.1.0

See [Pip and Git](https://pip.pypa.io/en/latest/reference/pip_install/#git) for more options.
