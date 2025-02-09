Pfsense VXLAN implementation:
-----------------------------
This is a repository to add VXLAN support to Pfsense (at the moment Pfsense CE 2.7.2 doesn't support VXLAN).
In this repository you will find a kernel module enabling VXLAN support for Pfsense CE 2.7.2, and adding VXLAN support to the web GUI.

Installation:
-------------
To install VXLAN on Pfsense CE 2.7.2, see INSTALL.md

Build from sources:
-------------------
If you want, you can build the kernel module from sources : see BUILD.md

Sources:
--------
[Pfsense sources](https://github.com/pfsense/FreeBSD-src).

[FreeBSD sources](https://github.com/freebsd/freebsd-src).

[Old Pfsense commit retiring VXLAN support](https://github.com/pfsense/pfsense/commit/3856366b4fb3823d02108c0ee63043509a89e0db#diff-fd0fa0ced9988433dfb5aad36a981839ebe69aa0224a5b86210200706dc30c82).
