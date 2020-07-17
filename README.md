
## Write Flash

```
esptool.py -p (PORT) -b 921600 write_flash --flash_mode dio --flash_size detect --flash_freq 40m 0x10000 bin/ESPlane2S2.bin 0x1000 bin/bootloader.bin 0x8000 bin/partition-table.bin
```

## Password

SSID：ESPLANE_XXXX
PASSWORD：12345678

