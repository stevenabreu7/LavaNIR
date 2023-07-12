# NIR for Lava

This repository provides an implementation of NIR for Lava. It provides a function to `read` a lava-dl model from a `.net` file (using lava-dl's `netx` tool) into NIR.

Todo: function to read an NIR model and save it as a lava-dl `.net` model.

Pull lava-dl from their repository, then follow their instructions to install lava-dl into a virtual environment (e.g. `.venv`).

Then pull nir from their repository, and install it using `pip install .` into the same virtual environment.

Verify writing to NIR by running `python lava_nir.py`.

Note (Jul 11, 7pm mountain time): have to add flatten module to NIR to make it work. PR coming soon.
