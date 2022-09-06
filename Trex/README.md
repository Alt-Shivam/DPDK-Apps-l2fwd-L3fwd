# To run a Trex Traffic generator pod on Docker

## TRex traffic generator
TRex traffic generator is a tool designed to benchmark platforms using realistic traffic.

One of the tools through which TRex can be learned and tested is a virtual machine instance or Docker, fully simulating TRex without the need for any additional hardware.

## TRex inside Docker (from v2.37 and up)
With a few commands you can run TRex inside docker with low performance/low footprint. You will need to have docker installed on your system with privileges. We are using in this example RedHat 7.4

Docker hub is located [docker hub](https://hub.docker.com/u/trexcisco/)

### Pull the trex image
```bash
docker pull trexcisco/trex
```
