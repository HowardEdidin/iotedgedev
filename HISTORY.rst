=======
History
=======

0.82.0 (2018-08-28)
-------------------

Added
^^^^^

* New command to add modules to solution
* Support for adding and building Node.js and Python modules
* Integration with IoT Edge Simulator provided by the `iotedgehubdev CLI <https://pypi.org/project/iotedgehubdev/>`_
* Allow specifying name and template of the default module when creating new solutions
* Support for build options in ``module.json`` file
* Support for customized context path in ``module.json`` file
* Support for multiple registries in ``.env`` file
* Support for GA release of IoT Edge runtime in IoT Edge Dev Container
* Update ``.vscode/launch.json`` file when adding modules

Changed
^^^^^^^

* Switch to Azure CLI IoT extension (>= 0.5.1) to monitor messages for Python >= 3.5 users
* Improve experience of creating Azure resources interactively
* Breaking changes (learn how to migrate `here <https://github.com/Azure/iotedgedev/wiki/migration-guides>`_\ )

  * Updated command list and options
  * Updated logic to determine which module images to build
  * New module folder structure
  * Building code in Dockerfiles instead of building code natively

Removed
^^^^^^^

* Support for ``iotedgectl`` and public preview runtime images


0.1.0 (2017-12-29)
------------------

- First release on PyPI.
