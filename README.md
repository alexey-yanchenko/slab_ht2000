README
======

### Requirements
```
sudo apt-get install libcurl4-openssl-dev
```
### Compile
```
gcc ht2000.c -lcurl
```
### Usage

```
./ht2000 /dev/hidraw0 http://192.168.1.65:9000
```

Reverse engineered userspace driver for SLAB HT2000 CO2, temperature and
relative humidity (RH) data logger made by Dongguan Xintai Instrument Co.

Full blogpost about reverse engineering this thing: http://globalblindspot.blogspot.be/2016/08/reverse-engineering-slab-ht2000-co2_11.html

Author: Tom Van Braeckel <tomvanbraeckel@gmail.com>

