# mining
Tools yang digunakan:
[JayDDee](https://github.com/JayDDee/cpuminer-opt/releases)

## Script Desktop

perintah **cpuminer** disesuaikan lagi dengan arsitektur CPU masing-masing dengan aplikasi CPU-Z, pilihannya:
* cpuminer-aes-sse42
* cpuminer-avx
* cpuminer-avx2-aes-sha
* cpuminer-avx2-aes
* cpuminer-avx2-sha-vaes
* cpuminer-avx512-sha-vaes
* cpuminer-avx512
* cpuminer-sse2

## Script Mobile

Perintah Termux : download
```sh
curl -O https://do.my.id/mining/pkg.sh
chmod a+x pkg.sh
./pkg.sh
```

## Zpool

Keungulan Zpool adalah limit payout yang kecil, sehingga kita bisa dibayar walaupun hasil mining sedikit.

SugarChain
```sh
cpuminer --algo yespower --param-n 2048 --param-r 32 --param-key "Satoshi Nakamoto 31/Oct/2008 Proof-of-work is essentially one-CPU-one-vote" -o stratum+tcp://yespowerSUGAR.sea.mine.zpool.ca:6241 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```

YenTen
```sh
cpuminer --algo yespowerr16 -o stratum+tcp://yespowerR16.sea.mine.zpool.ca:6534 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```
