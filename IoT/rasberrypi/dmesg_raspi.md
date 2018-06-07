$ sudo dmesg | more
~~~
[    0.053137] [bcm2709_secondary_init] enter cpu:1
[    0.053181] CPU1: update cpu_capacity 1024
[    0.053188] CPU1: thread -1, cpu 1, socket 0, mpidr 80000001
[    0.053562] [bcm2709_boot_secondary] cpu:2 started (0) 18
[    0.053725] [bcm2709_secondary_init] enter cpu:2
[    0.053746] CPU2: update cpu_capacity 1024
[    0.053752] CPU2: thread -1, cpu 2, socket 0, mpidr 80000002
[    0.054111] [bcm2709_boot_secondary] cpu:3 started (0) 17
[    0.054240] [bcm2709_secondary_init] enter cpu:3
[    0.054261] CPU3: update cpu_capacity 1024
[    0.054267] CPU3: thread -1, cpu 3, socket 0, mpidr 80000003
[    0.054326] Brought up 4 CPUs
[    0.054349] SMP: Total of 4 processors activated (153.60 BogoMIPS).
[    0.054358] CPU: All CPU(s) started in HYP mode.
[    0.054365] CPU: Virtualization extensions available.
[    0.054978] devtmpfs: initialized
[    0.066150] VFP support v0.3: implementor 41 architecture 3 part 40 variant 3 rev 4
[    0.066491] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 19112604462750000 ns
[    0.067186] pinctrl core: initialized pinctrl subsystem
[    0.067716] NET: Registered protocol family 16
[    0.072961] DMA: preallocated 4096 KiB pool for atomic coherent allocations
[    0.080049] hw-breakpoint: found 5 (+1 reserved) breakpoint and 4 watchpoint registers.
[    0.080060] hw-breakpoint: maximum watchpoint size is 8 bytes.
[    0.080211] Serial: AMBA PL011 UART driver
[    0.080351] uart-pl011 3f201000.uart: could not find pctldev for node /soc/gpio@7e200000/uart0_pins, deferring probe
[    0.080515] bcm2835-mbox 3f00b880.mailbox: mailbox enabled
[    0.143264] bcm2835-dma 3f007000.dma: DMA legacy API manager at f3007000, dmachans=0x1
[    0.143841] SCSI subsystem initialized
[    0.144032] usbcore: registered new interface driver usbfs
[    0.144122] usbcore: registered new interface driver hub
[    0.144220] usbcore: registered new device driver usb
[    0.150702] raspberrypi-firmware soc:firmware: Attached to firmware from 2017-04-05 11:49
[    0.177903] clocksource: Switched to clocksource arch_sys_counter
[    0.222615] FS-Cache: Loaded
[    0.222886] CacheFiles: Loaded
[    0.235193] NET: Registered protocol family 2
[    0.236046] TCP established hash table entries: 8192 (order: 3, 32768 bytes)
[    0.236160] TCP bind hash table entries: 8192 (order: 4, 65536 bytes)
[    0.236349] TCP: Hash tables configured (established 8192 bind 8192)
[    0.236442] UDP hash table entries: 512 (order: 2, 16384 bytes)
[    0.236488] UDP-Lite hash table entries: 512 (order: 2, 16384 bytes)
[    0.236718] NET: Registered protocol family 1
[    0.237040] RPC: Registered named UNIX socket transport module.
[    0.237051] RPC: Registered udp transport module.
[    0.237059] RPC: Registered tcp transport module.
[    0.237067] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    0.238244] hw perfevents: enabled with armv7_cortex_a7 PMU driver, 7 counters available
[    0.239573] futex hash table entries: 1024 (order: 4, 65536 bytes)
[    0.252770] VFS: Disk quotas dquot_6.6.0
[    0.253082] VFS: Dquot-cache hash table entries: 1024 (order 0, 4096 bytes)
[    0.255299] FS-Cache: Netfs 'nfs' registered for caching
[    0.256206] NFS: Registering the id_resolver key type
[    0.256246] Key type id_resolver registered
[    0.256256] Key type id_legacy registered
[    0.258594] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 252)
[    0.258725] io scheduler noop registered
[    0.258743] io scheduler deadline registered (default)
[    0.258795] io scheduler cfq registered
[    0.261311] BCM2708FB: allocated DMA memory fac10000
[    0.261336] BCM2708FB: allocated DMA channel 0 @ f3007000
[    0.298304] Console: switching to colour frame buffer device 160x64
[    0.320798] bcm2835-rng 3f104000.rng: hwrng registered
[    0.320896] vc-cma: Videocore CMA driver
[    0.320905] vc-cma: vc_cma_base      = 0x00000000
[    0.320914] vc-cma: vc_cma_size      = 0x00000000 (0 MiB)
[    0.320923] vc-cma: vc_cma_initial   = 0x00000000 (0 MiB)
[    0.321145] vc-mem: phys_addr:0x00000000 mem_base=0x3dc00000 mem_size:0x3f000000(1008 MiB)
[    0.335995] brd: module loaded
[    0.344642] loop: module loaded
[    0.345554] vchiq: vchiq_init_state: slot_zero = 0xbac80000, is_master = 0
[    0.347081] Loading iSCSI transport class v2.0-870.
[    0.347739] usbcore: registered new interface driver smsc95xx
[    0.347793] dwc_otg: version 3.00a 10-AUG-2012 (platform bus)
[    0.548158] Core Release: 2.80a
[    0.548171] Setting default values for core params
[    0.548206] Finished setting default values for core params
[    0.748577] Using Buffer DMA mode
[    0.748588] Periodic Transfer Interrupt Enhancement - disabled
[    0.748596] Multiprocessor Interrupt Enhancement - disabled
[    0.748605] OTG VER PARAM: 0, OTG VER FLAG: 0
[    0.748619] Dedicated Tx FIFOs mode
[    0.748953] WARN::dwc_otg_hcd_init:1047: FIQ DMA bounce buffers: virt = 0xbac04000 dma = 0xfac04000 len=9024
[    0.748984] FIQ FSM acceleration enabled for :
Non-periodic Split Transactions
Periodic Split Transactions
High-Speed Isochronous Endpoints
Interrupt/Control Split Transaction hack enabled
[    0.749007] dwc_otg: Microframe scheduler enabled
[    0.749050] WARN::hcd_init_fiq:415: FIQ on core 1 at 0x80448d28
[    0.749064] WARN::hcd_init_fiq:416: FIQ ASM at 0x80449098 length 36
[    0.749078] WARN::hcd_init_fiq:441: MPHI regs_base at 0xbb87e000
[    0.749139] dwc_otg 3f980000.usb: DWC OTG Controller
[    0.749176] dwc_otg 3f980000.usb: new USB bus registered, assigned bus number 1
[    0.749212] dwc_otg 3f980000.usb: irq 62, io mem 0x00000000
[    0.749262] Init: Port Power? op_state=1
[    0.749270] Init: Power Port (0)
[    0.749471] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002
[    0.749486] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    0.749499] usb usb1: Product: DWC OTG Controller
[    0.749511] usb usb1: Manufacturer: Linux 4.4.50-v7+ dwc_otg_hcd
[    0.749523] usb usb1: SerialNumber: 3f980000.usb
[    0.750302] hub 1-0:1.0: USB hub found
[    0.750345] hub 1-0:1.0: 1 port detected
[    0.751006] dwc_otg: FIQ enabled
[    0.751016] dwc_otg: NAK holdoff enabled
[    0.751024] dwc_otg: FIQ split-transaction FSM enabled
[    0.751058] Module dwc_common_port init
[    0.751312] usbcore: registered new interface driver usb-storage
[    0.751602] mousedev: PS/2 mouse device common for all mice
[    0.752350] bcm2835-cpufreq: min=600000 max=1200000
[    0.752650] sdhci: Secure Digital Host Controller Interface driver
[    0.752659] sdhci: Copyright(c) Pierre Ossman
[    0.752976] sdhost: log_buf @ bac07000 (fac07000)
[    0.807935] mmc0: sdhost-bcm2835 loaded - DMA enabled (>1)
[    0.810212] mmc-bcm2835 3f300000.mmc: mmc_debug:0 mmc_debug2:0
[    0.810225] mmc-bcm2835 3f300000.mmc: DMA channel allocated
[    0.868016] sdhci-pltfm: SDHCI platform and OF driver helper
[    0.868392] ledtrig-cpu: registered to indicate activity on CPUs
[    0.868499] hidraw: raw HID events driver (C) Jiri Kosina
[    0.868676] usbcore: registered new interface driver usbhid
[    0.868685] usbhid: USB HID core driver
[    0.869250] Initializing XFRM netlink socket
[    0.869285] NET: Registered protocol family 17
[    0.869429] Key type dns_resolver registered
[    0.870029] Registering SWP/SWPB emulation handler
[    0.870777] registered taskstats version 1
[    0.870976] vc-sm: Videocore shared memory driver
[    0.870993] [vc_sm_connected_init]: start
[    0.871500] [vc_sm_connected_init]: end - returning 0
[    0.872857] 3f201000.uart: ttyAMA0 at MMIO 0x3f201000 (irq = 87, base_baud = 0) is a PL011 rev2
[    0.873260] of_cfs_init
[    0.873344] of_cfs_init: OK
[    0.874165] Waiting for root device PARTUUID=45561e69-02...
[    0.907864] mmc0: host does not support reading read-only switch, assuming write-enable
[    0.910734] mmc0: new high speed SDXC card at address aaaa
[    0.911301] mmcblk0: mmc0:aaaa SE64G 59.5 GiB
[    0.912744]  mmcblk0: p1 p2
[    0.930628] mmc1: queuing unknown CIS tuple 0x80 (2 bytes)
[    0.932187] mmc1: queuing unknown CIS tuple 0x80 (3 bytes)
[    0.933739] mmc1: queuing unknown CIS tuple 0x80 (3 bytes)
[    0.936523] mmc1: queuing unknown CIS tuple 0x80 (7 bytes)
[    0.948020] Indeed it is in host mode hprt0 = 00021501
[    1.020468] EXT4-fs (mmcblk0p2): mounted filesystem with ordered data mode. Opts: (null)
[    1.020519] VFS: Mounted root (ext4 filesystem) readonly on device 179:2.
[    1.027707] devtmpfs: mounted
[    1.027808] mmc1: new high speed SDIO card at address 0001
[    1.028528] Freeing unused kernel memory: 476K (807eb000 - 80862000)
[    1.127956] usb 1-1: new high-speed USB device number 2 using dwc_otg
[    1.128113] Indeed it is in host mode hprt0 = 00001101
[    1.266145] random: systemd: uninitialized urandom read (16 bytes read, 34 bits of entropy available)
[    1.270070] systemd[1]: systemd 215 running in system mode. (+PAM +AUDIT +SELINUX +IMA +SYSVINIT +LIBCRYPTSETUP +GCRYPT +ACL +XZ -SECCOMP -APPARMOR)
[    1.270469] systemd[1]: Detected architecture 'arm'.
[    1.328225] usb 1-1: New USB device found, idVendor=0424, idProduct=9514
[    1.328249] usb 1-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.329032] hub 1-1:1.0: USB hub found
[    1.329129] hub 1-1:1.0: 5 ports detected
[    1.362933] NET: Registered protocol family 10
[    1.364474] systemd[1]: Inserted module 'ipv6'
[    1.368017] systemd[1]: Set hostname to <iot02kei>.
[    1.368177] random: systemd: uninitialized urandom read (16 bytes read, 48 bits of entropy available)
[    1.368241] systemd[1]: Initializing machine ID from random generator.
[    1.368456] systemd[1]: Installed transient /etc/machine-id file.
[    1.471223] random: systemd-sysv-ge: uninitialized urandom read (16 bytes read, 61 bits of entropy available)
[    1.578257] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.579561] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.580969] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.601826] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.602611] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.602770] random: systemd: uninitialized urandom read (16 bytes read, 71 bits of entropy available)
[    1.607974] usb 1-1.1: new high-speed USB device number 3 using dwc_otg
[    1.638120] random: systemd: uninitialized urandom read (16 bytes read, 72 bits of entropy available)
[    1.708304] usb 1-1.1: New USB device found, idVendor=0424, idProduct=ec00
[    1.708326] usb 1-1.1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.711258] smsc95xx v1.0.4
[    1.736288] systemd[1]: Cannot add dependency job for unit regenerate_ssh_host_keys.service, ignoring: Unit regenerate_ssh_host_keys.service failed to load: No such file or directory.
[    1.739893] systemd[1]: Starting Forward Password Requests to Wall Directory Watch.
[    1.740251] systemd[1]: Started Forward Password Requests to Wall Directory Watch.
[    1.740333] systemd[1]: Starting Remote File Systems (Pre).
[    1.740483] systemd[1]: Reached target Remote File Systems (Pre).
[    1.740578] systemd[1]: Starting Encrypted Volumes.
[    1.740648] systemd[1]: Reached target Encrypted Volumes.
[    1.740797] systemd[1]: Starting Arbitrary Executable File Formats File System Automount Point.
[    1.741254] systemd[1]: Set up automount Arbitrary Executable File Formats File System Automount Point.
[    1.741349] systemd[1]: Starting Swap.
[    1.741417] systemd[1]: Reached target Swap.
[    1.741492] systemd[1]: Expecting device dev-disk-by\x2dpartuuid-45561e69\x2d01.device...
[    1.741563] systemd[1]: Starting Root Slice.
[    1.741708] systemd[1]: Created slice Root Slice.
[    1.741779] systemd[1]: Starting User and Session Slice.
[    1.742005] systemd[1]: Created slice User and Session Slice.
[    1.742076] systemd[1]: Starting Delayed Shutdown Socket.
[    1.742245] systemd[1]: Listening on Delayed Shutdown Socket.
[    1.742317] systemd[1]: Starting /dev/initctl Compatibility Named Pipe.
[    1.742499] systemd[1]: Listening on /dev/initctl Compatibility Named Pipe.
[    1.742569] systemd[1]: Starting Journal Socket (/dev/log).
[    1.742747] systemd[1]: Listening on Journal Socket (/dev/log).
[    1.742841] systemd[1]: Starting udev Control Socket.
[    1.742993] systemd[1]: Listening on udev Control Socket.
[    1.743079] systemd[1]: Starting udev Kernel Socket.
[    1.743207] systemd[1]: Listening on udev Kernel Socket.
[    1.743303] systemd[1]: Starting Journal Socket.
[    1.743507] systemd[1]: Listening on Journal Socket.
[    1.743646] systemd[1]: Starting System Slice.
[    1.743857] systemd[1]: Created slice System Slice.
[    1.743973] systemd[1]: Starting File System Check on Root Device...
[    1.771396] smsc95xx 1-1.1:1.0 eth0: register 'smsc95xx' at usb-3f980000.usb-1.1, smsc95xx USB 2.0 Ethernet, b8:27:eb:8a:ce:24
[    1.788749] systemd[1]: Starting system-systemd\x2dfsck.slice.
[    1.789188] systemd[1]: Created slice system-systemd\x2dfsck.slice.
[    1.789309] systemd[1]: Starting system-autologin.slice.
[    1.789612] systemd[1]: Created slice system-autologin.slice.
[    1.789812] systemd[1]: Starting Increase datagram queue length...
[    1.792559] systemd[1]: Starting Restore / save the current clock...
[    1.800645] systemd[1]: Starting Create list of required static device nodes for the current kernel...
[    1.831927] systemd[1]: Starting Load Kernel Modules...
[    1.835580] systemd[1]: Mounting Debug File System...
[    1.838436] systemd[1]: Mounted Huge Pages File System.
[    1.839208] systemd[1]: Mounting POSIX Message Queue File System...
[    1.842446] systemd[1]: Starting udev Coldplug all Devices...
[    1.848048] usb 1-1.2: new high-speed USB device number 4 using dwc_otg
[    1.911550] systemd[1]: Started Set Up Additional Binary Formats.
[    1.911682] systemd[1]: Starting Slices.
[    1.911773] systemd[1]: Reached target Slices.
[    1.916019] systemd[1]: Started Create list of required static device nodes for the current kernel.
[    1.929965] fuse init (API version 7.23)
[    1.934282] systemd[1]: Started Increase datagram queue length.
[    1.935182] systemd[1]: Mounted Debug File System.
[    1.935822] systemd[1]: Mounted POSIX Message Queue File System.
[    1.950704] usb 1-1.2: New USB device found, idVendor=05e3, idProduct=0610
[    1.950727] usb 1-1.2: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    1.950740] usb 1-1.2: Product: USB2.1 Hub
[    1.950752] usb 1-1.2: Manufacturer: GenesysLogic
[    1.951780] hub 1-1.2:1.0: USB hub found
[    1.952083] hub 1-1.2:1.0: 4 ports detected
[    1.965447] i2c /dev entries driver
[    1.974977] systemd[1]: Started Restore / save the current clock.
[    1.976205] systemd[1]: Started Load Kernel Modules.
[    1.981078] systemd[1]: Time has been changed
[    1.999436] systemd[1]: Started udev Coldplug all Devices.
[    2.047990] usb 1-1.3: new full-speed USB device number 5 using dwc_otg
[    2.081472] systemd[1]: Started File System Check on Root Device.
[    2.096858] systemd[1]: Mounting FUSE Control File System...
[    2.128394] systemd[1]: Starting Apply Kernel Variables...
[    2.131336] systemd[1]: Mounting Configuration File System...
[    2.134310] systemd[1]: Starting Syslog Socket.
[    2.134623] systemd[1]: Listening on Syslog Socket.
[    2.134955] systemd[1]: Starting Journal Service...
[    2.138527] systemd[1]: Started Journal Service.
[    2.163533] usb 1-1.3: New USB device found, idVendor=2341, idProduct=0043
[    2.163557] usb 1-1.3: New USB device strings: Mfr=1, Product=2, SerialNumber=220
[    2.163572] usb 1-1.3: Manufacturer: Arduino (www.arduino.cc)
[    2.163584] usb 1-1.3: SerialNumber: 5573532353535190C090
[    2.248058] usb 1-1.2.1: new low-speed USB device number 6 using dwc_otg
[    2.335537] systemd-udevd[142]: starting version 215
[    2.378923] usb 1-1.2.1: New USB device found, idVendor=1c4f, idProduct=0032
[    2.378948] usb 1-1.2.1: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    2.378961] usb 1-1.2.1: Product: Usb Mouse
[    2.378975] usb 1-1.2.1: Manufacturer: SIGMACHIP
[    2.388450] input: SIGMACHIP Usb Mouse as /devices/platform/soc/3f980000.usb/usb1/1-1/1-1.2/1-1.2.1/1-1.2.1:1.0/0003:1C4F:0032.0001/input/input0
[    2.388949] hid-generic 0003:1C4F:0032.0001: input,hidraw0: USB HID v1.10 Mouse [SIGMACHIP Usb Mouse] on usb-3f980000.usb-1.2.1/input0
[    2.488002] usb 1-1.2.2: new low-speed USB device number 7 using dwc_otg
[    2.618597] usb 1-1.2.2: New USB device found, idVendor=046d, idProduct=c31c
[    2.618622] usb 1-1.2.2: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    2.618637] usb 1-1.2.2: Product: USB Keyboard
[    2.618650] usb 1-1.2.2: Manufacturer: Logitech
[    2.632976] input: Logitech USB Keyboard as /devices/platform/soc/3f980000.usb/usb1/1-1/1-1.2/1-1.2.2/1-1.2.2:1.0/0003:046D:C31C.0002/input/input1
[    2.679776] Driver for 1-wire Dallas network protocol.
[    2.689208] hid-generic 0003:046D:C31C.0002: input,hidraw1: USB HID v1.10 Keyboard [Logitech USB Keyboard] on usb-3f980000.usb-1.2.2/input0
[    2.695241] w1-gpio onewire@0: gpio pin 4, external pullup pin -1, parasitic power 0
[    2.695280] w1_add_master_device: set_pullup requires write_byte or touch_bit, disabling
[    2.702521] input: Logitech USB Keyboard as /devices/platform/soc/3f980000.usb/usb1/1-1/1-1.2/1-1.2.2/1-1.2.2:1.1/0003:046D:C31C.0003/input/input2
[    2.758324] hid-generic 0003:046D:C31C.0003: input,hidraw2: USB HID v1.10 Device [Logitech USB Keyboard] on usb-3f980000.usb-1.2.2/input1
[    2.862894] gpiomem-bcm2835 3f200000.gpiomem: Initialised: Registers at 0x3f200000
[    2.868073] bcm2835-wdt 3f100000.watchdog: Broadcom BCM2835 watchdog timer
[    2.987530] EXT4-fs (mmcblk0p2): re-mounted. Opts: (null)
[    3.013275] cdc_acm 1-1.3:1.0: ttyACM0: USB ACM device
[    3.017679] usbcore: registered new interface driver cdc_acm
[    3.017710] cdc_acm: USB Abstract Control Model driver for USB modems and ISDN adapters
[    3.089280] usbcore: registered new interface driver brcmfmac
[    3.243885] brcmfmac: brcmf_c_preinit_dcmds: Firmware version = wl0: May 27 2016 00:13:38 version 7.45.41.26 (r640327) FWID 01-df77e4a7
[    3.267358] brcmfmac: brcmf_cfg80211_reg_notifier: not a ISO3166 code
[    3.380908] brcmfmac: brcmf_cfg80211_reg_notifier: not a ISO3166 code
[    3.380939] cfg80211: World regulatory domain updated:
[    3.380948] cfg80211:  DFS Master region: unset
[    3.380957] cfg80211:   (start_freq - end_freq @ bandwidth), (max_antenna_gain, max_eirp), (dfs_cac_time)
[    3.380974] cfg80211:   (2402000 KHz - 2472000 KHz @ 40000 KHz), (N/A, 2000 mBm), (N/A)
[    3.380990] cfg80211:   (2457000 KHz - 2482000 KHz @ 20000 KHz, 92000 KHz AUTO), (N/A, 2000 mBm), (N/A)
[    3.381003] cfg80211:   (2474000 KHz - 2494000 KHz @ 20000 KHz), (N/A, 2000 mBm), (N/A)
[    3.381016] cfg80211:   (5170000 KHz - 5250000 KHz @ 80000 KHz, 160000 KHz AUTO), (N/A, 2000 mBm), (N/A)
[    3.381031] cfg80211:   (5250000 KHz - 5330000 KHz @ 80000 KHz, 160000 KHz AUTO), (N/A, 2000 mBm), (0 s)
[    3.381044] cfg80211:   (5490000 KHz - 5730000 KHz @ 160000 KHz), (N/A, 2000 mBm), (0 s)
[    3.381056] cfg80211:   (5735000 KHz - 5835000 KHz @ 80000 KHz), (N/A, 2000 mBm), (N/A)
[    3.381069] cfg80211:   (57240000 KHz - 63720000 KHz @ 2160000 KHz), (N/A, 0 mBm), (N/A)
[    3.732902] systemd-journald[136]: Received request to flush runtime journal from PID 1
[    3.778011] random: nonblocking pool is initialized
[    3.818561] ip_tables: (C) 2000-2006 Netfilter Core Team
[    4.702759] w1_master_driver w1_bus_master1: w1_search: max_slave_count 64 reached, will continue next search.
[    5.159231] smsc95xx 1-1.1:1.0 eth0: hardware isn't capable of remote wakeup
[    5.159422] IPv6: ADDRCONF(NETDEV_UP): eth0: link is not ready
[    6.721976] IPv6: ADDRCONF(NETDEV_CHANGE): eth0: link becomes ready
[    6.722481] smsc95xx 1-1.1:1.0 eth0: link up, 100Mbps, full-duplex, lpa 0xC5E1
[    8.308837] uart-pl011 3f201000.uart: no DMA platform data
[    8.410054] Adding 102396k swap on /var/swap.  Priority:-1 extents:8 across:192508k SSFS
[    8.748799] cfg80211: Regulatory domain changed to country: GB
[    8.748823] cfg80211:  DFS Master region: ETSI
[    8.748832] cfg80211:   (start_freq - end_freq @ bandwidth), (max_antenna_gain, max_eirp), (dfs_cac_time)
[    8.748848] cfg80211:   (2402000 KHz - 2482000 KHz @ 40000 KHz), (N/A, 2000 mBm), (N/A)
[    8.748863] cfg80211:   (5170000 KHz - 5250000 KHz @ 80000 KHz, 160000 KHz AUTO), (N/A, 2000 mBm), (N/A)
[    8.748878] cfg80211:   (5250000 KHz - 5330000 KHz @ 80000 KHz, 160000 KHz AUTO), (N/A, 2000 mBm), (0 s)
[    8.748891] cfg80211:   (5490000 KHz - 5710000 KHz @ 160000 KHz), (N/A, 2700 mBm), (0 s)
[    8.748903] cfg80211:   (57000000 KHz - 66000000 KHz @ 2160000 KHz), (N/A, 4000 mBm), (N/A)
[   12.787574] Bluetooth: Core ver 2.21
[   12.787648] NET: Registered protocol family 31
[   12.787655] Bluetooth: HCI device and connection manager initialized
[   12.787670] Bluetooth: HCI socket layer initialized
[   12.787680] Bluetooth: L2CAP socket layer initialized
[   12.787702] Bluetooth: SCO socket layer initialized
[   12.795350] Bluetooth: HCI UART driver ver 2.3
[   12.795363] Bluetooth: HCI UART protocol H4 registered
[   12.795368] Bluetooth: HCI UART protocol Three-wire (H5) registered
[   12.795466] Bluetooth: HCI UART protocol BCM registered
[   12.992955] Bluetooth: BNEP (Ethernet Emulation) ver 1.3
[   12.992977] Bluetooth: BNEP filters: protocol multicast
[   12.993002] Bluetooth: BNEP socket layer initialized
[   52.155171] w1_master_driver w1_bus_master1: Family 0 for 00.800000000000.8c is not registered.
......
~~~
$ date
~~~
Thu  7 Jun 18:45:48 KST 2018
~~~
