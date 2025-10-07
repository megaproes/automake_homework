# Automake Linux C Project

## Build & install

```bash
autoreconf -i        
./configure          # (default prefix /usr/local)                 
sudo make install

# or:
autoreconf -i && ./configure && sudo make install
```

## Run
```bash
myprog
# Hello from myfunc.h!
# 2 + 3 = 5
```

## Clean
```bash
make clean-all 
```
