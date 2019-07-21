# flava
Java 8 and 11 packaged as a Flatpak with support for Java Web Start (Icedtea) and FX applications.

## why
I use java web start files reguarly at work for managing servers, however IcedTea does not run very well in a container and containers don't integrate with desktops.

This uses prebuilt Java builds from Liberica, which are based on OpenJDK.

## usage

When installed, just double click .jar and .jnlp files. 

## Broken

- Minecraft
- File Forwarding