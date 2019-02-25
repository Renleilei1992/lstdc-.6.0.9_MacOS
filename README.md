# lstdc-.6.0.9_MacOS
"error: library not found for -lstdc++.6.0.9"   temporary solve this problem

- 该项目用于暂时性解决 MacOS 10.14.* 中升级 XCode 至 10.* 版本后编译C++相关代码时出现的报错 "error: library not found for -lstdc++.6.0.9"
- 将项目中的三个文件拷贝到 /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.14.sdk/usr/lib 目录下即可编译成功
