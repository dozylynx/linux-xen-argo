#
# Copyright (c) 2010 Citrix Systems, Inc.
# Modifications by Christopher Clark, Copyright (c) 2018 BAE Systems
# 
# This library is free software; you can redistribute it and/or
# modify it under the terms of the GNU Lesser General Public
# License as published by the Free Software Foundation; either
# version 2.1 of the License, or (at your option) any later version.
# 
# This library is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
# Lesser General Public License for more details.
# 
# You should have received a copy of the GNU Lesser General Public
# License along with this library; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301  USA
#

AM_CPPFLAGS = -I$(srcdir)/../src
AM_CFLAGS = -g

bin_PROGRAMS = ttcp-argo argo-proxy viptables

ttcp_argo_SOURCES = ttcp.c
ttcp_argo_LDADD = ../src/libargo.la

argo_proxy_SOURCES = proxy.c
argo_proxy_LDADD = ../src/libargo.la

viptables_SOURCES = viptables.c
viptables_LDADD = ../src/libargo.la
