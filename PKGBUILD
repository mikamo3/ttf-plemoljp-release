# Maintainer: mikamo3 <kamo3proj@gmail.com>
pkgname=ttf-plemoljp-release
pkgver=1.5.0
pkgrel=1
pkgdesc="Plex Mono Language JP"
arch=(any)
url="https://github.com/yuru7/PlemolJP"
license=('custom')
provides=()
conflicts=('ttf-plemoljp')
replaces=()
source=("https://github.com/yuru7/PlemolJP/releases/download/v${pkgver}/PlemolJP_NFJ_v1.5.0.zip")
md5sums=('SKIP')

package() {
  cd "$srcdir/PlemolJP_NFJ_v${pkgver}"
	find . -type f -name '*.ttf' -exec install -Dm644 {} -t "${pkgdir}/usr/share/fonts/PlemolJP" \;
}