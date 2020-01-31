## ns-3-allinone + mmwave module + TCP BBR + LOS-NLOS time tracing

This repository contains the source from which I built my ns-3 test environments on GCP VMs. The repository is 41 MB compressed, 155 MB uncompressed.

Included software versions are:

| Component | Version |
|-----------|------------|
| ns-3 | 3.27 |
| [mmWave module](https://github.com/nyuwireless-unipd/ns3-mmwave/releases/tag/v1.2) | 1.2 |
| [BBR module](https://github.com/mark-claypool/bbr) | latest |

### Requirements:
`g++ -v`
gcc version 7.3.0 (Ubuntu 7.3.0-27ubuntu1~18.04) 

`make -v`
GNU Make 4.1
### Compile:

`python build.py`
