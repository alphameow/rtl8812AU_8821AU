# rtl8812AU_8821AU
RTL 8812AU/8821AU driver,  support monitor mode

## How to use

```
make
make install
modprobe 8812au.ko
ifconfig wlan0 up
iwconfig wlan0 mode monitor
```

