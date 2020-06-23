# pyhsmm_packages
Files and instructions for install pyhsmm_spiketrains package.

These packages are tested on ubuntu 18.04 LTS with anaconda python2.7 environment,
It should work on linux and MacOS system, but not on windows machine.
For windows machine, you can try wsl.


# Dependencies:
make sure you have fllowing pakacge installed:


1. Anaconda2 or Miniconda2
    note: for Miniconda2, these packages are needed:
    ```python
    pip install numpy scipy matplotlib cython nose
    ···
2. gcc-4.8 g++-4.8
    ```shell
    sudo apt install gcc-4.8 g++-4.8
    ```
3. install pybasicbayes
    ```python
    pip install pybasicbayes
    ```


# installation:
1. go to "hips-lib" folder and run:
    ```python
    python setup.py build
    python setup.py install
    ```
2. go to "pyhsmm" folder and run:
    ```python
    python setup.py build
    python setup.py install
    ```
3. go to "pyhsmm_spiketrains" folder and run:
    ```python
    python setup.py build
    python setup.py install
    ```


# test:
go to "pyhsmm_spiketrains" folder and run:
```python
python demo.py
```
to test if the installation is correct.