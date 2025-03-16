Power Shell 中编译以支持 Ghidra 11.3.1 版本
- 其实也可以基于老版本（10.4）导入分析后，再使用最新Ghidra打开。
```
$env:GHIDRA_INSTALL_DIR="C:\GreenSW\ghidra_11.3.1_PUBLIC"

cd d:\code\github\ShannonBaseband\reversing\ghidra\ShannonLoader
./gradlew

# 编译结果： ShannonLoader-1.0.4-bdb4cb5-Ghidra_11.3.1.zip
```