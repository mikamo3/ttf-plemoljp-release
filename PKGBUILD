# Maintainer: mikamo3 <kamo3proj@gmail.com>
pkgname=ttf-plemoljp-release
pkgver=1.6.0
pkgrel=1
pkgdesc="Plex Mono Language JP"
arch=(any)
url="https://github.com/yuru7/PlemolJP"
license=('custom')
provides=()
conflicts=('ttf-plemoljp')
replaces=()
source=("https://github.com/yuru7/PlemolJP/releases/download/v${pkgver}/PlemolJP_NF_v${pkgver}.zip")
md5sums=('SKIP')

package() {
  cd "$srcdir/PlemolJP_NF_v${pkgver}"
	find . -type f -name '*.ttf' -exec install -Dm644 {} -t "${pkgdir}/usr/share/fonts/PlemolJP" \;
}