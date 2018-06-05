obj-m := led.o

KDIR =  /root/linux

PWD := $(shell pwd)

default:
	$(MAKE) ARCH=$(ARCH) CROSS_COMPILE=$(CROSS_COMPILE) -C $(KDIR) SUBDIRS=$(PWD) modules

clean:
	$(MAKE) -C $(KDIR) SUBDIRS=$(PWD) clean

#make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf-
