# Maintainer: Giulio Leone <giulio97.leone@gmail.com>
pkgname=oneos-wallpapers
pkgver=20140908
pkgrel=1
pkgdesc="This provides to One OS's Wallpapers."
arch=('i686' 'x86_64' 'i386')
url="http://infinityos.org/repo/oneosui"
license=('LGPLv2+')
makedepends=('bzr')
_realver=0.3.1
provides=("oneos-wallpapers")
source=https://github.com/g97iulio1609/oneos-wallpapers
md5sums=('SKIP')

package() {
    cd "${srcdir}/${pkgname}"

    mkdir -p "${pkgdir}"/usr/share/backgrounds
    cp -R backgrounds "${pkgdir}"/usr/share/

    mkdir -p "${pkgdir}"/usr/share/gnome-background-properties
    cp -R gnome-background-properties "${pkgdir}"/usr/share/

}
