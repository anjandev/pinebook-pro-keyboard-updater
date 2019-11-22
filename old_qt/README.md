# Pinebook Pro keyboard/touchpad firmware updater

This application does upgrade firmware of the built-in keyboard and touchpad.

## Compiling

```bash
git clone https://github.com/ayufan-rock64/pinebook-pro-keyboard-updater
cd pinebook-pro-keyboard-updater
sudo apt-get install qt5-default libusb-1.0-0-dev
qmake
make
```

## Running (always from terminal)

```bash
sudo ./HLK_SHXXFXX_Update_tool
```

## Upgrading

1. Click start,
2. Look at terminal the upgrade process,
3. Once upgrade finishes, the keyboard/touchpad will not yet work,
4. Suspend (closing lid) or force shutdown (with power button),
5. After resume or restart touchpad should start working.

## License

MIT, 2019, SHEN ZHEN HAI LUCK ELECTRONIC TECHNOLOGY CO., LTD