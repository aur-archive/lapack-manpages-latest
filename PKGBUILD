# Maintainer: Nyarcel <nyarcel AT SPAMFREE gmail DOT com>
# PKGBUILD revision: 2013-12-15

pkgname=lapack-manpages-latest
pkgver=3.5.0
pkgrel=1
pkgdesc="LAPACK and BLAS manual pages"
arch=('any')
url="http://netlib.org/lapack"
license=('custom')
depends=('man-db')
provides=('lapack-manpages')
source=(http://netlib.org/lapack/manpages.tgz)
md5sums=('275687b7e06498798e88b1ca8481b3e2')

package() {
	echo "Installing manpages"
	mkdir -p "${pkgdir}"/usr/share/man/man3
	install -D "${srcdir}"/man/man3/* "${pkgdir}"/usr/share/man/man3
}
