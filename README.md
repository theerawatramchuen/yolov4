# yolov4
yolov4 installation

### Refererence git darknet
https://github.com/alexeyab/darknet <br/>
note: fixed "darknet.py" on error libdarknet.so cannot find file <br/>
solution : replace lib = CDLL(cwd + "/libdarknet.so", RTLD_GLOBAL) <br/>
              with lib = CDLL("[full_path]/libdarknet.so", RTLD_GLOBAL) <br/>
            sample lib = CDLL("/media/sp/thee/darknet/libdarknet.so", RTLD_GLOBAL) <br/>

## YOLOv4-darknet installation and usage on your system (Windows & Linux)
https://techzizou.com/yolo-installation-on-windows-and-linux/#install_linux

## System Spec and Software version<br/>
RTX3060 Ubuntu 20.04 <br/>
### NVIDIA-SMI 470.103.01   Driver Version: 470.103.01   CUDA Version: 11.4 <br/>
cuda tool kits file "cuda_11.1.1_455.32.00_linux.run" <br/>
### Cuda compilation tools, release 11.1, V11.1.105 <br/>
cudnn file "cudnn-11.2-linux-x64-v8.1.1.33.tgz" <br/>
### Makefile refer this github
