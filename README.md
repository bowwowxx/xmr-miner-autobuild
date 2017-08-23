# xmr-miner-autobuild
for testing...

### miner start
```sh
docker run -idt --restart=always --name=nasbook -e THREADS=4 -e WORKER=nasbook bowwow/xmr-miner-autobuild
```

- -e POOL stratum+tcp://xmr-asia1.nanopool.org:14444
- -e ADDRESS xxx
- -e PAYMENTID xxx
- -e WORKER $HOSTNAME (workname)
- -e THREADS 4 (cpu)
