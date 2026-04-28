# Compiled dfu-util-0.9

If you have problems to compile dfu-util-0.9 on your Debian 12/MainsailOS 2.2.2 here is a compiled binaries with the actual libs of these OS.

Requirements:

* pkg-config:arm64 1.8.1-1
* libusb-1.0.0:arm64
* build-essential 12.9:arm64

```bash
sudo apt remove dfu-util
sudo apt install build-essential libusb-1.0-0-dev pkg-config
curl https://github.com/SnakeOilXY/ProosaXY/blob/master/Mods/ProosaXY%20Mini/config/dfu-util/dfu-util-0.9.tar.gz --output ~/dfu-util-0.9.tar.gz
tar xvf ~/dfu-util-0.9.tar.gz -C /tmp/
sudo chown root: /tmp/dfu*
sudo chmod 755 /tmp/dfu*
sudo mv /tmp/dfu* /usr/local/bin
```
