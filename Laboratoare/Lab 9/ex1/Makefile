KDIR = TODO
 
kbuild:
	make -C $(KDIR) M=`pwd`
 
clean:
	make -C $(KDIR) M=`pwd` clean
	rm -f *~ Module.symvers Module.markers modules.order
