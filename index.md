# Welcome to BitMac

here's a simple guideline for running your bitcoin machine...

you can check the recent available manufacturers from the link below
```
https://www.bitcoin.com/bitcoin-atm-manufacturers
```

here we use Lamassu as an example


the first thing to do is to get a good location for installing your machine

![hotspot](https://bitmachk.github.io/images/hotspot.png)

after setuping your hardware, the next thing your gonna do is to config your admin server


login to your server via the terminal
```
ssh root@<copied ip>
```

![admin panel](https://bitmachk.github.io/images/admin.png)


run install command from server side
```
curl -sS https://raw.githubusercontent.com/lamassu/lamassu-install/nextgen/install | bash
```

setup your wallet(s) and backup your private key(s)

ok, all done! ready to go?!!
