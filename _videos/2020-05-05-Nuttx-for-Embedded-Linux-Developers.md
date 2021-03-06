---
title: NuttX for Embedded Linux Developers - Masayuki Ishikawa, Sony
youtube_id: huzhQrwJF4A
date: 2020-05-05
category: dev
tags: [Embedded, Linux, Linux Foundation]
---

NuttX for Embedded Linux Developers - Masayuki Ishikawa, Sony

NuttX is an open source POSIX-compliant RTOS suitable for resource constrained devices and real-time systems (such as Drones and robotics) where Linux can be difficult to use. However, NuttX has rich features such as shell, libc, pipe, poll, signal, vfs, pthread, networking, and smp and includes many example applications. You can easily port many Linux applications to NuttX and use the same code to target both OSes. Drivers are accessed with open, read, write, ioctl and close operations, the same as in Linux.

In this talk, I will describe how Sony uses NuttX in shipped audio products (since 2015) and in research for future products including SMP systems and Networking (USB RNDIS and Bluetooth PAN). We were able to confirm Linux application portability to NuttX, by porting the Alexa/AVS device SDK to NuttX on an LC823450XGEVK board - a Cortex-M3 with 1.6MB SRAM, 16 MB flash running at 160 MHZ. The SDK consists of several pieces, such as curl, libc++, sqlite3, nghttp2, mbedtls. We found that by reducing run-time memory, this SDK could run on such a small device. We also implemented NuttX on a Sony Spresense board, a 6-core Cortex-M4F processor, and are in the process of upstreaming this work to the NuttX mainline.

Finally, I'll report on the 1st NuttX international workshop held in the Netherlands in July of this year. We found that many developers write and test their application code on Linux then deploy it to NuttX. We will describe this useful approach for targeting systems where it is infeasible to use Linux.