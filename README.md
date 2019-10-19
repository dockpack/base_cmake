Role Name
=========

An Ansible role to fetch and install the latest CMake tarball from the [www.cmake.org](http://www.cmake.org) website.

Requirements
------------

None

Role Variables
--------------

* `cmake_version`  *3.15.4* The version of CMake to fetch from [cmake.org](http://www.cmake.org)
* `cmake_dest_dir`  */opt/cmake* Where to install the CMake tarball
* `cmake_modify_path`  *True* Add CMake's PATH to .bashrc?

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: dockpack.base_cmake, cmake_version: 3.15.4 }

License
-------

BSD

Author Information
------------------

Keith Fieldhouse
keith.fieldhouse@kitware.com

Bas Meijer
bas.meijer@me.com
