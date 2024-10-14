To use Mojo code inside the Jupyter book, you need the following:

1. `ipykernel` to be installed to run the code inside the jupyter book.
2. `magic shell` to be activated, so that the kernel see the ENV that is pointing to `libedit.so.2`
3. Run VS code at `--verbose` to avoid the error `elf_dynamic_array_reader.h(64) tag not found`
4. Select the mojo kernel named as `MAX (Conda ENV Mojo kernel)`

To install the ipykernel, run `magic add ipykernel`

To get the Ubuntu libedit.so.2 and define the ENV variable, see the file `libedit.so.2.ipynb` 

To setup the VS code to run with `--verbose` flag everytime it runs, see the file `verbose.ipynb` 

To setup the correct kernel for the notebook, see the video
