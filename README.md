php_libjit
==========

Libjit port for php (dev is actually in progress)

# Installation

Install packages :

```bash
apt-get install g++
apt-get install flex
apt-get install bison
apt-get install git
apt-get install php5dev
```

Build libjit from sources :

```bash
git clone https://github.com/agalakhov/libjit.git
cd libjit
./auto_gen.sh
./configure
make && make install
```

Installing the extension :

```bash
git clone https://github.com/ichiriac/php_libjit.git
cd php_libjit
phpize
make && make install
```