# NDHU_Computer-Vision_Spring

`NDHU_Computer-Vision_Spring` project belongs to the Operating system engineering at National Dong Hwa University. The purpose of this project is to compile source code then create a Linux Operating system in QEMU system emulator, finally you can input linux command line in terminal

## Contents

- [Getting Started](#Getting-Started)
  - [Requirements](#Requirements)
  - [Installation](#Installation)
- [Directory Structure](#Directory-Structure)
- [Deployment](#Deployment)
- [Frameworks Used](#Frameworks-Used)
- [Author](#Author)


### Getting Started

###### Requirements

1. Python 3.9
2. Ubuntu 22.04

###### **Installation**

1. Upgrade package

```sh
sudo apt-het update
```

2. Install QEMU

```sh
pip install -r requirement.txt
```

3. Clone the repo and enter repo folder

```sh
git clone https://github.com/appleiphonedddd/NDHU_Computer-Vision_Spring.git
cd NDHU_Computer-Vision_Spring
```

### Directory Structure

```
filetree 
├── HW1
│   └── HW1.ipynb
├── HW2
│   └── HW2.ipynb
├── HW3
│   └── HW3.ipynb
├── LICENSE
└── README.md
```

### Deployment

Compile Makefile then you can input linux command line in terminal

```sh
make qemu-nox
```

### Frameworks Used

- [QEMU](https://www.qemu.org/)

### Author

zozo5120@outlook.com

Name:Egor Lee
