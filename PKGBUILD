# Maintainer: James An <james@jamesan.ca>

pkgname=drupal-l10n-xx-lolspeak
_language=xx-lolspeak
pkgver=7.31
pkgrel=1
pkgdesc="Drupal core translation: Lolspeak"
arch=('any')
url="http://localize.drupal.org/translate/downloads"
_watch="http://localize.drupal.org/translate/downloads"
license=('nonfree')
depends=('drupal')
source=("http://ftp.drupal.org/files/translations/7.x/drupal/drupal-7.31.xx-lolspeak.po")
md5sums=('aca2dd419801029f5f8423723255dc4d')
package () {
    install -Dm644 "${srcdir}/drupal-${pkgver}.${_language}.po" "${pkgdir}/usr/share/webapps/drupal/profiles/standard/translations/drupal-${pkgver}.${_language}.po"
}
