# Maintainer: Matthew Klein <mklein994@gmail.com>
pkgname=rustup-dummy
pkgver=1
pkgrel=3
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
source=('https://raw.githubusercontent.com/rust-lang/rustup.rs/master/LICENSE-MIT'
        'https://raw.githubusercontent.com/rust-lang/rustup.rs/master/LICENSE-APACHE')
sha256sums=('c9a75f18b9ab2927829a208fc6aa2cf4e63b8420887ba29cdb265d6619ae82d5'
            '8173d5c29b4f956d532781d2b86e4e30f83e6b7878dce18c919451d6ba707c90')
noextract=()
validpgpkeys=()

package() {
  for license in APACHE MIT; do install -Dm644 "LICENSE-$license" \
    "$pkgdir/usr/share/licenses/$pkgname/LICENSE-$license"; done
}

# vim:set ts=2 sw=2 et:
