# Maintainer: fffzlfk <fffzlfk@qq.com>
#
# This PKGBUILD was generated by `cargo aur`: https://crates.io/crates/cargo-aur

pkgname=cowsay-bin
pkgver=0.1.0
pkgrel=1
pkgdesc="Cowsay implemented using Rust."
url="https://github.com/fffzlfk/cowsay"
license=("MIT")
arch=("x86_64")
provides=("cowsay")
conflicts=("cowsay")
source=("https://github.com/fffzlfk/cowsay/releases/download/v$pkgver/cowsay-$pkgver-x86_64.tar.gz")
sha256sums=("0b8c5681f3c81a4eeb1fc6be2d8b6b6c7fddf3b0917c09d6163c39673caeff1a")

package() {
    install -Dm755 cowsay -t "$pkgdir/usr/bin"
    install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
