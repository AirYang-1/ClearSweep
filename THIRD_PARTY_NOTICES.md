# Third-party notices / 第三方声明

ClearSweep v2.0.6 includes unmodified third-party runtime components. ClearSweep application sources are private; the licenses and rights of the following third-party components remain applicable.

| Component | Version | License / notice | Corresponding upstream source |
| --- | --- | --- | --- |
| Qt / Qt Quick, QML, Controls, Effects, SVG and Shader Tools | 6.12.0 | LGPL v3 and component-specific notices | https://code.qt.io/cgit/qt/ ; release tag v6.12.0, modules qtbase, qtdeclarative, qtsvg and qtshadertools |
| PySide6 / Shiboken6 | 6.12.0 | LGPL-3.0-only option stated in the distributed wheel metadata | https://code.qt.io/cgit/pyside/pyside-setup.git/ ; release tag v6.12.0 |
| CPython | 3.14.3 | Python Software Foundation license and included notices | https://www.python.org/downloads/release/python-3143/ |
| Tcl / Tk | 8.6.15 | Tcl/Tk permissive licenses | https://github.com/tcltk/tcl/tree/core-8-6-15 ; https://github.com/tcltk/tk/tree/core-8-6-15 |
| OpenSSL | 3.0.18 | Apache License 2.0 | https://github.com/openssl/openssl/tree/openssl-3.0.18 |
| PyInstaller bootloader | 6.22.3 | GPL v2 with the PyInstaller distribution exception | https://github.com/pyinstaller/pyinstaller/tree/v6.22.3 |

The Qt/PySide libraries are dynamically loaded from the one-file program's temporary extraction directory. ClearSweep does not restrict debugging or modification of LGPL-covered components as permitted by their licenses. No upstream runtime source modifications were made for this release. Build integration is implemented separately from upstream packages.

Full primary license texts are in `licenses/` and the downloadable `ThirdPartyNotices.txt`. Qt's component and bundled third-party notices are documented at https://doc.qt.io/qt-6/licenses-used-in-qt.html and the corresponding upstream module sources. Python's included license file contains additional bundled-runtime notices. Microsoft Windows and .NET Framework are system prerequisites and remain subject to their respective Microsoft licenses.

ClearSweep 自有代码没有在此仓库授予开源许可；这不影响第三方组件许可授予的权利。此仓库不包含商业卸载器的代码、图标或其他素材。
