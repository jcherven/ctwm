# Maintainer: Your Name <jcherven@mail.usf.edu>
pkgname=ctwm
pkgver=4.0.3
pkgrel=1
pkgdesc="CTWM is an X11 Window Manager."
arch=('any')
url="https://www.ctwm.org"
license=('GPL')
checkdepends=()
optdepends=()
provides=()
install=
changelog=
source=("~/Downloads/ctwm-4.0.3")
md5sums=()

build() {
	cd "$pkgname-$pkgver"
	make
}

package() {
	cd "$pkgname-$pkgver"
	make DESTDIR="$pkgdir/" install
}
