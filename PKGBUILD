# Maintainer: Matthew Klein <mklein994@gmail.com>
pkgname=rustup-dummy
pkgver=1
pkgrel=4
#epoch=
pkgdesc="A dummy package for rustup if you installed using the official method"
arch=('any')
url="https://rustup.rs"
license=('MIT' 'Apache')
groups=()
depends=()
makedepends=()
checkdepends=()
optdepends=('lldb: rust-lldb script'
            'gdb: rust-gdb script')
provides=('rust' 'rust-nightly' 'cargo' 'cargo-nightly' 'rustfmt')
conflicts=('rust' 'rustfmt' 'cargo')
replaces=()
backup=()
options=()
install=
changelog=
source=('https://raw.githubusercontent.com/rust-lang/rustup.rs/master/LICENSE-MIT')
sha256sums=('c9a75f18b9ab2927829a208fc6aa2cf4e63b8420887ba29cdb265d6619ae82d5')
noextract=()
validpgpkeys=()

package() {
  install -Dm644 "LICENSE-MIT" "$pkgdir/usr/share/licenses/$pkgname/LICENSE-MIT"
}

# vim:set ts=2 sw=2 et:
