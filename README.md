# hello-s
This is a git superproject which is used to source-control multiple applications that are structured by using git submodules. The main assumption is that there are many submodules and there is a great overlap in using them in the applications. 

Benefits of this structure:
1. The developers only clone the repository (including the submodules) to one place in order to work on __all__ applications.
1. The developers can easily merge commits that were done to submodules for one application (branch) to other application's branches if they need to. 

