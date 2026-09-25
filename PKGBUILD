# Maintainer: smtdfc <me.smtdfc@gmail.com>

pkgname=bakeryos-plymouth-theme
pkgver=1.1.1
pkgrel=1
pkgdesc="Plymouth boot theme for BakeryOS"
arch=('any')
url="https://github.com/bakeryos-project/bakeryos-plymouth-theme"
license=('GPL-3.0-or-later')
depends=(
  'plymouth'
)
source=(
  
)
sha256sums=(
  
)
install=bakeryos-plymouth-theme.install
options=(!debug !strip)

package() {
  install -d "${pkgdir}/usr/share/plymouth/themes"
  cp -a "${srcdir}/bakeryos" "${pkgdir}/usr/share/plymouth/themes/"
  install -Dm644 "${startdir}/LICENSE" "${pkgdir}/usr/share/licenses/${pkgname}/LICENSE"
}