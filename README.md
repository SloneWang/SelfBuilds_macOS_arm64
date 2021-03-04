# SelfBuilds_macOS_ARM64  
Here are some pre-built frameworks, tools, python packages for Apple Silicon (macOS ARM64).  

## OpenCV  

### Xcode Frameworks *[Download][opencv.xcframeworls]*  
Version: `4.5.1`  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Xcode 12.4  

Platforms and architectures:  
  * iOS: `arm64`, `armv7`  
  * iOS Simulator: `x86_64`, `arm64`  
  * macOS: `x86_64`, `arm64`  
  * Mac Catalyst: `x86_64`, `arm64`  

### Python3 Package *[Download][opencv-python]*  
Version: `4.5.1.48`  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Command Line Tools for Xcode 12.4  
  * Python 3.8.2 (included in Command Line Tools)  
  * numpy 1.18.5 (See installation)  

Platforms and architectures:  
  * macOS: `arm64`  

Installation:  
  1. Download [tensorflow_macos-0.1alpha3.tar.gz][apple.numpy] and extract;  
  2. Open Terminal.app, and run `cd extract_dir/tensorflow_macos/arm64`;  
  3. Activate a python virtual environments (Optional), and run `pip install numpy-1.18.5-cp38-cp38-macosx_11_0_arm64.whl`;  
  4. Download this, goto download_dir, and run `pip install opencv_python-4.5.1.48-cp38-cp38-macosx_11_0_arm64.whl`  

### ~~Pre-built Binaries with Extra Modules *[Download][opencv]*  ~~
> opencv_contrib Included  
> Dynamic Link Libraries  
> Python2.7 Supported  
> Python3.X Unsopported  
> Java Unsopported  

Version: `4.5.1`  

System Requirements:  
  * macOS Big Sur 11.2.2  
  * Xcode 12.4  

Platforms and architectures:  
  * macOS: `arm64`  













[^_^]:links
[opencv.xcframeworls]:https://a/
[opencv-python]:https://b/
[opencv]:https://c/
[apple.numpy]:https://github.com/apple/tensorflow_macos/releases/download/v0.1alpha3/tensorflow_macos-0.1alpha3.tar.gz
