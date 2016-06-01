---
layout: docs
title:  Installing Streams Quick Start Edition VM Image
description:  Installation Guide for IBM Streams Quick Start Edition VM
weight:  20
published: false
---

The Streams Quick Start Edition Virtual Machine can help you get started with Streams quickly, without having to install a Streams cluster environment.

{% include download.html%}
<br>
This guide takes you through the process of installing and starting the QSE VM image.

## System Requirements

| Components  | Minimum Requirements | Comments |
| ----------- | -------------------- | -------------|
| Operating System  | 64-bit operating system that supports importing Open Virtualization Format (OVF) images such as VMware or VirtualBox  | VMware and/or VirtualBox are supported on the following operating systems: <br>- Apple Mac OS X <br>- Linux <br>- Microsoft Windows
| Memory	  |8 GB	                 |The amount of memory that is required by IBM Streams is dependent on the applications that are developed and deployed.  This minimum requirement is based on the memory requirements of the Commodity Purchasing sample application and other samples that are provided with the product.     
| Disk space  | 20 GB |  |
| VMware or VirtualBox product | VM product that runs on a 64-bit operating system	| The Quick Start Edition VM image should run in one of the following products:<br> - VMware Workstation or Player 8, or later, for Microsoft Windows<br> - VMware Fusion 8, or later, for Apple Mac OS X<br> - VirtualBox 5, or later, for Apple Mac OS X, Microsoft Windows or Linux

## Before you begin

Your Streams ID for the Quick Start Edition is **streamsadmin**, and your password is **passw0rd**. The root ID password is also **passw0rd**.

The Quick Start Edition is only available in English.

**Performance notes:**

* By default, the Quick Start Edition virtual machine is configured to have two processor cores and 4 GB of memory. Depending on your system resources and the applications that you develop and deploy, you might be able to improve performance by allocating more processor cores and memory to the virtual machine. You can adjust the processor and memory configuration by updating your VM settings.

* If you have performance problems with the virtual machine, enable any available options that can reduce guest disk input/output latency. For example, in VirtualBox, select the Use Host I/O Cache option in the Storage Controller settings for the VM.

## Procedure

1.  Download the vm-streamsVxxx.ova file (where Vxxx is the version number of the Quick Start Edition).

1.  Import the .ova file into your VM product:

    VMware: File -> Import
    
    VirtualBox: File -> Import 

1.  The first time that you start the image, respond to the following prompts:

    1.  To continue, accept all of the following license agreements:

        * CentOS
        * IBM® Streams

    To navigate in the license agreement screens, use the **Tab** and **Arrow** keys. Press the **Enter** key to continue.

    After you accept the license agreements, status messages are displayed and the Quick Start Edition VM image desktop opens.

## What to do next

Explore the Streams QSE VM image following the [Quick Start Edition VM Getting Started Guide](/streamsx.documentation/docs/latest/qse-getting-started/)
