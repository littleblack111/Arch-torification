# Maintainer: Jenil
pkgname=arch-torify
pkgver=1.0
pkgrel=1
pkgdesc="A tool for full system torification of Arch Linux"
arch=('x86_64')
url="https://github.com/jenil1122/Arch-torification"
license=('GPL3')
depends=('tor' 'iptables')
source=("https://github.com/jenil1122/Arch-torification/releases/download/${pkgver}/arch-torify")
sha256sums=('SKIP')
conflicts=("arch-torify")


package() {
    install -Dm755 arch-torify "${pkgdir}/usr/bin/arch-torify"
    hash -r
}
