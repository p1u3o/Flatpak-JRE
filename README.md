# flava
This is java 8 and 11 packaged as a Flatpak with support for Java Web Start (Icedtea) and FX applications.

## why
I use java web start files reguarly at work for managing our servers, unfortunately IcedTea does not run very well in a container and containers don't integrate with desktops.

This uses prebuilt java builds from Liberica, which are based on OpenJDK. They're 100% open source and include JavaFX which is a pain to compile.

## How to use

When installed, just double click .jar and .jnlp files. 

## Broken

Minecraft
File Forwarding