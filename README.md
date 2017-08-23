# xmr-miner-autobuild
for testing...

### miner start
```sh
docker run -idt --name=xmr02 -e THREADS=4 bowwow/xmr-miner-autobuild
```

- -e POOL stratum+tcp://xmr-asia1.nanopool.org:14444
- -e ADDRESS xxx
- -e PAYMENTID xxx
- -e WORKER $HOSTNAME (workname)
- -e THREADS 4 (cpu)
