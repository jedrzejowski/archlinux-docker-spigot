# Maintainer: Adam Jęrzejowski <adam@jedrzejowski.pl>

pkgname=docker-spigot
pkgver="0.0.3"
pkgrel=1
pkgdesc="Spigot Server"
arch=('any')
depends=('docker' 'docker-compose')

package() {

	install -Dm644 "${startdir}/docker-compose.yml" "${pkgdir}/usr/lib/${pkgname}/docker-compose.yml"
	install -Dm644 "${startdir}/systemd.service" "${pkgdir}/usr/lib/systemd/system/${pkgname}@.service"

}
