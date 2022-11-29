pkgname=ttf-material-design-icons-desktop
pkgver=7.0.96
pkgrel=1
pkgdesc="A community-made icon font based on Google's material design icons"
arch=('any')
url='https://github.com/Templarian/MaterialDesign-Font'
license=('Apache')
source=("${pkgname}-${pkgver}.ttf::${url}/blob/master/MaterialDesignIconsDesktop.ttf?raw=true"
        "${pkgname}-${pkgver}-apache.txt::${url}/blob/master/LICENSE?raw=true")
sha256sums=('c5c8a4a157f53a70a22716d80b7f4d2df5a2a0ee92773e405f7ca6f2572c7ad3'
            '3bae6305bcaa6d10219b999f65c342034c2d40b1c0e8567fa08605e73ccba829')

package() {
    install -Dm644 ${pkgname}-${pkgver}.ttf "${pkgdir}/usr/share/fonts/TTF/MaterialDesignIconsDesktop.ttf"
    install -Dm645 ${pkgname}-${pkgver}-apache.txt "${pkgdir}/usr/share/licenses/$pkgname/LICENSE"
}
