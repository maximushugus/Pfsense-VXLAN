To build the VXLAN kernel module:
---------------------------------

1) You need a FreeBSD machine (or VM)
2) Clone Pfsense src on this FreeBSD machine using the exact same branch as your Pfsense version
for Pfsense CE 2.7.2 :
git clone --branch RELENG_2_7_2 https://github.com/pfsense/FreeBSD-src.git /usr/src/
3) cd /usr/src/sys/modules/if_vxlan
4) Run make
You will find kernel module "if_vxlan.ko" file in /usr/obj/directory.
See INSTALL.md to install it.
