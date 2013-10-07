pkgname=dvtm
pkgver=0.9.git.mark
pkgrel=1
arch=(i686 x86_64)
build() { make -C "$startdir"; }
package() { make -C "$startdir" install DESTDIR="$pkgdir"; }
