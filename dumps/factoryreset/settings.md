# uname -a

```
Linux localhost 4.14.190-perf #1 SMP PREEMPT Mon Nov 4 18:37:23 PST 2024 aarch64
```

# df -h

```
Filesystem            Size Used Avail Use% Mounted on
tmpfs                 1.7G 1.6M  1.7G   1% /dev
tmpfs                 1.7G    0  1.7G   0% /mnt
/dev/block/dm-8       2.1G 2.1G     0 100% /
/dev/block/dm-9       484M 482M     0 100% /system_ext
/dev/block/dm-10      718M 716M     0 100% /vendor
/dev/block/dm-11       68M  68M     0 100% /product
tmpfs                 1.7G 8.0K  1.7G   1% /apex
/dev/block/mmcblk0p28 140M 107M   33M  77% /vendor/firmware_mnt
/dev/block/dm-12       14G 752M   14G   6% /data
/dev/fuse              14G 752M   14G   6% /storage/emulated
```

# mount

```
tmpfs on /dev type tmpfs (rw,seclabel,nosuid,relatime,mode=755)
devpts on /dev/pts type devpts (rw,seclabel,relatime,mode=600,ptmxmode=000)
proc on /proc type proc (rw,relatime,gid=3009,hidepid=2)
sysfs on /sys type sysfs (rw,seclabel,relatime)
selinuxfs on /sys/fs/selinux type selinuxfs (rw,relatime)
tmpfs on /mnt type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755,gid=1000)
/dev/block/mmcblk0p45 on /metadata type ext4 (rw,seclabel,nosuid,nodev,noatime,discard,data=ordered)
/dev/block/dm-8 on / type ext4 (ro,seclabel,nodev,relatime,discard)
/dev/block/dm-9 on /system_ext type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-10 on /vendor type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-11 on /product type ext4 (ro,seclabel,relatime,discard)
tmpfs on /apex type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755)
tmpfs on /linkerconfig type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755)
tmpfs on /mnt/installer type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755,gid=1000)
tmpfs on /mnt/androidwritable type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755,gid=1000)
/dev/block/dm-8 on /apex/com.android.adbd type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.appsearch type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.art type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.cellbroadcast type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.conscrypt type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.extservices type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.i18n type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.ipsec type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.media type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.media.swcodec type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.mediaprovider type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.neuralnetworks type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.os.statsd type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.permission type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.resolv type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.runtime type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.scheduling type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.sdkext type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.tethering type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.tzdata type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.vndk.v32 type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-8 on /apex/com.android.wifi type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-9 on /apex/com.android.vndk.v30 type ext4 (ro,seclabel,relatime,discard)
/dev/block/dm-9 on /apex/com.android.vndk.v31 type ext4 (ro,seclabel,relatime,discard)
none on /dev/blkio type cgroup (rw,nosuid,nodev,noexec,relatime,blkio)
none on /sys/fs/cgroup type cgroup2 (rw,nosuid,nodev,noexec,relatime)
none on /dev/cpuctl type cgroup (rw,nosuid,nodev,noexec,relatime,cpu)
none on /dev/cpuset type cgroup (rw,nosuid,nodev,noexec,relatime,cpuset,noprefix,release_agent=/sbin/cpuset_release_agent)
none on /dev/memcg type cgroup (rw,nosuid,nodev,noexec,relatime,memory)
none on /dev/stune type cgroup (rw,nosuid,nodev,noexec,relatime,schedtune)
tmpfs on /linkerconfig type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755)
tracefs on /sys/kernel/tracing type tracefs (rw,seclabel,relatime,gid=3012)
none on /config type configfs (rw,nosuid,nodev,noexec,relatime)
binder on /dev/binderfs type binder (rw,relatime,max=1048576,stats=global)
none on /sys/fs/fuse/connections type fusectl (rw,relatime)
bpf on /sys/fs/bpf type bpf (rw,nosuid,nodev,noexec,relatime)
/dev/block/mmcblk0p28 on /vendor/firmware_mnt type vfat (ro,context=u:object_r:firmware_file:s0,relatime,uid=1000,gid=1000,fmask=0337,dmask=0227,codepage=437,iocharset=iso8859-1,shortname=lower,errors=remount-ro)
/dev/block/mmcblk0p30 on /vendor/dsp type ext4 (ro,seclabel,nosuid,nodev,relatime,data=ordered)
/dev/block/mmcblk0p44 on /mnt/vendor/persist type ext4 (rw,seclabel,nosuid,nodev,noatime,data=ordered)
/dev/block/mmcblk0p35 on /vendor/bt_firmware type vfat (ro,context=u:object_r:bt_firmware_file:s0,relatime,uid=1002,gid=3002,fmask=0337,dmask=0227,codepage=437,iocharset=iso8859-1,shortname=lower,errors=remount-ro)
tmpfs on /storage type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=755,gid=1000)
/dev/block/dm-12 on /data type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
/dev/block/dm-12 on /data/user/0 type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
tmpfs on /data_mirror type tmpfs (rw,seclabel,nosuid,nodev,noexec,relatime,mode=700,gid=1000)
/dev/block/dm-12 on /data_mirror/data_ce/null type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
/dev/block/dm-12 on /data_mirror/data_ce/null/0 type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
/dev/block/dm-12 on /data_mirror/data_de/null type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
/dev/block/dm-12 on /data_mirror/cur_profiles type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
/dev/block/dm-12 on /data_mirror/ref_profiles type f2fs (rw,lazytime,seclabel,nosuid,nodev,noatime,background_gc=on,discard,no_heap,user_xattr,inline_xattr,acl,inline_data,inline_dentry,flush_merge,extent_cache,mode=adaptive,active_logs=6,reserve_root=7237,resuid=0,resgid=1065,inlinecrypt,alloc_mode=reuse,fsync_mode=strict)
adb on /dev/usb-ffs/adb type functionfs (rw,relatime)
diag on /dev/ffs-diag type functionfs (rw,relatime)
diag_mdm on /dev/ffs-diag-1 type functionfs (rw,relatime)
diag_mdm2 on /dev/ffs-diag-2 type functionfs (rw,relatime)
/data/media on /mnt/runtime/default/emulated type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/runtime/read/emulated type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=9997,multiuser,mask=23,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/runtime/write/emulated type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=9997,multiuser,mask=7,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/runtime/full/emulated type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=9997,multiuser,mask=7,derive_gid,default_normal,unshared_obb)
/dev/fuse on /mnt/user/0/emulated type fuse (rw,lazytime,nosuid,nodev,noexec,noatime,user_id=0,group_id=0,allow_other)
/dev/fuse on /mnt/installer/0/emulated type fuse (rw,lazytime,nosuid,nodev,noexec,noatime,user_id=0,group_id=0,allow_other)
/dev/fuse on /mnt/androidwritable/0/emulated type fuse (rw,lazytime,nosuid,nodev,noexec,noatime,user_id=0,group_id=0,allow_other)
/dev/fuse on /storage/emulated type fuse (rw,lazytime,nosuid,nodev,noexec,noatime,user_id=0,group_id=0,allow_other)
/data/media on /mnt/pass_through/0/emulated type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=9997,multiuser,mask=7,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/user/0/emulated/0/Android/data type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /storage/emulated/0/Android/data type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/androidwritable/0/emulated/0/Android/data type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/installer/0/emulated/0/Android/data type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/user/0/emulated/0/Android/obb type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /storage/emulated/0/Android/obb type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/androidwritable/0/emulated/0/Android/obb type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=1015,multiuser,mask=6,derive_gid,default_normal,unshared_obb)
/data/media on /mnt/installer/0/emulated/0/Android/obb type sdcardfs (rw,nosuid,nodev,noexec,noatime,fsuid=1023,fsgid=1023,gid=9997,multiuser,mask=7,derive_gid,default_normal,unshared_obb)
```

# ps -A

```
USER           PID  PPID     VSZ    RSS WCHAN            ADDR S NAME
root             1     0 13053744 13892 0                   0 S init
root             2     0       0      0 0                   0 S [kthreadd]
root             3     2       0      0 0                   0 I [rcu_gp]
root             5     2       0      0 0                   0 I [kworker/0:0H]
root             6     2       0      0 0                   0 S [kworker/u16:0]
root             7     2       0      0 0                   0 I [mm_percpu_wq]
root             8     2       0      0 0                   0 S [ksoftirqd/0]
root             9     2       0      0 0                   0 I [rcu_preempt]
root            10     2       0      0 0                   0 I [rcu_sched]
root            11     2       0      0 0                   0 I [rcu_bh]
root            12     2       0      0 0                   0 S [rcuop/0]
root            13     2       0      0 0                   0 S [rcuos/0]
root            14     2       0      0 0                   0 S [rcuob/0]
root            15     2       0      0 0                   0 S [migration/0]
root            16     2       0      0 0                   0 S [cpuhp/0]
root            17     2       0      0 0                   0 S [cpuhp/1]
root            18     2       0      0 0                   0 S [migration/1]
root            19     2       0      0 0                   0 S [ksoftirqd/1]
root            21     2       0      0 0                   0 I [kworker/1:0H]
root            22     2       0      0 0                   0 S [rcuop/1]
root            23     2       0      0 0                   0 S [rcuos/1]
root            24     2       0      0 0                   0 S [rcuob/1]
root            25     2       0      0 0                   0 S [cpuhp/2]
root            26     2       0      0 0                   0 S [migration/2]
root            27     2       0      0 0                   0 S [ksoftirqd/2]
root            30     2       0      0 0                   0 S [rcuop/2]
root            31     2       0      0 0                   0 S [rcuos/2]
root            32     2       0      0 0                   0 S [rcuob/2]
root            33     2       0      0 0                   0 S [cpuhp/3]
root            34     2       0      0 0                   0 S [migration/3]
root            35     2       0      0 0                   0 S [ksoftirqd/3]
root            38     2       0      0 0                   0 S [rcuop/3]
root            39     2       0      0 0                   0 S [rcuos/3]
root            40     2       0      0 0                   0 S [rcuob/3]
root            41     2       0      0 0                   0 S [cpuhp/4]
root            42     2       0      0 0                   0 S [migration/4]
root            43     2       0      0 0                   0 S [ksoftirqd/4]
root            45     2       0      0 0                   0 I [kworker/4:0H]
root            46     2       0      0 0                   0 S [rcuop/4]
root            47     2       0      0 0                   0 S [rcuos/4]
root            48     2       0      0 0                   0 S [rcuob/4]
root            49     2       0      0 0                   0 S [cpuhp/5]
root            50     2       0      0 0                   0 S [migration/5]
root            51     2       0      0 0                   0 S [ksoftirqd/5]
root            53     2       0      0 0                   0 I [kworker/5:0H]
root            54     2       0      0 0                   0 S [rcuop/5]
root            55     2       0      0 0                   0 S [rcuos/5]
root            56     2       0      0 0                   0 S [rcuob/5]
root            57     2       0      0 0                   0 S [cpuhp/6]
root            58     2       0      0 0                   0 S [migration/6]
root            59     2       0      0 0                   0 S [ksoftirqd/6]
root            62     2       0      0 0                   0 S [rcuop/6]
root            63     2       0      0 0                   0 S [rcuos/6]
root            64     2       0      0 0                   0 S [rcuob/6]
root            65     2       0      0 0                   0 S [cpuhp/7]
root            66     2       0      0 0                   0 S [migration/7]
root            67     2       0      0 0                   0 S [ksoftirqd/7]
root            70     2       0      0 0                   0 S [rcuop/7]
root            71     2       0      0 0                   0 S [rcuos/7]
root            72     2       0      0 0                   0 S [rcuob/7]
root            73     2       0      0 0                   0 I [netns]
root            75     2       0      0 0                   0 S [kworker/u16:1]
root            77     2       0      0 0                   0 I [ipa_usb_wq]
root            78     2       0      0 0                   0 S [msm_watchdog]
root            79     2       0      0 0                   0 S [spi_wdsp]
root            80     2       0      0 0                   0 S [qmp_aop]
root            81     2       0      0 0                   0 S [oom_reaper]
root            82     2       0      0 0                   0 I [writeback]
root            83     2       0      0 0                   0 S [kcompactd0]
root            84     2       0      0 0                   0 I [crypto]
root            85     2       0      0 0                   0 I [kblockd]
root            86     2       0      0 0                   0 I [blk_crypto_wq]
root            88     2       0      0 0                   0 S [irq/93-arm-smmu]
root            89     2       0      0 0                   0 S [irq/94-arm-smmu]
root            90     2       0      0 0                   0 S [irq/103-arm-smm]
root            91     2       0      0 0                   0 S [irq/32-tsens-up]
root            92     2       0      0 0                   0 S [irq/33-tsens-cr]
root            93     2       0      0 0                   0 S [irq/38-tsens-up]
root            94     2       0      0 0                   0 S [irq/42-tsens-cr]
root            95     2       0      0 0                   0 I [edac-poller]
root            96     2       0      0 0                   0 S [system]
root            97     2       0      0 0                   0 I [ipa_power_mgmt]
root            98     2       0      0 0                   0 I [transport_power]
root            99     2       0      0 0                   0 I [ipa_pm_activate]
root           100     2       0      0 0                   0 I [devfreq_wq]
root           101     2       0      0 0                   0 I [cfg80211]
root           142     2       0      0 0                   0 S [kauditd]
root           143     2       0      0 0                   0 S [kswapd0]
root           144     2       0      0 0                   0 S [ecryptfs-kthrea]
root           181     2       0      0 0                   0 S [irq/106-arm-smm]
root           182     2       0      0 0                   0 S [irq/107-arm-smm]
root           183     2       0      0 0                   0 S [irq/18-smp2p]
root           184     2       0      0 0                   0 S [irq/19-smp2p]
root           185     2       0      0 0                   0 S [irq/20-smp2p]
root           186     2       0      0 0                   0 S [irq/108-arm-smm]
root           188     2       0      0 0                   0 I [mem_share_svc]
root           189     2       0      0 0                   0 S [cdsprm-wq]
root           190     2       0      0 0                   0 I [cdsprm-wq-delay]
root           191     2       0      0 0                   0 S [irq/109-arm-smm]
root           192     2       0      0 0                   0 S [irq/110-arm-smm]
root           193     2       0      0 0                   0 S [hwrng]
root           195     2       0      0 0                   0 I [diag_real_time_]
root           196     2       0      0 0                   0 I [diag_wq]
root           198     2       0      0 0                   0 I [DIAG_USB_diag]
root           199     2       0      0 0                   0 I [diag_cntl_wq]
root           200     2       0      0 0                   0 I [diag_dci_wq]
root           201     2       0      0 0                   0 I [MODEM_CNTL]
root           202     2       0      0 0                   0 I [MODEM_DATA]
root           203     2       0      0 0                   0 I [MODEM_CMD]
root           204     2       0      0 0                   0 I [MODEM_DCI]
root           205     2       0      0 0                   0 I [MODEM_DCI_CMD]
root           206     2       0      0 0                   0 I [LPASS_CNTL]
root           207     2       0      0 0                   0 I [LPASS_DATA]
root           208     2       0      0 0                   0 I [LPASS_CMD]
root           209     2       0      0 0                   0 I [LPASS_DCI]
root           210     2       0      0 0                   0 I [LPASS_DCI_CMD]
root           211     2       0      0 0                   0 I [WCNSS_CNTL]
root           212     2       0      0 0                   0 I [WCNSS_DATA]
root           213     2       0      0 0                   0 I [WCNSS_CMD]
root           214     2       0      0 0                   0 I [WCNSS_DCI]
root           215     2       0      0 0                   0 I [WCNSS_DCI_CMD]
root           216     2       0      0 0                   0 I [SENSORS_CNTL]
root           217     2       0      0 0                   0 I [SENSORS_DATA]
root           218     2       0      0 0                   0 I [SENSORS_CMD]
root           219     2       0      0 0                   0 I [SENSORS_DCI]
root           220     2       0      0 0                   0 I [SENSORS_DCI_CMD]
root           221     2       0      0 0                   0 I [DIAG_CTRL]
root           222     2       0      0 0                   0 I [DIAG_DATA]
root           223     2       0      0 0                   0 I [DIAG_CMD]
root           224     2       0      0 0                   0 I [DIAG_DCI_DATA]
root           225     2       0      0 0                   0 I [DIAG_DCI_CMD]
root           226     2       0      0 0                   0 I [CDSP_CNTL]
root           227     2       0      0 0                   0 I [CDSP_DATA]
root           228     2       0      0 0                   0 I [CDSP_CMD]
root           229     2       0      0 0                   0 I [CDSP_DCI]
root           230     2       0      0 0                   0 I [CDSP_DCI_CMD]
root           231     2       0      0 0                   0 I [NPU_CNTL]
root           232     2       0      0 0                   0 I [NPU_DATA]
root           233     2       0      0 0                   0 I [NPU_CMD]
root           234     2       0      0 0                   0 I [NPU_DCI]
root           235     2       0      0 0                   0 I [NPU_DCI_CMD]
root           236     2       0      0 0                   0 I [DIAG_RPMSG_APPS]
root           237     2       0      0 0                   0 I [DIAG_RPMSG_APPS]
root           238     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           239     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           240     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           241     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           242     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           243     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           244     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           245     2       0      0 0                   0 I [DIAG_RPMSG_DIAG]
root           246     2       0      0 0                   0 S [kworker/u16:2]
root           247     2       0      0 0                   0 S [kworker/u16:3]
root           248     2       0      0 0                   0 S [kworker/u16:4]
root           249     2       0      0 0                   0 S [kworker/u16:5]
root           250     2       0      0 0                   0 S [kworker/u16:6]
root           252     2       0      0 0                   0 I [kgsl-workqueue]
root           253     2       0      0 0                   0 I [kgsl-mementry]
root           254     2       0      0 0                   0 S [kgsl_worker_thr]
root           255     2       0      0 0                   0 S [irq/95-arm-smmu]
root           256     2       0      0 0                   0 S [irq/96-arm-smmu]
root           257     2       0      0 0                   0 S [irq/97-arm-smmu]
root           258     2       0      0 0                   0 S [irq/98-arm-smmu]
root           259     2       0      0 0                   0 I [kgsl-events]
root           260     2       0      0 0                   0 I [kgsl_devfreq_wq]
root           261     2       0      0 0                   0 S [qseecom-unreg-l]
root           262     2       0      0 0                   0 S [qseecom-unload-]
root           263     2       0      0 0                   0 I [memory_wq]
root           264     2       0      0 0                   0 S [irq/111-arm-smm]
root           265     2       0      0 0                   0 S [irq/112-arm-smm]
root           266     2       0      0 0                   0 S [irq/113-arm-smm]
root           267     2       0      0 0                   0 I [qcrypto_seq_res]
root           268     2       0      0 0                   0 S [irq/114-arm-smm]
root           291     2       0      0 0                   0 I [bond0]
root           297     2       0      0 0                   0 I [uether]
root           298     2       0      0 0                   0 I [k_ipa_usb]
root           301     2       0      0 0                   0 S [irq/105-arm-smm]
root           302     2       0      0 0                   0 I [npu_general_wq]
root           303     2       0      0 0                   0 I [msm_vidc_worker]
root           304     2       0      0 0                   0 I [pm_workerq_venu]
root           305     2       0      0 0                   0 S [irq/115-arm-smm]
root           306     2       0      0 0                   0 S [irq/116-arm-smm]
root           307     2       0      0 0                   0 S [irq/117-arm-smm]
root           308     2       0      0 0                   0 S [irq/118-arm-smm]
root           309     2       0      0 0                   0 I [cam-cpas]
root           310     2       0      0 0                   0 I [qcom,cam_virtua]
root           311     2       0      0 0                   0 S [irq/119-arm-smm]
root           312     2       0      0 0                   0 I [qcom,cam170-cpa]
root           313     2       0      0 0                   0 S [irq/120-arm-smm]
root           314     2       0      0 0                   0 I [cam_cci_wq]
root           315     2       0      0 0                   0 I [cam_cci_wq]
root           316     2       0      0 0                   0 S [irq/121-arm-smm]
root           317     2       0      0 0                   0 S [irq/122-arm-smm]
root           318     2       0      0 0                   0 S [irq/123-arm-smm]
root           319     2       0      0 0                   0 S [irq/242-stwlc86]
root           320     2       0      0 0                   0 S [irq/61-qcom,tem]
root           322     2       0      0 0                   0 S [irq/73-qcom,tem]
root           323     2       0      0 0                   0 I [kworker/7:3]
root           325     2       0      0 0                   0 S [irq/403-limits_]
root           326     2       0      0 0                   0 I [kworker/0:1H]
root           327     2       0      0 0                   0 S [irq/404-limits_]
root           330     2       0      0 0                   0 S [irq/53-bcl-lvl0]
root           331     2       0      0 0                   0 S [irq/55-bcl-lvl1]
root           332     2       0      0 0                   0 S [irq/57-bcl-lvl2]
root           333     2       0      0 0                   0 S [irq/74-bcl-lvl0]
root           334     2       0      0 0                   0 S [irq/75-bcl-lvl1]
root           335     2       0      0 0                   0 S [irq/76-bcl-lvl2]
root           336     2       0      0 0                   0 I [dm_bufio_cache]
root           337     2       0      0 0                   0 S [irq/14-KRYO L3-]
root           338     2       0      0 0                   0 I [mmc_clk_gate/mm]
root           340     2       0      0 0                   0 S [irq/28-7c4000.s]
root           341     2       0      0 0                   0 S [irq/27-mmc0]
root           342     2       0      0 0                   0 I [sdhci_msm_pm_qo]
root           343     2       0      0 0                   0 D [mmc-cmdqd/0]
root           344     2       0      0 0                   0 S [mmcqd/0rpmb]
root           345     2       0      0 0                   0 S [irq/124-arm-smm]
root           346     2       0      0 0                   0 I [uaudio_svc]
root           347     2       0      0 0                   0 I [ipv6_addrconf]
root           348     2       0      0 0                   0 S [irq/21-smp2p]
root           350     2       0      0 0                   0 S [irq/125-arm-smm]
root           351     2       0      0 0                   0 S [irq/126-arm-smm]
root           352     2       0      0 0                   0 S [crtc_commit:98]
root           353     2       0      0 0                   0 S [crtc_event:98]
root           354     2       0      0 0                   0 S [crtc_commit:135]
root           355     2       0      0 0                   0 S [crtc_event:135]
root           356     2       0      0 0                   0 S [pp_event]
root           365     2       0      0 0                   0 S [irq/310-touchpa]
root           366     2       0      0 0                   0 S [rot_commitq_0_0]
root           367     2       0      0 0                   0 S [rot_commitq_0_1]
root           368     2       0      0 0                   0 S [rot_doneq_0_0]
root           369     2       0      0 0                   0 S [rot_doneq_0_1]
root           370     2       0      0 0                   0 S [rot_fenceq_0_0]
root           371     2       0      0 0                   0 S [rot_fenceq_0_1]
root           372     2       0      0 0                   0 S [rot_fenceq_0_2]
root           373     2       0      0 0                   0 S [rot_fenceq_0_3]
root           374     2       0      0 0                   0 S [rot_fenceq_0_4]
root           375     2       0      0 0                   0 S [rot_fenceq_0_5]
root           376     2       0      0 0                   0 S [rot_fenceq_0_6]
root           377     2       0      0 0                   0 S [rot_fenceq_0_7]
root           378     2       0      0 0                   0 S [rot_fenceq_0_8]
root           379     2       0      0 0                   0 S [rot_fenceq_0_9]
root           380     2       0      0 0                   0 S [rot_fenceq_0_10]
root           381     2       0      0 0                   0 S [rot_fenceq_0_11]
root           382     2       0      0 0                   0 S [rot_fenceq_0_12]
root           383     2       0      0 0                   0 S [rot_fenceq_0_13]
root           384     2       0      0 0                   0 S [rot_fenceq_0_14]
root           385     2       0      0 0                   0 S [rot_fenceq_0_15]
root           386     2       0      0 0                   0 S [irq/424-qg-vbat]
root           387     2       0      0 0                   0 S [irq/425-qg-vbat]
root           388     2       0      0 0                   0 S [irq/426-qg-fifo]
root           389     2       0      0 0                   0 S [irq/427-qg-good]
root           390     2       0      0 0                   0 S [irq/428-chgr-er]
root           391     2       0      0 0                   0 S [irq/429-chg-sta]
root           393     2       0      0 0                   0 S [irq/436-otg-fai]
root           394     2       0      0 0                   0 S [irq/440-high-du]
root           395     2       0      0 0                   0 S [irq/441-input-c]
root           397     2       0      0 0                   0 S [irq/443-switche]
root           399     2       0      0 0                   0 S [irq/444-bat-tem]
root           400     2       0      0 0                   0 S [irq/445-bat-ov]
root           402     2       0      0 0                   0 S [irq/446-bat-low]
root           403     2       0      0 0                   0 S [irq/447-bat-the]
root           404     2       0      0 0                   0 S [irq/448-bat-ter]
root           405     2       0      0 0                   0 S [irq/451-usbin-c]
root           406     2       0      0 0                   0 S [irq/452-usbin-v]
root           407     2       0      0 0                   0 S [irq/453-usbin-u]
root           408     2       0      0 0                   0 S [irq/454-usbin-o]
root           409     2       0      0 0                   0 S [irq/455-usbin-p]
root           410     2       0      0 0                   0 S [irq/457-usbin-s]
root           411     2       0      0 0                   0 S [irq/458-usbin-i]
root           412     2       0      0 0                   0 S [irq/460-dcin-uv]
root           413     2       0      0 0                   0 S [irq/461-dcin-ov]
root           414     2       0      0 0                   0 S [irq/462-dcin-pl]
root           415     2       0      0 0                   0 S [irq/464-dcin-po]
root           416     2       0      0 0                   0 S [irq/465-dcin-en]
root           417     2       0      0 0                   0 S [irq/466-typec-o]
root           418     2       0      0 0                   0 S [irq/468-typec-c]
root           419     2       0      0 0                   0 S [irq/469-typec-v]
root           420     2       0      0 0                   0 S [irq/471-typec-a]
root           421     2       0      0 0                   0 S [irq/472-typec-l]
root           422     2       0      0 0                   0 S [irq/474-wdog-sn]
root           423     2       0      0 0                   0 S [irq/475-wdog-ba]
root           424     2       0      0 0                   0 S [irq/477-aicl-do]
root           425     2       0      0 0                   0 S [irq/478-smb-en]
root           426     2       0      0 0                   0 S [irq/480-temp-ch]
root           427     2       0      0 0                   0 S [irq/482-sdam-st]
root           433     2       0      0 0                   0 S [irq/40-thr-int-]
root           434     2       0      0 0                   0 S [irq/78-thr-int-]
root           441     2       0      0 0                   0 S [irq/34-sig-tx]
root           442     2       0      0 0                   0 S [irq/35-sig-rx]
root           444     2       0      0 0                   0 S [irq/373-pwr_eve]
root           445     2       0      0 0                   0 S [irq/372-dp_hs_p]
root           446     2       0      0 0                   0 S [irq/375-dm_hs_p]
root           447     2       0      0 0                   0 S [irq/374-ss_phy_]
root           448     2       0      0 0                   0 S [irq/127-arm-smm]
root           449     2       0      0 0                   0 I [usb_bam_wq]
root           450     2       0      0 0                   0 S [core_ctl/0]
root           451     2       0      0 0                   0 S [core_ctl/6]
root           454     2       0      0 0                   0 I [rq_stats]
root           455     2       0      0 0                   0 S [msm_perf:events]
root           456     2       0      0 0                   0 S [irq/128-arm-smm]
root           457     2       0      0 0                   0 S [irq/129-arm-smm]
root           458     2       0      0 0                   0 S [irq/130-arm-smm]
root           459     2       0      0 0                   0 S [irq/131-arm-smm]
root           460     2       0      0 0                   0 S [irq/132-arm-smm]
root           461     2       0      0 0                   0 S [irq/133-arm-smm]
root           462     2       0      0 0                   0 S [irq/134-arm-smm]
root           463     2       0      0 0                   0 S [irq/135-arm-smm]
root           464     2       0      0 0                   0 S [irq/136-arm-smm]
root           465     2       0      0 0                   0 S [irq/137-arm-smm]
root           466     2       0      0 0                   0 S [irq/138-arm-smm]
root           467     2       0      0 0                   0 S [irq/139-arm-smm]
root           468     2       0      0 0                   0 I [sb-1]
root           469     2       0      0 0                   0 S [ngd_rx_thread1]
root           470     2       0      0 0                   0 S [ngd_notify_sl1]
root           473     2       0      0 0                   0 S [jbd2/mmcblk0p45]
root           474     2       0      0 0                   0 I [ext4-rsv-conver]
root           475     2       0      0 0                   0 I [kdmflush]
root           476     2       0      0 0                   0 I [bioset]
root           477     2       0      0 0                   0 I [kdmflush]
root           478     2       0      0 0                   0 I [bioset]
root           479     2       0      0 0                   0 I [kdmflush]
root           480     2       0      0 0                   0 I [bioset]
root           481     2       0      0 0                   0 I [kdmflush]
root           482     2       0      0 0                   0 I [bioset]
root           483     2       0      0 0                   0 I [kdmflush]
root           484     2       0      0 0                   0 I [bioset]
root           485     2       0      0 0                   0 I [kdmflush]
root           486     2       0      0 0                   0 I [bioset]
root           487     2       0      0 0                   0 I [kdmflush]
root           488     2       0      0 0                   0 I [bioset]
root           489     2       0      0 0                   0 I [kdmflush]
root           490     2       0      0 0                   0 I [bioset]
root           491     2       0      0 0                   0 I [kdmflush]
root           492     2       0      0 0                   0 I [bioset]
root           493     2       0      0 0                   0 I [kverityd]
root           494     2       0      0 0                   0 I [bioset]
root           495     2       0      0 0                   0 I [bioset]
root           496     2       0      0 0                   0 I [bioset]
root           497     2       0      0 0                   0 I [ext4-rsv-conver]
root           503     2       0      0 0                   0 I [kworker/5:1H]
root           508     2       0      0 0                   0 I [kdmflush]
root           509     2       0      0 0                   0 I [bioset]
root           510     2       0      0 0                   0 I [kverityd]
root           511     2       0      0 0                   0 I [bioset]
root           512     2       0      0 0                   0 I [bioset]
root           513     2       0      0 0                   0 I [bioset]
root           514     2       0      0 0                   0 I [ext4-rsv-conver]
root           515     2       0      0 0                   0 I [kdmflush]
root           516     2       0      0 0                   0 I [bioset]
root           517     2       0      0 0                   0 I [kverityd]
root           518     2       0      0 0                   0 I [bioset]
root           519     2       0      0 0                   0 I [bioset]
root           520     2       0      0 0                   0 I [bioset]
root           521     2       0      0 0                   0 I [ext4-rsv-conver]
root           522     2       0      0 0                   0 I [kdmflush]
root           523     2       0      0 0                   0 I [bioset]
root           524     2       0      0 0                   0 I [kverityd]
root           525     2       0      0 0                   0 I [bioset]
root           526     2       0      0 0                   0 I [bioset]
root           527     2       0      0 0                   0 I [bioset]
root           528     2       0      0 0                   0 I [kworker/4:2]
root           529     2       0      0 0                   0 I [ext4-rsv-conver]
root           535     1 12944800  8740 0                   0 S init
root           537     1 12946956  9940 0                   0 S ueventd
root           552     2       0      0 0                   0 I [apr_driver]
root           553     2       0      0 0                   0 S [irq/260-humane_]
logd           560     1 13031040  5540 0                   0 S logd
lmkd           561     1 12985732  4968 0                   0 S lmkd
system         562     1 12974524  6020 0                   0 S servicemanager
system         563     1 13035280  6792 0                   0 S hwservicemanager
system         564     1 12947536  4556 0                   0 S vndservicemanager
system         565     1 12949376  5936 0                   0 S android.hardware.keymaster@4.1-service-qti
system         566     1 13155328  7276 0                   0 S qseecomd
system         567     1 12990996  5532 0                   0 S vendor.qti.hardware.qseecom@1.0-service
root           571     1 12964324  9564 0                   0 S vold
root           577     2       0      0 0                   0 S [jbd2/mmcblk0p30]
root           578     2       0      0 0                   0 I [ext4-rsv-conver]
root           580     2       0      0 0                   0 S [jbd2/mmcblk0p44]
root           581     2       0      0 0                   0 I [ext4-rsv-conver]
root           617     2       0      0 0                   0 I [kdmflush]
root           623     2       0      0 0                   0 S [irq/140-arm-smm]
root           626     2       0      0 0                   0 S [irq/141-arm-smm]
root           627     1 13822908  6240 0                   0 S thermal-engine
system         628     1 12992672  4496 0                   0 S android.system.suspend@1.0-service
root           629     2       0      0 0                   0 S [irq/142-arm-smm]
humane_dev_+   631     1 12978360  5220 0                   0 S humane_device_identity
keystore       632     1 13087372 14276 0                   0 S keystore2
system         633     1 12933048  4792 0                   0 S android.hardware.atrace@1.0-service
root           634     1 12954604  5368 0                   0 S android.hardware.boot@1.1-service
system         635     1 12927452  5780 0                   0 S android.hardware.gatekeeper@1.0-service-qti
system         636     1 12895512  6208 0                   0 S vendor.qti.esepowermanager@1.1-service
system         637     1 12926512  5004 0                   0 S vendor.qti.hardware.cryptfshw@1.0-service-qti
system         638     1 12983892  5364 0                   0 S vendor.qti.hardware.qteeconnector@1.0-service
system         639     1 12991312  5532 0                   0 S vendor.qti.secure_element@1.2-service
system         640     1 12995940  5184 0                   0 S sscrpcd
root           714     2       0      0 0                   0 I [ipa_interrupt_w]
root           715     2       0      0 0                   0 I [ipawq36]
root           716     2       0      0 0                   0 I [iparepwq36]
root           717     2       0      0 0                   0 I [ipawq33]
root           718     2       0      0 0                   0 I [iparepwq33]
root           719     2       0      0 0                   0 I [ipawq32]
root           720     2       0      0 0                   0 I [iparepwq32]
root           721     2       0      0 0                   0 I [clnt_req]
root           724     2       0      0 0                   0 I [bioset]
root           726     2       0      0 0                   0 S [f2fs_flush-253:]
root           727     2       0      0 0                   0 S [f2fs_discard-25]
root           728     2       0      0 0                   0 S [f2fs_gc-253:12]
tombstoned     737     1 12876476  2296 0                   0 S tombstoned
system         757     1 13087392  4288 0                   0 S time_daemon
radio          758     1 13008884  6788 0                   0 S ipacm
statsd         769     1 13001540  4752 0                   0 S statsd
root           770     1 13294248  8408 0                   0 S netd
root           772     1 17173052 194396 0                  0 S zygote64
root           773     1 1796092 172808 0                   0 S zygote
root           789     2       0      0 0                   0 I [kworker/u17:12]
root           821   770 12893112  3368 0                   0 S iptables-restore
root           823   770 12929976  3544 0                   0 S ip6tables-restore
root           869     2       0      0 0                   0 S [glink_cdsp]
root           870     2       0      0 0                   0 S [qrtr_rx]
root           882     2       0      0 0                   0 S [glink_npu]
root           884     2       0      0 0                   0 S [glink_adsp]
root           885     2       0      0 0                   0 S [qrtr_rx]
root           886     2       0      0 0                   0 S [qrtr_rx]
system         909     1 13947012  7368 0                   0 S ssgtzd
audioserver    910     1   67776  19904 0                   0 S android.hardware.audio.service
system         911     1 12909628  2952 0                   0 S android.hidl.allocator@1.0-service
system         912     1 12988248  6672 0                   0 S qccsyshal@1.2-service
bluetooth      913     1 12982224  7012 0                   0 S android.hardware.bluetooth@1.0-service-qti
cameraserver   914     1 13554372 78268 0                   0 S android.hardware.camera.provider@2.4-service_64
media          915     1   22272   4720 0                   0 S android.hardware.cas@1.2-service
media          916     1 13000048  7604 0                   0 S android.hardware.drm@1.3-service.clearkey
gps            917     1 13380984 18692 0                   0 S android.hardware.gnss@2.1-service-qti
system         918     1 13265396 20216 0                   0 S android.hardware.graphics.composer@2.4-service
system         919     1 12894804  5312 0                   0 S android.hardware.health@2.1-service
system         920     1 12930964  4428 0                   0 S android.hardware.lights-service.qti
system         921     1 12909004  5004 0                   0 S android.hardware.memtrack@1.0-service
system         922     1 13163352 20016 0                   0 S android.hardware.neuralnetworks@1.3-service-qti
system         925     1 13044500  6184 0                   0 S android.hardware.power-service
system         926     1 13289876 10180 0                   0 S android.hardware.sensors@2.0-service.multihal
system         929     1 12970212  4944 0                   0 S android.hardware.thermal@2.0-service.qti
system         930     1 12925972  4944 0                   0 S android.hardware.usb@1.0-service
wifi           931     1 12988836 14016 0                   0 S android.hardware.wifi@1.0-service
system         932     1 12960072  5872 0                   0 S vendor.display.color@1.0-service
system         933     1 12999008  6132 0                   0 S vendor.humane.hardware.wlc@1.0-service
system         934     1 12943688  5096 0                   0 S vendor.qti.hardware.capabilityconfigstore@1.0-service
system         935     1 13042840  8096 0                   0 S vendor.qti.hardware.display.allocator-service
system         936     1 13006012  5052 0                   0 S dspservice
root           941     1 13080596  6980 0                   0 S vendor.qti.hardware.iop@2.0-service
root           942     1 13312984 15944 0                   0 S vendor.qti.hardware.perf@2.2-service
system         961     1 12899844  5092 0                   0 S vendor.qti.hardware.qccvndhal@1.0-service
system         964     1 12920796  6240 0                   0 S vendor.qti.hardware.sensorscalibrate@1.0-service
system         965     1 12993124  5420 0                   0 S vendor.qti.hardware.servicetracker@1.2-service
system         966     1 12902804  6008 0                   0 S vendor.qti.hardware.soter@1.0-service
system         967     1 12916264  4972 0                   0 S vendor.qti.hardware.tui_comm@1.0-service-qti
system         975     1 12941912  4736 0                   0 S vendor.qti.power.pasrmanager@1.0-service
vendor_qrtr    977     1 12876608  2920 0                   0 S qrtr-ns
system        1002     1 12924196  4388 0                   0 S pd-mapper
system        1030     1 13033540  4480 0                   0 S pm-service
audioserver   1031     1 13816536 43688 0                   0 S audioserver
system        1054     1 13491816 33708 0                   0 S colorcameraservice
credstore     1062     1 12930040  7672 0                   0 S credstore
gpu_service   1064     1 13001332  7408 0                   0 S gpuservice
system        1065     1 12910976  3184 0                   0 S sh
system        1066     1 13480820 36784 0                   0 S humane_device_manager
humane_syst+  1067     1 12975984 16776 0                   0 S humane_touchpad_service
humane_syst+  1069     1 13014068  5584 0                   0 S humane_wlc_service
root          1070     1 13025820  5792 0                   0 S MemfaultDumpster
humane_pmcu   1076     1 12976804  4100 0                   0 S pmcu_service
system        1078     1 13604516 51304 0                   0 S surfaceflinger
system        1079     1 13757436 32996 0                   0 S tracefilewriterserviceimpl
nobody        1080     1 12946716  3064 0                   0 S rmt_storage
vendor_rfs    1088     1 12881220  4024 0                   0 S tftp_server
system        1093     1 13075204  5588 0                   0 S sensors.qti
root          1096     2       0      0 0                   0 I [modem]
root          1098     2       0      0 0                   0 I [adsp]
root          1099     2       0      0 0                   0 I [adsp]
root          1101     2       0      0 0                   0 S [irq/143-arm-smm]
root          1104     2       0      0 0                   0 S [irq/144-arm-smm]
root          1105     2       0      0 0                   0 I [f_mtp]
root          1107     2       0      0 0                   0 I [at_usb0]
root          1108     2       0      0 0                   0 I [at_usb1]
root          1110     2       0      0 0                   0 I [at_usb2]
system        1111  1065 13806704 50868 0                   0 S ndkhandtracking
root          1113     2       0      0 0                   0 I [rmnet_ctrl]
root          1114     2       0      0 0                   0 I [dpl_ctrl]
root          1115     2       0      0 0                   0 I [qdss]
root          1116     2       0      0 0                   0 I [qdss_mdm]
root          1132     2       0      0 0                   0 S [irq/487-swr_mas]
root          1133     2       0      0 0                   0 S [irq/488-swr_mas]
root          1134     2       0      0 0                   0 S [irq/489-swr_mas]
root          1180     2       0      0 0                   0 S [irq/490-swr_wak]
root          1199     2       0      0 0                   0 I [cds_recovery_wo]
root          1200     2       0      0 0                   0 S [wlan_logging_th]
system        1215     1 12989180  4424 0                   0 S pm-proxy
shell         1218     1 13217856 19004 0                   0 S adbd
drm           1225     1   27880   7508 0                   0 S drmserver
system        1226     1 12966868  4376 0                   0 S humane_accessory_updater
iorapd        1240     1 13145128 12996 0                   0 S iorapd
system        1248     1 13046632  8068 0                   0 S MemfaultStructuredLogd
nobody        1251     1 12930524  8176 0                   0 S traced_probes
nobody        1254     1 12952244  5296 0                   0 S traced
root          1258     1 12945664  5928 0                   0 S dpmd
system        1261     1 13121856  5228 0                   0 S dpmQmiMgr
system        1286  1258 12964548  4508 0                   0 S dpmd
cameraserver  1307     1 13354848 35268 0                   0 S cameraserver
incidentd     1309     1 13070808  5256 0                   0 S incidentd
root          1310     1 12968060  7648 0                   0 S installd
mediaex       1314     1 13492056 35248 0                   0 S media.extractor
media         1316     1 13036804  8940 0                   0 S media.metrics
media         1317     1   66908  20996 0                   0 S mediaserver
root          1318     1 12948436  6428 0                   0 S storaged
wifi          1319     1 12955948  7076 0                   0 S wificond
system        1324     1 13049100  7832 0                   0 S perfservice
system        1328     1   25752   7048 0                   0 S wfdhdcphalservice
mediacodec    1331     1   53956  14608 0                   0 S media.codec
system        1333     1 13151860 12464 0                   0 S cnd
system        1334     1   26856   7612 0                   0 S wifidisplayhalservice
radio         1336     1 13061992  7644 0                   0 S ims_rtp_daemon
radio         1337     1 12899604  3684 0                   0 S imsqmidaemon
radio         1344     1 12956928  9060 0                   0 S imsrcsd
radio         1353     1 12963796  2728 0                   0 S ipacm-diag
root          1355     2       0      0 0                   0 S [glink_modem]
root          1356     2       0      0 0                   0 S [qrtr_rx]
radio         1362     1 14548920 10880 0                   0 S netmgrd
radio         1367     1 13014000  3080 0                   0 S port-bridge
system        1379     1 12956268  5084 0                   0 S adsprpcd
media         1380     1 12979552  5208 0                   0 S adsprpcd
system        1382     1 12980844  5152 0                   0 S cdsprpcd
system        1384     1   20008   3856 0                   0 S wfdvndservice
mediacodec    1385     1 13512884 23156 0                   0 S media.swcodec
system        1394     1 13070088  6512 0                   0 S cnss-daemon
radio         1402     1 12909024  2420 0                   0 S ssgqmigd
gps           1415     1 13011228  4256 0                   0 S mlid
gps           1424     1 12968836  3120 0                   0 S loc_launcher
system        1435     1 13044044  5600 0                   0 S ATFWD-daemon
system        1436     1 12905268  6160 0                   0 S gatekeeperd
root          1439     1 13024204  9588 0                   0 S update_engine
system        1444     1 13120916  5476 0                   0 S qcc-trd
system        1445     1 13008576  4996 0                   0 S tloc_daemon
gps           1460  1424 13034468  5496 0                   0 S lowi-server
gps           1461  1424 13120124  8140 0                   0 S slim_daemon
gps           1462  1424 13169232  9396 0                   0 S xtra-daemon
radio         1475     1 14814228 51588 0                   0 S qcrild
radio         1499     1 13092816  8220 0                   0 S imsdatadaemon
radio         1528     1 13051512  3796 0                   0 S qti
radio         1532     1 12996160  3888 0                   0 S adpl
root          1544     1 12884056  4136 0                   0 S msm_irqbalance
system        1582     1 13028000  3072 0                   0 S hvdcp_opti
system        1666   772 20655188 276924 0                  0 S system_server
root          1812     2       0      0 0                   0 I [ipawq34]
root          1814     2       0      0 0                   0 I [iparepwq34]
root          1816     2       0      0 0                   0 I [ipawq35]
root          1817     2       0      0 0                   0 I [iparepwq35]
root          1890     2       0      0 0                   0 S [psimon]
iorapd        2165  1240 12937372  7964 0                   0 S iorap.prefetcherd
system        2286   772 17466644 85496 0                   0 S humane.connectivity.location_provider_overlays.network
system        2303   772 17449840 89024 0                   0 S humane.connectivity.location_provider_overlays.fused
system        2365   772 17488408 93592 0                   0 S humane.connectivity.desense_manager
radio         2435   772 17614800 90696 0                   0 S .dataservices
u0_a65        2452   772 17521588 86768 0                   0 S .qtidataservices
u0_a92        2469   772 17514216 90520 0                   0 S com.qti.phone
system        2481   772 17450832 90320 0                   0 S humane.connectivity.lqm_service
network_sta+  2496   772 17657408 111144 0                  0 S com.android.networkstack.process
u0_a108       2515   772 17451188 84584 0                   0 S com.qualcomm.qtil.aptxacu
u0_a90        2524   772 17454628 87936 0                   0 S com.qualcomm.qtil.aptxals
system        2533   772 17450820 84788 0                   0 S vendor.qti.qesdk.sysservice
u0_a87        2584   772 17617588 105800 0                  0 S org.codeaurora.ims
secure_elem+  2587   772 17469552 84352 0                   0 S com.android.se
system        2602   772 17519084 91936 0                   0 S humane.grandcentral
system        2619   772 17869680 95860 0                   0 S humane.connectivity.location
radio         2634   772 18232012 98672 0                   0 S com.android.phone
u0_a110       2641   772 17535240 101128 0                  0 S com.qualcomm.qti.qdma
u0_a98        2680   772 18387744 177592 0                  0 S com.android.systemui
system        2700   772 17637076 123916 0                  0 S com.android.settings
u0_a117       2717   772 17531264 120672 0                  0 S android.ext.services
u0_a112       2815   772 17433644 89336 0                   0 S com.qualcomm.qti.qccauthmgr
u0_a102       2855   772 17433328 84444 0                   0 S com.android.smspush
root          2857     1 13132796  5368 0                   0 S humane_antenna_tune
system        2907     1 12907540  4344 0                   0 S qspmsvc
root          2944     2       0      0 0                   0 S [irq/71-90b6300.]
root          2947     2       0      0 0                   0 S [irq/72-90cd000.]
u0_a37        2966   772 17503356 97104 0                   0 S hu.ma.ne.ironman:voiceinteractor
system        2981   772 17738884 101992 0                  0 S com.memfault.usagereporter
u0_a66        3020   772 17449956 84740 0                   0 S .pasr
u0_a26        3046   772 17580156 93036 0                   0 S hu.ma.ne.metricreporter
u0_a94        3054   772 17532228 96024 0                   0 S com.qualcomm.location
system        3089   772 17459676 90972 0                   0 S com.qti.diagservices
u0_a116       3093   772 17634516 112040 0                  0 S com.android.providers.media.module
u0_a37        3125   772 17532028 102652 0                  0 S hu.ma.ne.ironman
system        3143   772 17450844 84668 0                   0 S humane.settings.service
system        3147   772 17966668 291708 0                  0 S humane.experience.onboarding
u0_a32        3178   772 17468984 87128 0                   0 S com.android.timezone.location.provider
u0_a104       3223   772 17469416 85388 0                   0 S com.qualcomm.qti.performancemode
u0_a103       3312   772 17467532 84224 0                   0 S com.qualcomm.qtil.aptxui
u0_a28        3380   772 17561612 111388 0                  0 S android.process.acore
u0_a109       3538   772 17487040 84532 0                   0 S com.qualcomm.telephony
u0_a27        3625   772 17612008 95856 0                   0 S android.process.media
u0_a73        3652   772 17532132 94904 0                   0 S com.android.dialer
u0_a95        3706   772 17558260 106760 0                  0 S org.codeaurora.dialer
u0_a96        3723   772 17470532 88968 0                   0 S com.qualcomm.location.XT
u0_a83        3833   772 17438144 86016 0                   0 S com.android.camera2
u0_a118       3876   772 17477660 98816 0                   0 S com.android.cellbroadcastreceiver.module
u0_a71        3912   772 17437404 87496 0                   0 S com.android.imsserviceentitlement
u0_a72        3920   772 17459124 88900 0                   0 S com.android.contacts
u0_a85        3958   772 17535516 105796 0                  0 S com.android.inputmethod.latin
u0_a91        3994   772 17525360 95380 0                   0 S com.android.mms
u0_a69        4032   772 17433332 82784 0                   0 S com.android.onetimeinitializer
u0_a29        4061   772 17436288 83784 0                   0 S com.android.packageinstaller
u0_a115       4087   772 17618460 93544 0                   0 S com.android.permissioncontroller
u0_a42        4120   772 17451364 92440 0                   0 S com.android.providers.calendar
shell         4140   772 17433744 84992 0                   0 S com.android.shell
u0_a39        4159   772 17555220 88612 0                   0 S com.android.statementservice
u0_a105       4183   772 17439256 89480 0                   0 S com.qualcomm.qct.dlt
u0_a40        4198   772 17753072 121420 0                  0 S humane.voice.tts
u0_a67        4223   772 17420780 84320 0                   0 S com.qualcomm.qti.qms.service.connectionsecurity
u0_a38        4243   772 17723444 100124 0                  0 S hu.ma.ne.bort
u0_a34        4307   772 17552608 105784 0                  0 S hu.ma.ne.bort.ota
u0_a36        4337   772 17727012 105876 0                  0 S hu.ma.ne.krypto
u0_a36        4373   772 17583820 114912 0                  0 S hu.ma.ne.krypto:krypto
u0_a46        4391   772 17433372 84120 0                   0 S com.android.externalstorage
system        4440   772 17438104 87800 0                   0 S humane.experience.settings
root          4462     2       0      0 0                   0 I [kworker/3:2H]
root          4532     2       0      0 0                   0 I [kworker/1:2H]
root          4557     2       0      0 0                   0 I [kworker/2:2H]
root          4758     2       0      0 0                   0 I [kworker/5:2]
root          4875     2       0      0 0                   0 I [kworker/2:1H]
root          4989     2       0      0 0                   0 I [kworker/4:2H]
root          5013     2       0      0 0                   0 I [kworker/3:0H]
root          5084     2       0      0 0                   0 I [kworker/3:2]
root          5194     2       0      0 0                   0 I [kworker/4:1]
u0_a37        5197   772 17562656 117128 0                  0 S hu.ma.ne.ironman:provisioning
root          5269     2       0      0 0                   0 S [scheduler_threa]
root          5270     2       0      0 0                   0 S [cds_ol_rx_threa]
wifi          5279     1 13135580 13784 0                   0 S wpa_supplicant
system        5453   772 17527844 93432 0                   0 S com.android.keychain
root          7112     2       0      0 0                   0 I [kworker/5:1]
root          7206     2       0      0 0                   0 R [kworker/u16:7]
root          7227     2       0      0 0                   0 I [kworker/6:3]
shell         7675  1218 12917436  2348 SyS_nanos+          0 S process-tracker
shell         7678  1218 12935868  2380 SyS_nanos+          0 S process-tracker
shell         7785  1218 12934012  2544 __skb_wai+          0 S logcat
root          7864     2       0      0 0                   0 I [kworker/u17:1]
root          7890     2       0      0 0                   0 I [kworker/6:5]
root          8114     2       0      0 0                   0 I [kworker/3:0]
root          8172     2       0      0 0                   0 I [kworker/1:1]
root          8175     2       0      0 0                   0 I [kworker/6:2]
root          8224     2       0      0 0                   0 I [kworker/7:1]
root          8285     2       0      0 0                   0 I [kworker/7:4]
root          8319     2       0      0 0                   0 I [kworker/6:1H]
root          8349     2       0      0 0                   0 I [kworker/u16:8]
root          8369     2       0      0 0                   0 I [kworker/7:5]
root          8542     2       0      0 0                   0 I [kworker/7:0H]
root          8570     2       0      0 0                   0 I [kworker/1:0]
root          8611     2       0      0 0                   0 I [kworker/u16:9]
root          8658     2       0      0 0                   0 I [kworker/0:2]
root          8698     2       0      0 0                   0 I [kworker/2:1]
root          8722     2       0      0 0                   0 I [kworker/6:4]
shell         8731  1218 12917120  3272 SyS_rt_si+          0 S sh
root          8757     2       0      0 0                   0 I [kworker/6:2H]
root          8779     2       0      0 0                   0 I [kworker/0:0]
root          8783     2       0      0 0                   0 I [kworker/7:0]
root          8789     2       0      0 0                   0 I [kworker/2:0]
root          8804     2       0      0 0                   0 I [kworker/6:0]
root          8820     2       0      0 0                   0 I [kworker/7:1H]
root          8913     2       0      0 0                   0 I [kworker/7:2]
root          8926     2       0      0 0                   0 I [kworker/6:0H]
root          8935     2       0      0 0                   0 I [kworker/2:2]
root          8938     2       0      0 0                   0 I [kworker/6:1]
root          8953     2       0      0 0                   0 I [kworker/1:2]
root          8965     2       0      0 0                   0 I [kworker/7:2H]
root          8968     2       0      0 0                   0 I [kworker/0:1]
root          8979     2       0      0 0                   0 I [kworker/u16:10]
root          8980     2       0      0 0                   0 R [kworker/u16:11]
root          9017     2       0      0 0                   0 I [kworker/1:3]
shell         9018  8731 12956760  3424 0                   0 R ps
root          9019     2       0      0 0                   0 R [kworker/u16:12]
```

# CPUInfo

```
Processor	: AArch64 Processor rev 15 (aarch64)
processor	: 0
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 1
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 2
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 3
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 4
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 5
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xd
CPU part	: 0x805
CPU revision	: 14

processor	: 6
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xf
CPU part	: 0x804
CPU revision	: 15

processor	: 7
BogoMIPS	: 38.40
Features	: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp
CPU implementer	: 0x51
CPU architecture: 8
CPU variant	: 0xf
CPU part	: 0x804
CPU revision	: 15

Hardware	: Qualcomm Technologies, Inc ATOLL-AB
```