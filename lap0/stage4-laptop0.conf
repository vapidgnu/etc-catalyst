## Static settings
subarch: amd64
target: stage4
rel_type: default
profile: default/linux/amd64/17.0/desktop
cflags: -O2 -pipe -march=bdver2
portage_confdir: /srv/build/laptop0/portage

#update_seed: yes
#update_seed_command: --update --deep @world

##TODO drasticly needs to not be hard coded, like WTF. 
## Dynamic settings (might be passed on as parameters instead)
# Name of the "seed" stage3 file to use
source_subpath: stage3-amd64-current

# Name of the portage snapshot to use
snapshot: portage-current
# Timestamp to use on your resulting stage3 file
version_stamp: dotcustomed


stage4/packages:
	net-misc/dhcp
	net-misc/iputils
	sys-boot/grub
	sys-apps/gptfdisk
	sys-apps/iproute2
	sys-devel/bc
	sys-power/acpid
	app-crypt/gentoo-keys
