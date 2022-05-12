
_theme="Sweet-Garuda"
_pkgname="plasma-splash-sweet-garuda"
pkgname="$_pkgname-git"
_gitname=$_pkgname
pkgver=1
pkgrel=1
pkgdesc="A sweet splash screen for Garuda Linux (KDE Plasma)."
arch=("any")
url="https://github.com/aditya8Raj/$_gitname"
license=("GPL")
depends=("plasma-desktop")
makedepends=("git")
source=("git://github.com/aditya8Raj/$_gitname.git")
sha256sums=("SKIP")


package() {
	cd "$_gitname"
	mkdir -p "${pkgdir}/usr/share/plasma/look-and-feel/"
	cp -dr --no-preserve=ownership "$_theme" "${pkgdir}/usr/share/plasma/look-and-feel/"
}