#Maintainer: Alex Gajewski <agajews@gmail.com>

_pkgname='Apricity Icons'
pkgname=apricity-icons
pkgver=0.1.5
pkgrel=1
pkgdesc='Icons for Apricity OS'
arch=(any)
license=(GPL)
url="https://github.com/Apricity-OS/apricity-icons"
depends=()
source=("apricity-icons.tar.gz")
sha256sums=('70152115c189496683e59e66a5c29f68b72fddc177d615dd2e6b2eeb86c785ed')

package() {
	mkdir -p "${pkgdir}/usr/share/icons"
	cp -rf "${srcdir}/apricity-icons/Apricity Icons" "${pkgdir}/usr/share/icons"
}
