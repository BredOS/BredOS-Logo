# Maintainer: bill88t from BredOS

pkgname=bredos-logo
pkgver=2.0
pkgrel=1
pkgdesc="BredOS logo"
arch=('any')
url="https://github.com/BredOS/BredOS-Logo"
license=('GPL3')
source=('bred.png'
        'bred.svg')
sha256sums=('84815afc7ae9b1d30c9b0f22ea32ab36bae4446750905dcd78abd6c70491c405'
            '6aaeda6f98d695b204e89384bf4b3d00801fdfee3c9f0fd8eee9bfe6fad2914f')

package() {
  mkdir -p ${pkgdir}/usr/share/pixmaps
  install -Dm644 ${srcdir}/bred.png ${pkgdir}/usr/share/pixmaps/
  install -Dm644 ${srcdir}/bred.svg ${pkgdir}/usr/share/pixmaps/
}
 
