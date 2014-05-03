pkgname=python3-epc
pkgver=0.0.5
pkgrel=1
pkgdesc="EPC (RPC stack for Emacs Lisp) server for Python."
arch=('x86_64')
url="http://python-epc.readthedocs.org"
license=('GPLv3')
depends=('python3' 'python3-sexpdata')
source=("http://pypi.python.org/packages/source/e/epc/epc-${pkgver}.tar.gz")
md5sums=('de54a24ace8a9b3f5b2d8f014b8c4a42')

package() {
  cd "$srcdir/epc-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
