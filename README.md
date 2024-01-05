# ducktools #

This is a namespace project that will install *all* ducktools modules.

This mostly exists to make sure that 'ducktools' on pip installs ducktools namespaced projects 
and isn't used by someone else in the future. 
`pip install ducktools` will install the latest versions of *all* modules I have created under the
ducktools namespace.

If you are using one of the modules in a project it is recommended to depend on that module directly.

Included modules:
* [ducktools-lazyimporter](https://github.com/DavidCEllis/ducktools-lazyimporter)

## Licensing ##

Individual components of ducktools may be licensed under more permissive (non-copyleft) licences
this namespace package uses GPLv3 as the least permissive license any included project may use.
