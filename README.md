
## pyFlow -- a lightweight parallel task engine


This is the root of the pyflow development repository. Note this is not
the pyflow distribution tarball.

Recent release tarballs can be found on the github release list here:

https://github.com/sequencing/pyflow/releases


To create a release tarball corresponding to any other version, run:

    git clone git://github.com/sequencing/pyflow.git pyflow
    cd pyflow
    git checkout ${VERSION}
    ./scratch/make_release_tarball.bash
    # tarball is "./pyflow-${VERSION}.tar.gz"

### Contents

For the development repository (this directory), the sub-directories are:

pyflow/

Contains all pyflow code intended for distribution, plus demo code and
documentation.

scratch/

This directory contains support scripts for tests/cleanup/release tarballing.. etc.

