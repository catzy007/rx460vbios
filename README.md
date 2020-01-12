# rx460vbios

### Install
```
tar -xf atiflash_linux.tar.xz 
sudo mv atiflash /bin
```

### Usage
```
sudo atiflash -i
sudo atiflash
sudo atiflash -f -p 0 Sapphire.RX560.4096.170419.rom
sudo atiflash -f -p 0 Sapphire.RX460.4096.Micron.Ori.rom 
```

> Tested on Xubuntu 18.04

> My rx460 doesn't have 6 pin pcie power so reducing the boost clock is a must.
try to reduce the boost clock to 1250 Mhz or lower
