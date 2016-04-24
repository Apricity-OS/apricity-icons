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
sha256sums=('b63dc978b869dbe2b27fa13d44c60722b52d7a65a8edeb0f929873156569e3e4')

package() {
	mkdir -p "${pkgdir}/usr/share/icons"
	cp -rf "${srcdir}/apricity-icons/Apricity Icons" "${pkgdir}/usr/share/icons"
}
