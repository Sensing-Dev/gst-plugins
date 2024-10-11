Let the root directory be `ROOT_DIR`

## Install

### Pre-req
* Windows 10 (TODO: test Windows 11)
* vcpkg 2024.07.12 or later (1de2026)

### Install plugins

```
cd %ROOT_DIR%
vcpkg.exe install
```

## Set environment variables
```
set PATH=%ROOT_DIR%\vcpkg_installed\x64-windows\bin;%PATH%
set GST_PLUGIN_PATH=%ROOT_DIR%\vcpkg_installed\x64-windows\plugins\gstreamer;%GST_PLUGIN_PATH%
```