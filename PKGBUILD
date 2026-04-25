# Maintainer: anto22 <https://github.com/anto22>
pkgname=obs-media-playlist-source
pkgver=0.1.3
pkgrel=1
pkgdesc="Media playlist source plugin for OBS Studio"
arch=('x86_64')
url="https://github.com/CodeYan01/media-playlist-source"
license=('GPL2')
depends=('obs-studio')
makedepends=('cmake')
source=("https://github.com/CodeYan01/media-playlist-source/releases/download/${pkgver}/media-playlist-source-${pkgver}-source.tar.xz")
sha256sums=('afd7ac5351e0b2efc39fa3e821ad3a6c0d8c6c55d635398218babb7249f64082')

build() {
  cd "media-playlist-source-${pkgver}-source"

  cmake -B build -S . \
    -DCMAKE_BUILD_TYPE=Release \
    -DCMAKE_INSTALL_PREFIX=/usr

  cmake --build build
}

package() {
  cd "media-playlist-source-${pkgver}-source"

  DESTDIR="${pkgdir}" cmake --install build
}