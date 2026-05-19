# Maintainer: measles <1mesles1>
pkgname=jgui
pkgver=0.3.1
pkgrel=1
pkgdesc="Interactive TUI menu editor for jgmenu in standalone window managers"
arch=('any')
url="https://github.com/1mesles1/jgui"
license=('GPL3')
depends=('python' 'jgmenu')
source=("git+$url.git#tag=v$pkgver")
sha256sums=('SKIP')

package() {
    install -d "${pkgdir}/usr/bin"

    install -m755 "${srcdir}/${pkgname}/${pkgname}" "${pkgdir}/usr/bin/${pkgname}"
}
