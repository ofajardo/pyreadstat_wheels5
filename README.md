# pyreadstat_wheels5
Wheels for Pyreadstat based on cibuildwheel

This repo is used to build Python wheels for Pyreadstat for 
linux, mac and windows. 

The file controlling the workflow is in .github/workflows/wheels.yml.
There is a file for windows in .github/actions/windows_actions/action.yml.

Wheels are uploaded as artifacts to github and also to [anaconda](https://anaconda.org/ofajardo/pyreadstat),
where they are publicly available. 

Later wheels are uploaded manually to Pypi. This is to allow anaconda to be a source for testing wheels before releasing. 
