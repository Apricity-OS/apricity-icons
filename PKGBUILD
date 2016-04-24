#Maintainer: Alex Gajewski <agajews@gmail.com>

_pkgname='Apricity Icons'
pkgname=apricity-icons
pkgver=0.1.6
pkgrel=1
pkgdesc='Icons for Apricity OS'
arch=(any)
license=(GPL)
url="https://github.com/Apricity-OS/apricity-icons"
depends=()
source=("apricity-icons.tar.gz")
sha256sums=('f434a47578be52ef9c663afc877f85a479dab9ea6dad2e3f4b8619bd6b886787')

package() {
	mkdir -p "${pkgdir}/usr/share/icons"
	cp -rf "${srcdir}/apricity-icons/Apricity Icons" "${pkgdir}/usr/share/icons"
}
