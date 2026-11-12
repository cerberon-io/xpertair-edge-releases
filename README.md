# XpertAir Edge releases

Debian packages of the XpertAir Edge agent for Raspberry Pi OS (64-bit), published here by CI.
This repository holds packages only.

Install, as shown by the setup wizard in XpertAir:

```sh
curl -fLO https://github.com/cerberon-io/xpertair-edge-releases/releases/latest/download/xpertair-edge_arm64.deb
sudo apt install ./xpertair-edge_arm64.deb
```

Enrolled gateways install new releases by themselves, once a day. A release marked as
pre-release is not rolled out.