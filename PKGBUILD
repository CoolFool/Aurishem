# Maintainer: CoolFool <coolfool149@gmail.com>
pkgname=aurishem
pkgver=1.0.0
pkgrel=1
pkgdesc="Install packages directly from aur.archlinux.org"
arch=("any")
url="https://github.com/coolfool/aurishem"
license=('MIT')
depends=('python-pydbus' 'python-gobject')
source=('aurishem.tar.gz')
#source=("git://github.com/coolfool/${pkgname}/")
sha1sums=('SKIP')

package() {
    install -D "$srcdir/aurishem/aurishem.desktop" "$pkgdir/usr/share/applications/aurishem.desktop"
    install -D "$srcdir/aurishem/aurishem.png" "$pkgdir/usr/share/icons/hicolor/48x48/apps/aurishem.png"
    install -D "$srcdir/aurishem/aurishem" "$pkgdir/usr/bin/aurishem"
    chmod +x "$pkgdir/usr/bin/aurishem"
    xdg-mime default aurishem.desktop x-scheme-handler/aurishem
}