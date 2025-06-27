# Readme for devicegen_std

## About devicegen_std

`devicegen_std` is a gated heterostructure device generator. It facilitates the creation of `Gmsh` mesh files corresponding to a gate geometry defined in a GDS layout text file.

## Installation

To install `devicegen_std`, we recommend first creating the `device_gen` environment with `conda` using:

```bash
$ conda env create -f environment.yml
$ conda activate devicegen_std
```

and then running:

```bash
$ pip install .
```

in the devicegen_std repository.

## Community

You are welcome to create new features for `devicegen_std`. To do so, please create a user-owned fork of the devicegen_std repository and submit a pull request containing your modifications.

## Copyright

`devicegen_std` is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. See the file COPYING in http://www.gnu.org/licenses/, for a description of the GNU General Public License terms under which you can copy the files.

## Reporting bugs in devicegen_std

Please report any bug by creating an issue on the devicegen_std GitHub page: https://github.com/nanoacademic/devicegen_std/issues.

## Scientific research

If you use `devicegen_std` in any work leading to a scientific publication, we would love to know ! Please contact us at: info@nanoacademic.com.

## Contacting Nanoacademic Technologies

The devicegen_std package is developed and maintain by Nanoacademic Technologies. For any question that is not a bug report, please contact us at: info@nanoacademic.com.

## About Gmsh

`devicegen_std` uses `Gmsh` to create its meshes. `Gmsh` is "an open source 3D finite element mesh generator with a built-in CAD engine and post-processor", which is released under the GPL license. For more information on `Gmsh`, please visit: https://gmsh.info/.
