# See /LICENSE for more information.
# This is free software, licensed under the GNU General Public License v2.

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI support for attended sysupgrades
LUCI_DEPENDS:=+luci-base +uhttpd-mod-ubus +attendedsysupgrade-common +cgi-io
LUCI_MINIFY_JS:=0

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
