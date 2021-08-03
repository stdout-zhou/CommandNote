Conda is a package management tool, which is suitable for multiple programming languages.You can even create a visual development environment which will isolate with other's.

# Install

Just install miniconda.

```shell
$ curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
$ chmod 777 Miniconda3-latest-Linux-x86_64.sh #add the running permission
$ bash Miniconda3-latest-Linux-x86_64.sh #run
```

# Update version

``` shell
$ conda update conda
```



# Use

When you first use conda, you should "chmod 777 active" in miniconda3/bin.

Activating conda.

``` shell
$ source bin/activate
```

List all visual environment.

``` shell
$ conda env list
```

Add channels.

``` shell
$ conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
$ conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
$ conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/conda-forge/
$ conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/bioconda/
```

Show channels.

``` shell 
$ conda config --get channels
```

Create visual environment.

``` shell
$ conda create -n flask python=3.6.2 # "flask" is the name of visual environment.
```

Activate a environment

``` shell
$ conda activate flask
```

Install packages.

``` shell
$ conda install flask # "flask" is the name of installed package.
```

