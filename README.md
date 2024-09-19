# 46load

lil' silly i386  MBR bootsector bootloader with very basic support of ext2 filesystem and capable of loading simple ELF kernels

## Features ✨
 * load kernel executable into memory from root of selected partition
 * basic ext2 support, its currently limited only to load first 12 blocks of file(12-96KB of disk space) and only from root directory
 * entering PM
 * ✨ fancy 0x07bad GDT address
 * ✨ it wouldn't enable a20 line unless you patch it yourself

## Building

To build 46load you need to have a bsdmake. Build is untested in anything except FreeBSD tho.

Just enter `make` to build it.
