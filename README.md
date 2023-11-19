# bsnes-plus-ext-qt

This is a subset of Qt for use with https://github.com/chronogeran/bsnes-plus for development and distribution purposes only, to permit building of bsnes-plus without adding Qt to Windows' PATH.

This should be updated from the full Qt distribution, and should only include the same files (or a similar set) as what is initially present.

Being a partial, but otherwise unmodified, copy of Qt's offline distribution, this is still beholden to Qt's license.

.lib and .dll files were acquired from https://download.qt.io/archive/qt/5.12/5.12.3/. To replicate, download the .exe, install the msvc2017_64 component, and extract the libs and dlls from the installation.