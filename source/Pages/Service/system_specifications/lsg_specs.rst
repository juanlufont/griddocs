.. warning:: Page under construction

.. _specs-lsg:

******************
LSG Specifications
******************

This page describes the specifications for the life science grid clusters. For a list of the clusters, see :ref:`life-science-clusters`.

.. contents:: 
    :depth: 4

If you have any questions concerning the technical specifications below, please contact us at helpdesk@surfsara.nl.


.. _dcache-lsg-summary:


Quick summary
============= 

============================ =====================================================
LSG cluster                  Capacity                                             
============================ =====================================================
Operating System             Linux CentOS 6.x 64bit
Total number of cores        128 CPU cores at 2.3 GHz
Total amount of memory       512 GB
Total scratch space          10TB
Disk storage                 40TB of staging area                             
Network backbone             10Gbit/s local switch, 1Gbit/s external connectivity
============================ =====================================================


Service Nodes
=============
* PowerEdge R420 2xIntel(R) Xeon(R) CPU E5-2420 0 @ 1.90GHz
* Type: 
* Cores: 24
* RAM: 96 GB
* Number of nodes: 2


Worker Nodes
============
* PowerEdge R815 4xAMD Opteron(tm) Processor 6376
* Type: 
* Cores: 64
* RAM: 256GB
* Number of nodes: 2


Storage Node
============
* PowerEdge R515 2xAMD Opteron(tm) Processor 4280
* Type: 
* Cores: 16
* RAM: 128 GB
* Number of nodes: 1


Queues
======
 
=============== ===========================
Queue           Max. Walltime (hh:mm:ss)
=============== ===========================
express         00:30:00
infra           00:30:00
medium          36:00:00
long            72:00:00
=============== ===========================
