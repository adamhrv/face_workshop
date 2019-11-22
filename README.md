# Computer Vision Face Workshop

## Setup

The basic steps are:

- clone project
- install miniconda
- create conda or pip environment
- run demos

### Clone Project

- `git clone https://github.com/adamhrv/face_workshop`
- you may need to [install git first](https://gist.github.com/derhuerst/1b15ff4652a867391f03)

### Install Miniconda

- Download the install file for your system <https://docs.conda.io/en/latest/miniconda.html>
- open terminal and run `bash Miniconda3-latest-MacOSX-x86_64.sh.sh` change this to the name of your .sh file first

### Create Conda Environemnt

- open terminal and `cd` into `face_workshop`

```
conda create -n face_workshop python=3.7
#conda activate face_workshop  # to activate environment
conda install nb_conda
conda install -c conda-forge nb_conda_kernels
pip install -r requirements.txt
jupyter notebook
```


### Troubleshooting

- dlib: building dlib may take a while. You may need to install or upgrade gcc or cmake. If on MacOS, you may also need to install xcode developer tools first. If issues, check <https://github.com/davisking/dlib/>
- conda: if you're using bash or zsh you may need to edit the conda env paths in your `~/.bashrc` or `~/.zshrc` file