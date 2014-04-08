# ZeroVM Tutorial

TODO: description here

## Setup

### Ubuntu 12.04 LTS

Install the latest version of ZeroVM command line utilities from the official
repository:

    ```bash
    $ sudo apt-get install python-software-properties
    $ sudo add-apt-repository ppa:zerovm-ci/zerovm-latest
    $ sudo apt-get update
    $ sudo apt-get install zerovm-cli
    ```

This will install the `zvsh` program used in this tutorial.

## Tutorial

The samples in this tutorial are numbered. Since each example is more complex
than the next, it is advised that you try them in order. Each sample contains
its own README.

In addition to the prepared samples, you can just execute Python code using
`python -c` in the following manner:

    ```bash
    $ zvsh --zvm-image=python.tar python -c "import sys; print sys.platform"
    ```
