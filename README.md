LAVA Landing Tests
==================

Script that runs various kinds of tests before landing branches proposed to
various LAVA projects. The script sets up a basic test environment and then
proceeds to do additional setup and tests according to the ci-info meta data.

The meta-data can be either right in the tree (which is not the case as of this
time) of the tested LAVA project or be specified externally (like the one in
this repository)

Usage
=====

    git clone https://github.com/zyga/lava-landing-tests.git
    bzr branch lp:lava-tool
    ./lava-landing-tests/run-ci-tests lava-tool lava-landing-tests/lava-tool.ci-info

