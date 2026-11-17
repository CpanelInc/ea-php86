SRCDIR := $(shell pwd)
NAME := $(shell basename $(SRCDIR))
include ../../common/Makefile

srpm:
	rpmbuild $(RPMDEFINES) $(SRCDEFINES) --define 'scl php86' -bs $(NAME).spec
