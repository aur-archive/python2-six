# Maintainer: Allan McRae <allan@archlinux.org>

pkgname=python2-six
pkgver=1.1.0
pkgrel=1
pkgdesc="Python 2 and 3 compatibility utilities"
arch=('any')
url="http://pypi.python.org/pypi/six/"
license=('custom')
depends=('python2')
source=(http://pypi.python.org/packages/source/s/six/six-$pkgver.tar.gz)
md5sums=('9e8099b57cd27493a6988e9c9b313e23')

package() {
  cd "$srcdir/six-$pkgver"
  python2 setup.py install --root "${pkgdir}" --optimize=1
}
