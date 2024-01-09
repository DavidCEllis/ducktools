# ducktools #

This is a namespace project that will install *all* ducktools modules.

This mostly exists to make sure that 'ducktools' on pip installs all ducktools namespaced projects in the case
that someone types `pip install ducktools`.

If you are using one of the modules in a project it is recommended to depend on that module directly.

Modules are not versioned under this meta package, it will always install the newest version
of all included modules.

Included modules:
* [ducktools-lazyimporter](https://github.com/DavidCEllis/ducktools-lazyimporter)
* [ducktools-jsonkit](https://github.com/DavidCEllis/ducktools-jsonkit)
* [ducktools-scriptmetadata](https://pypi.org/project/ducktools-scriptmetadata/)


## Licensing ##

Individual components of ducktools may be licensed under more permissive (non-copyleft) licences
this namespace package uses GPLv3 as the least permissive license any included project may use.
