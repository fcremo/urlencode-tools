# Maintainer: fcremo
pkgname="urlencode-tools"
pkgver="0.0.1"
pkgdesc="Tools for urlencoding and urldecoding strings"
pkgrel=1
arch=('any')
license=('GPL')
depends=('python3')

source=("urlencode"
    "urldecode")

sha1sums=("SKIP" "SKIP")

package() {
    echo $pkgdir
    echo $srcdir
    mkdir -p "$pkgdir/usr/bin"
    cp $srcdir/* $pkgdir/usr/bin
}
