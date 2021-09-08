build:
	dtc -I dts -O dtb -Wno-unit_address_vs_reg -o bttdpi.dtbo bttdpi.dts

install:
	cp bttdpi.dtbo /boot/overlays/

test:
	dtoverlay bttdpi.dtbo
