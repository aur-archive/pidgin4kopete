# Maintainer: ilusi0n

pkgname=pidgin4kopete
pkgver=1
pkgrel=1
pkgdesc="Pidgin emotions for Kmess/kopete"
arch=('any')
url="http://kde-look.org/content/show.php/Pidgin+Emoticons+for+Kopete?content=70360"
license=('GPL')
conflicts=()
depends=()
options=(!strip)
source=(http://kde-look.org/CONTENT/content-files/70360-pidgin4kopete.tar.gz)

build() {
	mkdir -p $pkgdir/usr/share/emoticons/
	tar -xzvf ${srcdir}/70360-pidgin4kopete.tar.gz -C ${pkgdir}/usr/share/emoticons
}
md5sums=('fde9f0a32639505776923569b8282f4c')