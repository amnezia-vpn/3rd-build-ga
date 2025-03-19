# 3rd-build-ga

All binaries that used in [Amnezia-VPN](https://github.com/amnezia-vpn) project built in this repository.

### Usage

This repository contains GitHub Action for each project module. 

Build action is triggered by commit message with build type.

### Build types

Build all modules:
- [all]

Build all modules on specific platform:
- [linux]
- [macos]
- [windows]
- [android]
- [ios]

Build specific module for all platform:
- [awg]
- [xray]
- [cloak]
- [libssh]
- [openssl]
- [openvpn]
- [openvpnadapter]
- [shadowsocks]
- [tun2socks]

Build module for defined platform:
- [macos-awg]
- [linux-awg]
- [ios-awg]
- [android-awg]
- [windows-awg]
- [android-libssh]
- [ios-libssh]
- [linux-libssh]
- [windows-libssh]
- [macos-libssh]
- [android-openssl]
- [linux-openssl]
- [macos-openssl]
- [ios-openssl]
- [windows-openssl]
- [android-openvpn]
- [linux-openvpn]
- [macos-openvpn]
- [windows-openvpn]
- [openvpnadapter-macos]
- [android-shadowsocks]
- [linux-shadowsocks]
- [ios-xray]
- [android-xray]

### Release 

You need to make a release from your action if you want to use built output in main repository. 

We use tags for Release job start. Just put a tag on commit message to store your built output in [GitHub release](https://github.com/amnezia-vpn/3rd-build-ga/releases).

Binaries from [GitHub release](https://github.com/amnezia-vpn/3rd-build-ga/releases) can be uploaded into [3rd-prebuilt](https://github.com/amnezia-vpn/3rd-prebuilt) with sha256 sum and then you can update [3rd-prebuilt](https://github.com/amnezia-vpn/3rd-prebuilt) in main repository. 

