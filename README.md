# llvm-nightly-13

LLVM trunk (v13) binary packages

Mac OS build:

```bash
cmake -DLLVM_ENABLE_PROJECTS="clang" -DLLVM_TARGETS_TO_BUILD="X86" -DCMAKE_BUILD_TYPE=MinSizeRel -DLLVM_BUILD_TOOLS="NO"  -G "Unix Makefiles" ../llvm -DLLVM_INSTALL_TOOLCHAIN_ONLY=OFF -DCMAKE_INSTALL_PREFIX=$HOME/workarena/repos/external/llvm-min-install -DLLVM_ENABLE_RTTI=ON
```
