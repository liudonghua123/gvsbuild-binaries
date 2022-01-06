## gvsbuild-binaries

This is an unofficial site for viewing and downloading GTK3 prebuild binaries for windows.

### Download files

| VERSION     | x86         | x64         |
| :---        |    :----:   |    :----:   |
| 3.20        | [gtk3-windows-prebuild-3.20-x86.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.20-x86.zip)       | [gtk3-windows-prebuild-3.20-x64.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.20-x64.zip)   |
| 3.22        | [gtk3-windows-prebuild-3.22-x86.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.22-x86.zip)       | [gtk3-windows-prebuild-3.22-x64.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.22-x64.zip)   |
| 3.24        | [gtk3-windows-prebuild-3.24-x86.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.24-x86.zip)       | [gtk3-windows-prebuild-3.24-x64.zip](https://github.com/liudonghua123/gvsbuild-binaries/releases/download/latest/gtk3-windows-prebuild-3.24-x64.zip)   |

### Build details

You can find the build script on https://github.com/liudonghua123/gvsbuild-binaries/blob/main/.github/workflows/build.yml.

The main build command is `python build.py build --fast-build --keep-tools -p (x86|x64) --gtk3-ver (3.20|3.22|3.24) --vs-ver 16 gtk3`.

### Support or Contact

If you have any bugs or suggestions, please file an issue on https://github.com/liudonghua123/gvsbuild-binaries/issues.
