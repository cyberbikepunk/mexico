# Mexican federal budget pipeline

This repository is part of the [Open-Spending](http://next.openspending.org) project. It contains a data pre-processing pipeline that cleans-up and concatenates multiple yearly budgets into one file ready to be modelled and uploaded into Open-Spending.

## Set-up

If you're a pythonista, just make sure that you have a `jupyter` notebook running `python3` with `pandas` installed. That's all you need. For less experienced python users, here's how to set yourself up.

### Download miniconda

[Download the Python3.5 version of Miniconda](http://conda.pydata.org/miniconda.html). If you're on Windows, you're done. In case you need help, check out the [Conda documentation](http://conda.pydata.org/docs/install/quick.html).

### Install miniconda

If you on Linux or OS-X, run the installation script, then follow the instructions.

```
chmod +x Miniconda3-latest-Linux-x86_64.sh && bash +x Miniconda3-latest-Linux-x86_64.sh 
```

__Note:__ It's best to answer `no` to the question "Do you wish the installer to prepend the Miniconda3 install location
to PATH in your /home/loic/.bashrc ?" (you don't really want to change the default python path on your computer).

### Launch the notebook

Launch the notebook from the command line. 

```
export PATH=/path/to/miniconda3/bin:$PATH && jupyter notebook
```

## Run the pipeline

Just follow the instructions in the notebook. Basically, you just need to:

1. specify an input folder
2. put the yealry budget files that you wish to concatenate in that folder
3. specify an output folder where the results will be dumped
4. click on `Run All` in the notebook menu

That's it!
