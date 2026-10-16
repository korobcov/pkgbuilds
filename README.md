# pkgbuilds

PKGBUILD-ы для Arch Linux / CachyOS, которые я собираю для себя.

| Пакет | Описание |
|-------|----------|
| [1c-enterprise-thin-client](1c-enterprise-thin-client) | 1C:Enterprise 8.3 thin client (from official .deb package) — [подробности](1c-enterprise-thin-client/README.md) |
| [network-manager-amneziawg-git](network-manager-amneziawg-git) | NetworkManager VPN plugin for AmneziaWG |

## Сборка

```sh
git clone https://github.com/korobcov/pkgbuilds
cd pkgbuilds/<пакет>
makepkg -si
```

Если в папке пакета есть `README.md` — сначала прочитайте его: некоторым пакетам нужны
исходные файлы, которые нельзя положить в репозиторий (например, дистрибутив 1С).
