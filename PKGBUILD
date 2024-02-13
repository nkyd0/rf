pkgname=rf
pkgver=1.0.0
pkgrel=1
pkgdesc="shortened rm -rf"
arch=('any')
source=("rf.sh")
sha512sums=('SKIP')

package() {
	mkdir -p "${pkgdir}/usr/bin"
	cp "${srcdir}/rf.sh" "${pkgdir}/usr/bin/rf"
	chmod +x "${pkgdir}/usr/bin/rf"
}
