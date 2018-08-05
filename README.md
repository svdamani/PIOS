# PIOS

PIOS: Parallel Instructional Operating System - Lab 1 Solution

## Installation

```sh
apt-get install make gcc-4.4 gcc-4.4-multilib qemu

update-alternatives --install /usr/bin/qemu qemu /usr/bin/qemu-i386 20

git clone https://github.com/svdamani/PIOS && cd PIOS/
make grade
```