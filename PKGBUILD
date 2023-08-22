# Maintainer: bill88t from BredOS

pkgname=bredos-logo
pkgver=1.0
pkgrel=1.0
pkgdesc="BredOS logo"
arch=('any')
url="https://github.com/BredOS/BredOS-Logo"
license=('GPL3')
source=('bred.png'
        'bred.svg')
sha256sums=('44fbe830082568383c07dd2c397d4e373b42745bc11d94756d9155354b8cb65b'
            '87dd57a944be1f07fa48466a8228f98db297363226dd4f4238891fd7071439d1')

package() {
  mkdir -p ${pkgdir}/usr/share/pixmaps
  install -Dm644 ${srcdir}/bred.png ${pkgdir}/usr/share/pixmaps/
  install -Dm644 ${srcdir}/bred.svg ${pkgdir}/usr/share/pixmaps/
}
 
