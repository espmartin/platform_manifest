platform_manifest
=================
SCHUTZHUNDAOKP:
==============
Getting Started:

If you want to build your own Android AOKP for the HTC Ace, study up on Git and Repo.

First, initialize your local repository using the AOKP tree. At the terminal prompt, type:

     repo init -u git://github.com/AOKP/platform_manifest.git -b kitkat
                  
Sync is next:

     repo sync

ONLY if supporting multiple kernels:

. ./platform_manifest/manual_add_kernel_manifest.sh

Please note that I take NO responsibility for your phone being "bricked"! Study up :-)
