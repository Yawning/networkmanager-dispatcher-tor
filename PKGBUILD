pkgname=networkmanager-dispatcher-tor
pkgver=0.1
pkgrel=1
pkgdesc="Dispatcher Script for tor"
arch=(any)
url="https://github.com/yawning/networkmanager-dispatcher-tor"
depends=("networkmanager" "tor")
source=("10-tor")
sha256sums=("ef807c4a2a25f2538ea8324556c9e14a93fcd91d2eaba3dbb81ab3244fb355be")

package() {
  install -Dm700 $srcdir/10-tor $pkgdir/etc/NetworkManager/dispatcher.d/10-tor
}
