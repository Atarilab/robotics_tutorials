﻿# Supaero robotics, 2022

This repository contains the exercices for the robotics class at Supaero, 2022.
The exercices are organized by notebook. Each notebook corresponds to one chapter of the class.
The notebooks are in Python and based on the software [Pinocchio](https://github.com/stack-of-tasks/pinocchio).

## Set up

### Linux, Python 3, PyPI

On a Linux system with Python 3, you can get the dependencies directly with +[pip (see installation procedure and update below)](#installing-pip):
```bash
python3 -m pip install -r requirements.txt
```


NB: you should consider using a [virtualenv](https://docs.python.org/3/library/venv.html)

Once you have the dependencies, you can start the server with `jupyter notebook`

### Docker

On other systems, use use the virtualization provided by +Docker. A Docker image is provided, and can be started with:

```bash
sudo docker run --net host gepetto/supaero
```

## Side notes

### Installing pip

Pip is a tool for installing and managing Python packages. You can install it with

```bash
sudo apt install python3-pip
```

The default version of +pip installed by +apt is not up to date, so upgrade it with
```bash
python3 -m pip install --upgrade --user
```

In general, running +pip is likely to run an alias on +pip in /usr, so either run it through python3 as explained above, or make sure your path select the right pip executable in your ~/.local. The option --user is kind of optional for recent +pip version, but removing it should work with a warning.

### Installing docker

On linux, install docker with +apt (or see https://docs.docker.com/engine/install/ubuntu/).

```bash
sudo apt install docker.io
```
On other OS, see [how to get Docker](https://docs.docker.com/get-docker/).


# Join me on \[Matrix\]

[\[Matrix\]](https://matrix.org/) is a distributed chat system that will be used during the class. Consider [creating an account](https://app.element.io/#/register) and join [the classroom channel](https://matrix.to/#/#supaero-robotics-2022:laas.fr).
