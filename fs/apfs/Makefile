# SPDX-License-Identifier: GPL-2.0-only
#
# Makefile for APFS support in kernel


obj-$(CONFIG_APFS_FS) = apfs.o

# Define to always mount read-write
ccflags-$(CONFIG_APFS_RW_ALWAYS) := -DCONFIG_APFS_RW_ALWAYS

apfs-objs := btree.o compress.o dir.o extents.o file.o inode.o key.o libzbitmap.o \
	     lzfse/lzfse_decode.o lzfse/lzfse_decode_base.o lzfse/lzfse_fse.o \
	     lzfse/lzvn_decode_base.o message.o namei.o node.o object.o snapshot.o \
	     spaceman.o super.o symlink.o transaction.o unicode.o xattr.o xfield.o
