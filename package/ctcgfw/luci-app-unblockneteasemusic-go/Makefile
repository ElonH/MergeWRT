# Copyright (C) 2016 Openwrt.org
#
# This is a free software, use it under GNU General Public License v3.0.
#
# Created By [CTCGFW]Project-OpenWrt
# https://github.com/project-openwrt

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for UnblockNeteaseMusic-Go
LUCI_DEPENDS:=+bash +busybox +coreutils-nohup +curl +dnsmasq-full +ipset +UnblockNeteaseMusic-Go
LUCI_PKGARCH:=all
PKG_NAME:=luci-app-unblockneteasemusic-go
PKG_VERSION:=1.0
PKG_RELEASE:=1

PKG_MAINTAINER:=[CTCGFW]Project-OpenWrt

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
