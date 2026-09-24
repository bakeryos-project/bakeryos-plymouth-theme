# Maintainer: smtdfc <me.smtdfc@gmail.com>

pkgname=bakeryos-plymouth-theme
pkgver=1.0.2
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
}