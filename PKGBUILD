# Maintainer: Holmes <holmes_holmes [at] live [dot] com>

pkgname=documentation-kibojoe
pkgver=1802
pkgrel=2
pkgdesc='User Orientation Guide for Kibojoe Linux'
license=('GPL3')
arch=('x86_64')
url="https://github.com/kibojoe/documentation-kibojoe"
source=("git+$url.git")
sha256sums=('SKIP')

package() {
	cd $srcdir/$pkgname
	install -dm644 $pkgdir/usr/share/doc
	cp -r $srcdir/$pkgname/kibojoe $pkgdir/usr/share/doc
}