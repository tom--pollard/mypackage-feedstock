About mypackage
===============

Home: 

Package license: 

Feedstock license: BSD-3-Clause

Summary: 



Current build status
====================


<table><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/tom--pollard/mypackage-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/tom--pollard/mypackage-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr>
  <tr>
    <td>OSX</td>
    <td>
      <img src="https://img.shields.io/badge/OSX-disabled-lightgrey.svg" alt="OSX disabled">
    </td>
  </tr>
  <tr>
    <td>Windows</td>
    <td>
      <img src="https://img.shields.io/badge/Windows-disabled-lightgrey.svg" alt="Windows disabled">
    </td>
  </tr>
  <tr>
    <td>Linux_ppc64le</td>
    <td>
      <img src="https://img.shields.io/badge/ppc64le-disabled-lightgrey.svg" alt="ppc64le disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-mypackage-green.svg)](https://anaconda.org/anaconda_channel_name/mypackage) | [![Conda Downloads](https://img.shields.io/conda/dn/anaconda_channel_name/mypackage.svg)](https://anaconda.org/anaconda_channel_name/mypackage) | [![Conda Version](https://img.shields.io/conda/vn/anaconda_channel_name/mypackage.svg)](https://anaconda.org/anaconda_channel_name/mypackage) | [![Conda Platforms](https://img.shields.io/conda/pn/anaconda_channel_name/mypackage.svg)](https://anaconda.org/anaconda_channel_name/mypackage) |

Installing mypackage
====================

Installing `mypackage` from the `anaconda_channel_name` channel can be achieved by adding `anaconda_channel_name` to your channels with:

```
conda config --add channels anaconda_channel_name
```

Once the `anaconda_channel_name` channel has been enabled, `mypackage` can be installed with:

```
conda install mypackage
```

It is possible to list all of the versions of `mypackage` available on your platform with:

```
conda search mypackage --channel anaconda_channel_name
```




Updating mypackage-feedstock
============================

If you would like to improve the mypackage recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`anaconda_channel_name` channel, whereupon the built conda packages will be available for
everybody to install and use from the `anaconda_channel_name` channel.
Note that all branches in the tom--pollard/mypackage-feedstock are
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


