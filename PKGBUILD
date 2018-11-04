# Maintainer: Matthew Klein <mklein994@gmail.com>
pkgname=rustup-dummy
pkgver=1
pkgrel=2
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
source=(https://raw.githubusercontent.com/rust-lang-nursery/rustup.rs/master/LICENSE-MIT)
noextract=()
md5sums=('0b29d505d9225d1f0815cbdcf602b901')
validpgpkeys=()

package() {
	pwd
	install -Dm644 LICENSE-MIT "$pkgdir/usr/share/licenses/$pkgname/LICENSE-MIT"
}
