About attrs
===========

Home: https://attrs.readthedocs.io/en/stable/

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: attrs is the Python package that will bring back the joy of writing classes by relieving you from the drudgery of implementing object protocols (aka dunder methods).

attrs is the Python package that will bring back the joy of writing
classes by relieving you from the drudgery of implementing object
protocols (aka dunder methods). Its main goal is to help you to write
concise and correct software without slowing down your code. For that, it
gives you a class decorator and a way to declaratively define the
attributes on that class:


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/nsls2forge/nsls2forge/_build/latest?definitionId=28&branchName=master">
        <img src="https://dev.azure.com/nsls2forge/nsls2forge/_apis/build/status/attrs-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-attrs-green.svg)](https://anaconda.org/nsls2forge/attrs) | [![Conda Downloads](https://img.shields.io/conda/dn/nsls2forge/attrs.svg)](https://anaconda.org/nsls2forge/attrs) | [![Conda Version](https://img.shields.io/conda/vn/nsls2forge/attrs.svg)](https://anaconda.org/nsls2forge/attrs) | [![Conda Platforms](https://img.shields.io/conda/pn/nsls2forge/attrs.svg)](https://anaconda.org/nsls2forge/attrs) |

Installing attrs
================

Installing `attrs` from the `nsls2forge` channel can be achieved by adding `nsls2forge` to your channels with:

```
conda config --add channels nsls2forge
```

Once the `nsls2forge` channel has been enabled, `attrs` can be installed with:

```
conda install attrs
```

It is possible to list all of the versions of `attrs` available on your platform with:

```
conda search attrs --channel nsls2forge
```




Updating attrs-feedstock
========================

If you would like to improve the attrs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`nsls2forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `nsls2forge` channel.
Note that all branches in the nsls-ii-forge/attrs-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@CJ-Wright](https://github.com/CJ-Wright/)
* [@jochym](https://github.com/jochym/)
* [@licode](https://github.com/licode/)
* [@nicoddemus](https://github.com/nicoddemus/)

