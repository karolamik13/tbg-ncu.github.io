---
layout: single
title: Software
permalink: /software/
toc: true
author_profile: true
sidebar:
  nav: shortcuts
---

## `MAZE` Module for PLUMED2

### Information

`maze` (version 1.0)  
*Heterogeneous Ligand Unbinding along Transient Protein Tunnels*  
[Github](https://github.com/maze-code/plumed2-maze){: .btn .btn--inverse .btn--small}
[Page](https://maze-code.github.io){: .btn .btn--inverse .btn--small}
[arXiv](https://arxiv.org/abs/1808.08089){: .btn .btn--inverse .btn--small}

`MAZE` is a code that implements enhanced sampling methods for sampling the 
reaction pathways of ligand unbinding. It is made as a module for [PLUMED2]
(https://plumed.github.io/doc-v2.5/user-doc/html/index.html), an engine for 
free energy calculations of atomistic systems and enhanced sampling.

### Download and Install

You need to download the `MAZE` repository and enable the `MAZE` module by adding 
the `--enable-modules=maze` to the PLUMED configure command. You can follow the
instructions given
[here](https://plumed.github.io/doc-v2.4/user-doc/html/_installation.html). 

For example:
```sh
> ./configure --prefix=/usr/local --enable-modules=maze
> make -j 4
> make install
```

### Author

The `MAZE` module is developed and maintained by Jakub Rydzewski (Nicolaus 
Copernicus University), <jr@fizyka.umk.pl>.

### Support

You can ask questions or join the development discussion on:
- the [Gitter channel](https://gitter.im/maze-code/).
- the [PLUMED Google group](https://groups.google.com/forum/#!forum/plumed-users).

You can also post bug reports and feature requests in [Github
issues](https://github.com/maze-code/plumed2-maze/issues). Make sure to read the
Plumed guidelines first.

### Citation

If you find this useful, please cite the methods which `MAZE` is based on
using:

```latex
@article{rydzewski2019finding,
  title={Finding Multiple Reaction Pathways of Ligand Unbinding},
  author={Rydzewski, Jakub and Valsson, Omar},
  journal={J. Chem. Phys.},
  volume={150},
  pages={221101},
  year={2019}
}
```

and

```latex
@article{rydzewski2019maze,
  title={maze: Heterogeneous Ligand Unbinding along Transient Protein Tunnels},
  author={Rydzewski, Jakub},
  journal={Comp. Phys. Commun.},
  pages={106865},
  volume={TBA},
  year={2019}
}
```

### Funding

During its development, `MAZE` was funded by the National Science Center grants
no. 2015/19/N/ST3/02171, 2016/20/T/ST3/00488, and in part by 2016/23/B/ST4/01770.
