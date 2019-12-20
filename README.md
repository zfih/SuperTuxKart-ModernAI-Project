# SuperTuxKart-ModernAI-Project
Combined project of all necessary things for the ModernAI project about SuperTuxKart

When cloning, remember to use the following command to ensure that the complete
project is cloned.

```git clone https://github.com/zfih/SuperTuxKart-ModernAI-Project --recurse-submodules```


## Repos:
The repo is made up of a series of repos.
- *stk-code-mai*: is the code repo, cloned from original stk and going off from
their 1.0 branch.

	The code related to this project, including all the `torch` code is in the `/stk-code-mai/src/mai-engine/` folder
- *stk-assets*: is the assets repo, this repo should be downloaded here by using
the command

```svn checkout https://svn.code.sf.net/p/supertuxkart/code/stk-assets stk-assets```

The repo is not suited for git and therefore not added to the this repo
- *dependencies*: the dependecies needed to compile on some platforms. Using
these are instructed in the INSTALL.md for stk-code-mai and the Win64
dependencies have already been moved

## Compilation and running
* stk-code-mai has an `INSTALL.md` file with instructions as to how to build.
The mentioned dependecies folder is included in this repo.