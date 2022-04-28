# eclipdemux
demultiplex utility for eclip raw fastq files (process eclip barcodes and ramdomers)

## Installing on Bridges2

```
module load anaconda3
git clone git@github.com:pscedu/eclipdemux.git
cd eclipdemux
python setup.py --user
```

To use, start `ipython`

```
➜  eclipdemux git:(master) ipython
zsh: command not found: ipython
➜  eclipdemux git:(master) module load anaconda3
(base) ➜  eclipdemux git:(master) ipython              
Python 3.8.5 (default, Sep  4 2020, 07:30:14) 
Type 'copyright', 'credits' or 'license' for more information
IPython 7.19.0 -- An enhanced Interactive Python. Type '?' for help.

In [1]: import eclipdemux_package
```
