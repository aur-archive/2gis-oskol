pkgname=2gis-oskol
pkgver=23
pkgrel=1
pkgdesc="Map of Stary Oskol for 2GIS, January 2014"
arch=('i686' 'x86_64')
url="http://oskol.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Staroskol-23.orig.zip")
md5sums=('32468134a2ba07762731a5b8635731af')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Staroskol.dgdat" "${pkgdir}/opt/2gis/oskol.dgdat" || return 1
  
}
