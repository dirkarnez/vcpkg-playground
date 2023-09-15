```
- name: Windows 2019
  os: windows-2019
  install_dir: C:\libKeyFinder
  cmake_extras: >-
    -DVCPKG_TARGET_TRIPLET=x64-windows-static
    -DCMAKE_TOOLCHAIN_FILE=C:\vcpkg\scripts\buildsystems\vcpkg.cmake
  cmake_config: --config RelWithDebInfo
  ctest_config: --build-config RelWithDebInfo
```
