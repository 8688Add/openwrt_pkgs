# SPDX-License-Identifier: Apache-2.0
#
# Copyright (C) 2023 ImmortalWrt.org

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-ddns-go
PKG_VERSION:=1.3.2
PKG_RELEASE:=10

LUCI_TITLE:=LuCI Support for Dynamic ddns-go Client
LUCI_DEPENDS:=+ddns-go
LUCI_PKGARCH:=all

define Package/$(PKG_NAME)/conffiles
/etc/config/ddns-go
/etc/ddns-go/ddns-go-config.yaml
endef

include $(TOPDIR)/feeds/luci/luci.mk
# call BuildPackage - OpenWrt buildroot signature
