# Mining Coin

Coin yang standar digunakan disini adalah MBC dan RVN.
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

## MicroBitCoin

![image](https://github.com/user-attachments/assets/0832680f-508e-40fa-9a30-d03e73937ba7)  
![image](https://github.com/user-attachments/assets/0e856eb8-63f3-4e51-aa49-94836e49330a)

Anda bisa menggunakan [WonPay wallet](https://wonpay.io/) untuk mendapatkan wallet address. Disini dicontohkan wallet address menggunakan alamat **BXheTnryBeec7Ere3zsuRmWjB1LiyCFpec**
```sh
./cpuminer -a power2b -o stratum+tcp://power2b.sea.mine.zpool.ca:6242 -u BXheTnryBeec7Ere3zsuRmWjB1LiyCFpec -p c=MBC,zap=MBC
```
* Monitor proses mining di [pool](https://zpool.ca/wallet/BXheTnryBeec7Ere3zsuRmWjB1LiyCFpec)
* Cek jurnal transaksi di [explorer](https://microbitcoinorg.github.io/explorer/)

## Ravencoin

Anda bisa menggunakan trust,atomic,komodo wallet atau yang lainnya untuk mendapatkan wallet address

SugarChain
```sh
./cpuminer --algo yespower --param-n 2048 --param-r 32 --param-key "Satoshi Nakamoto 31/Oct/2008 Proof-of-work is essentially one-CPU-one-vote" -o stratum+tcp://yespowerSUGAR.sea.mine.zpool.ca:6241 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```

YenTen
```sh
./cpuminer --algo yespowerr16 -o stratum+tcp://yespowerR16.sea.mine.zpool.ca:6534 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```

Magpie
```sh
./cpuminer --algo yespower --param-n 2048 --param-r 32 --param-key "Magpies are birds of the Corvidae family." -o stratum+tcp://yespowerMGPC.sea.mine.zpool.ca:6247 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```

Crionic
```sh
./cpuminer --algo yespower --param-n 2048 --param-r 32 --param-key "LTNCGYES" -o stratum+tcp://yespowerLTNCG.sea.mine.zpool.ca:6245 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN,zap=CRNC
```

UraniumX
```sh
./cpuminer --algo yespower --param-n 2048 --param-r 32 --param-key "UraniumX" -o stratum+tcp://yespowerURX.sea.mine.zpool.ca:6236 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN,zap=URX
```

All coin GhostRider Algo
```sh
./cpuminer -a gr -o stratum+tcp://ghostrider.sea.mine.zpool.ca:5354 -u RKJpSmjTq5MPDaBx2ubTx1msVB2uZcKA5j -p c=RVN
```
