# lstdc-.6.0.9_MacOS
"error: library not found for -lstdc++.6.0.9"   temporary solve this problem

- 该项目用于暂时性解决 MacOS 10.14.* 中升级 XCode 至 10.* 版本后编译C++相关代码时出现的报错 "error: library not found for -lstdc++.6.0.9"
- 将项目中的三个文件拷贝到 /Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.14.sdk/usr/lib 目录下即可编译成功
- 此三个文件来源于 MacOS 10.13.* 版本中的 XCode 9.* sdk, 换句话说，Mac系统中将XCode降级至XCode 9.*版本即可编译成功.
