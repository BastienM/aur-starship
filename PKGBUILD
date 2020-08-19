pkgname=starship
pkgver=0.44.0
pkgrel=1
pkgdesc="The minimal, blazing-fast, and infinitely customizable prompt for any shell!"
arch=('x86_64')
url="https://github.com/starship/starship"
license=('ISC')
source=("https://github.com/starship/starship/releases/download/v${pkgver}/${pkgname}-${arch}-unknown-linux-gnu.tar.gz")
sha256sums=('0ac99620d1733ec1aa4600ee1472b480a321d10b69477601fd26c99e2bee8021')

package() {
  cd "${srcdir}"
  install -Dm755 ${pkgname} ${pkgdir}/usr/bin/${pkgname}
}
