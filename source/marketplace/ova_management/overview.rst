.. _ova_management_overview:

====================
Overview
====================

OpenNebula supports importing OVAs that have been exported from vCenter / ESXi environments, generating the necessary VM Template and Images.

It is possible to import `.ova` files or a folder containing the OVF files (VMDK disk files and manifest file in `.ovf` format). The import tool will inject context packages in the target Images, automatically detecting the guest operating system.

