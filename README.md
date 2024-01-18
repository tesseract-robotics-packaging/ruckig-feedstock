About ruckig-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/tesseract-robotics/ruckig-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/pantor/ruckig

Package license: MIT

Summary: Motion Generation for Robots and Machines. Real-time. Jerk-constrained. Time-optimal.

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-ruckig-green.svg)](https://anaconda.org/tesseract-robotics/ruckig) | [![Conda Downloads](https://img.shields.io/conda/dn/tesseract-robotics/ruckig.svg)](https://anaconda.org/tesseract-robotics/ruckig) | [![Conda Version](https://img.shields.io/conda/vn/tesseract-robotics/ruckig.svg)](https://anaconda.org/tesseract-robotics/ruckig) | [![Conda Platforms](https://img.shields.io/conda/pn/tesseract-robotics/ruckig.svg)](https://anaconda.org/tesseract-robotics/ruckig) |

Installing ruckig
=================

Installing `ruckig` from the `tesseract-robotics/label/labels/dev/indv` channel can be achieved by adding `tesseract-robotics/label/labels/dev/indv` to your channels with:

```
conda config --add channels tesseract-robotics/label/labels/dev/indv
conda config --set channel_priority strict
```

Once the `tesseract-robotics/label/labels/dev/indv` channel has been enabled, `ruckig` can be installed with `conda`:

```
conda install ruckig
```

or with `mamba`:

```
mamba install ruckig
```

It is possible to list all of the versions of `ruckig` available on your platform with `conda`:

```
conda search ruckig --channel tesseract-robotics/label/labels/dev/indv
```

or with `mamba`:

```
mamba search ruckig --channel tesseract-robotics/label/labels/dev/indv
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search ruckig --channel tesseract-robotics/label/labels/dev/indv

# List packages depending on `ruckig`:
mamba repoquery whoneeds ruckig --channel tesseract-robotics/label/labels/dev/indv

# List dependencies of `ruckig`:
mamba repoquery depends ruckig --channel tesseract-robotics/label/labels/dev/indv
```




Updating ruckig-feedstock
=========================

If you would like to improve the ruckig recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`tesseract-robotics` channel, whereupon the built conda packages will be available for
everybody to install and use from the `tesseract-robotics` channel.
Note that all branches in the tesseract-robotics/ruckig-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@johnwason](https://github.com/johnwason/)

