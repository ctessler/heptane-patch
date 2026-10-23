# Patches to HEPTANE

This repository contains patches to the
[Heptane](https://gitlab.inria.fr/puaut/heptane) WCET.


Each of the patches are listed below along with their purpose.

## Usage

Clone Heptane and this patch repository, then use `git am` to apply
the patches.

```bash
$ git clone https://github.com/ctessler/heptane-patch.git
$ git clone https://gitlab.inria.fr/puaut/heptane.git
$ cd heptane
heptane $ git am ../heptane-patch/*.patch
```

## Patches

- [0001-Program.cc.patch](./0001-Program.cc.patch)

  Build fixes for gcc 16.2.1

- [0002-AnalysisHelper.cc.patch](./0002-AnalysisHelper.cc.patch)

  Build fixes for gcc 16.2.1
