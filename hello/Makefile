include $(APPDIR)/Make.defs

# Hello, World! built-in application info

CONFIG_APP_HELLO_PRIORITY ?= SCHED_PRIORITY_DEFAULT
CONFIG_APP_HELLO_STACKSIZE ?= 2048

APPNAME = hello
PRIORITY = $(CONFIG_APP_HELLO_PRIORITY)
STACKSIZE = $(CONFIG_APP_HELLO_STACKSIZE)

# Hello, World! Example

ASRCS =
CSRCS =
MAINSRC = hello_main.c

CONFIG_APP_HELLO_PROGNAME ?= hello$(EXEEXT)
PROGNAME = $(CONFIG_APP_HELLO_PROGNAME)

include $(APPDIR)/Application.mk
