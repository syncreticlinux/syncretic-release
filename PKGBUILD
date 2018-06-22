# $Id$
# Maintainer: Matt Kowal <matt@mkxt.net>

pkgname=syncretic-release
pkgver=18.08  #$(date +%Y.%m)
pkgrel=1
pkgdesc="Adds the Syncretic lsb-release file"
arch=('any')
url="N/A"
license=('GPL')
groups=('syncretic-core')
depends=('bash')
conflicts=('manjaro-release')
install="syncretic-release.install"
source=("lsb-release")
md5sums=('SKIP')

package() {
    # Copy files
    mkdir -p ${pkgdir}/etc
    install -m644 ${srcdir}/lsb-release ${pkgdir}/etc/
}
