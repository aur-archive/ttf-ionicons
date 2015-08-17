# Contributor: Andrea Scarpino <andrea@archlinux.org>

pkgname=ttf-ionicons
pkgver=2.0.0
pkgrel=1
pkgdesc="The premium icon font for Ionic Framework"
arch=('any')
license=('MIT')
url='http://ionicons.com/'
depends=('fontconfig' 'xorg-fonts-encodings' 'xorg-font-utils')
install=ttf-font.install
source=("https://github.com/driftyco/ionicons/raw/v${pkgver}/fonts/ionicons.ttf")
md5sums=('0d39918c71ad0bf2db5766fe14828114')

package() {
  install -d "${pkgdir}"/usr/share/fonts/TTF
  install -m644 ionicons.ttf "${pkgdir}"/usr/share/fonts/TTF/
}
