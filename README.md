# ducktools #

This is a namespace project that will install *all* ducktools modules.

This mostly exists to make sure that 'ducktools' on pip installs all ducktools namespaced projects in the case
that someone types `pip install ducktools`.

If you are using one of the modules in a project it is highly recommended to depend on that module directly.

Modules are not versioned under this meta package, it will always install the newest version
of all included modules.

Included modules:
* [ducktools-classbuilder](https://pypi.org/project/ducktools-classbuilder/)
* [ducktools-env](https://pypi.org/project/ducktools-env/)
* [ducktools-jsonkit](https://pypi.org/project/ducktools-jsonkit/)
* [ducktools-lazyimporter](https://pypi.org/project/ducktools-lazyimporter/)
* [ducktools-pythonfinder](https://pypi.org/project/ducktools-pythonfinder/)
* [ducktools-pytui](https://pypi.org/project/ducktools-pytui)
* [ducktools-scriptmetadata](https://pypi.org/project/ducktools-scriptmetadata/)

## Licensing ##

All ducktools components are licenced under the MIT License, so this metapackage has been updated to also use the MIT License.
