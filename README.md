# SelfBuilds_MacOS_ARM64
Here are some pre-built frameworks, tools, python packages for Apple Silicon (MacOS ARM64) only.

## OpenCV
### XCode Frameworks
Platforms and architectures:
  * iOS: arm64, armv7
  * iOS Simulator: x86_64, arm64
  * macOS: x86_64, arm64
  * Mac Catalyst: x86_64, arm64
Building command:
'''zsh
python opencv/platforms/apple/build_xcframework.py --out ./build_xcframework
'''
