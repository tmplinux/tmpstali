pkgname=tmpstali
pkgver=1.0.1
pkgrel=1
pkgdesc="Part of the tmplinux suite. Temporary Stali"
arch=('any')
url="https://github.com/TheOddCell/tmpstali"
license=('MIT')
depends=('bash' 'git' 'shadow' 'util-linux' 'systemd' 'squashfs-tools')
makedepends=()
source=('tmpstali')
sha256sums=('SKIP')

package() {
    install -Dm755 tmpstali "$pkgdir/usr/bin/tmpstali"
}
