About socat
===========

Home: http://www.dest-unreach.org/socat/

Package license: GPL-2.0-or-later

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/socat-feedstock/blob/master/LICENSE.txt)

Summary: A relay for bidirectional transfer between data channels (netcat++)

Development: http://repo.or.cz/r/socat.git

Documentation: http://www.dest-unreach.org/socat/doc/README

socat is a relay for bidirectional data transfer between two independent data
channels. Each of these data channels may be a file, pipe, device (serial line
etc. or a pseudo terminal), a socket (UNIX, IP4, IP6 - raw, UDP, TCP), an
SSL socket, proxy CONNECT connection, a file descriptor (stdin etc.), the GNU
line editor (readline), a program, or a combination of two of these.
These modes include generation of "listening" sockets, named pipes, and pseudo
terminals.

socat can be used, e.g., as TCP port forwarder (one-shot or daemon), as an
external socksifier, for attacking weak firewalls, as a shell interface to UNIX
sockets, IP6 relay, for redirecting TCP oriented programs to a serial line, to
logically connect serial lines on different computers, or to establish a
relatively secure environment (su and  chroot) for running client or server
shell scripts with network connections.


Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
            <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_openssl1.1.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_64_openssl1.1.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_openssl3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_64_openssl3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_openssl1.1.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_openssl1.1.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_aarch64_openssl3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_aarch64_openssl3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_openssl1.1.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_openssl1.1.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_ppc64le_openssl3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=linux&configuration=linux_ppc64le_openssl3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_openssl1.1.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=osx&configuration=osx_64_openssl1.1.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_openssl3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=osx&configuration=osx_64_openssl3" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_openssl1.1.1</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_openssl1.1.1" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_arm64_openssl3</td>
              <td>
                <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=1935&branchName=master">
                  <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/socat-feedstock?branchName=master&jobName=osx&configuration=osx_arm64_openssl3" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-socat-green.svg)](https://anaconda.org/conda-forge/socat) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/socat.svg)](https://anaconda.org/conda-forge/socat) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/socat.svg)](https://anaconda.org/conda-forge/socat) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/socat.svg)](https://anaconda.org/conda-forge/socat) |

Installing socat
================

Installing `socat` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `socat` can be installed with:

```
conda install socat
```

It is possible to list all of the versions of `socat` available on your platform with:

```
conda search socat --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.com/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating socat-feedstock
========================

If you would like to improve the socat recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/socat-feedstock are
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

* [@sodre](https://github.com/sodre/)

