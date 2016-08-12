# Mexican federal budget pipeline

This repository is part of the [Open-Spending](http://next.openspending.org) project. It contains a data pre-processing pipeline that cleans-up and concatenates multiple yearly budgets into one file ready to be modelled and uploaded into Open-Spending.

## Set up the notebook 

If you're a pythonista, just make sure that you have a `jupyter` notebook running `python3` with `pandas` installed. That's all you need. If not, the easiest way to get set up is to [download the Python3.5 version of Miniconda](http://conda.pydata.org/miniconda.html). On Windows, you're provided with a GUI, so basically you're done. If you're on Linux or OS-X, you'll have to run the installation script, like so: 

```
chmod +x Miniconda3-latest-Linux-x86_64.sh && bash +x Miniconda3-latest-Linux-x86_64.sh 
```

__Note:__ It's best to answer `no` to the question "Do you wish the installer to prepend the Miniconda3 install location to PATH in your /home/path/.bashrc ?" (you don't really want to change the default python path on your computer). In case you need help, check out the [Conda documentation](http://conda.pydata.org/docs/install/quick.html).

## Run the pipeline

Clone and `cd` into the repository:

```
git clone https://github.com/cyberbikepunk/mexico.git && cd
```

Checkout a new branch:

```
git checkout -b my-processing-branch
```

Launch the notebook from the GUI (Windows) or from the command line (Linux and OS-X):

```
export PATH=/path/to/miniconda3/bin:$PATH && jupyter notebook
```

Follow the instructions in the notebook. When you're done, push your pipeline configuration back to the repo for reference purposes. Thanks. Enjoy!
