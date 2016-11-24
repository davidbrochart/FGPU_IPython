This directory contains all sources for the FPGU python package.

It can be installed from terminal by navigating to this directory and executing:
```sh
sudo -H pip install --upgrade 'git+https://github.com/malkadi/FGPU_IPython'
```

- The files *FGPU.py, \_\_init\_\_.py and general_const.py* are needed to setup the package.
- *clang* and *llc* are executables to compile OpenCL kernels for FGPU (compiled for the kernel 3.17.0-xilinx)
- *llvm-objdump* can be used to show the disassembly of the compiled kernel.
- *compile.sh* is a script used for the compilation process.
- *xlnk* is a package for CMA (Continuous Memory Allocator) provided by Xilinx
