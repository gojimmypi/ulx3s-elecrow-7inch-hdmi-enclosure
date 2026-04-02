# Prebuilt FPGA Files

Known working `.bit` files to be used for quick start and testing.

- [HDMI_test_hires.bit](./HDMI_test_hires.bit) from Bruno's [learn FPGA repo](https://github.com/BrunoLevy/learn-fpga/tree/master/Basic/ULX3S/ULX3S_hdmi).
- `fujprog-v48-win64.exe` Pre-compiled Windows executable.
- https://github.com/emard/ulx3s-binother  collection of functional binary files and uploaders to quickstart

## Programming

The Windows executable can be called from WSL:

``` bash
cd /mnt/c/workspace/ulx3s-elecrow-7inch-hdmi-enclosure/bitfiles

 ./fujprog-v48-win64.exe "C:\workspace\ulx3s-elecrow-7inch-hdmi-enclosure\bitfiles\HDMI_test_hires.bit"
 ```


## Build Tools

See

- https://github.com/kost/fujprog

## Other tests

- HDMI [test and exercise video](https://www.youtube.com/watch?v=WJaRHJX4xYA). (reminder to not plug in external HDMI when also using ULX3S HDMI internally)


## Links

- https://github.com/emard/ulx3s