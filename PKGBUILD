# Maintainer: Somebody <somebody[at]foo[dot]tld>
pkgname=pideo
pkgver=0.3.1
pkgrel=1
pkgdesc="A simple script to play videos from storage devices in your RPi."
url="http://github.com/darkhogg/piplay"
arch=('any')
license=('GPL3')
depends=('udevil' 'udisks2' 'subliminal-git')
source=('pideo')
md5sums=('86d0955d57dbe2b2751c4227dcfcadc3')

package() {
  install -Dm755 pideo "$pkgdir/usr/bin/pideo"
}
