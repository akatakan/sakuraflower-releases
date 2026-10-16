# SakuraFlower

League of Legends için skin yöneticisi. Bu depo yalnız sürümleri barındırır: kurulum dosyası, güncelleme parçaları ve imzalı `update.json`.

## Kurulum

**[SakuraFlower-setup.exe](https://github.com/akatakan/sakuraflower-releases/releases/latest/download/SakuraFlower-setup.exe)** dosyasını indirip çalıştırın (her zaman en son sürüm). Bundan sonraki sürümler uygulamanın içinden gelir: yeni sürüm çıkınca uygulama güncellemeyi ister ve yalnız değişen parçaları indirir.

Güncellemeler ed25519 ile imzalıdır. Uygulama, imzası doğrulanmayan ya da bu depo dışından gelen hiçbir dosyayı kurmaz.

## Uyarı

Riot Games ile bir bağı yoktur. Oyun dosyalarını değiştiren araçların kullanımı Riot'un kullanım koşullarına aykırı olabilir ve hesabınız için risk taşır. Kullanım kendi sorumluluğunuzdadır.

## Lisanslar

- **SakuraFlower**: [Wildflover](https://github.com/Dylan-Marsili/wildflover) v1.0.0 çatalıdır. MIT Lisansı, Copyright (c) 2026 Wildflover.
- **cslol-manager araçları** (`mod-tools.exe`, `wad-make.exe`, `wad-extract.exe`, `cslol-dll.dll`, `cslol-diag.exe`): GPL-3.0. Kaynak kod: https://github.com/LeagueToolkit/cslol-manager
- **7-Zip** (`7z.exe`, `7z.dll`): GNU LGPL ve unRAR kısıtlaması. Lisans metni kurulumda `managers/7zip-License.txt` olarak bulunur. Kaynak kod: https://www.7-zip.org

Uygulamanın kullanırken resmî kaynaklarından indirdiği, bu depoda dağıtılmayan bileşenler:

- **Pengu Loader**: MIT. https://github.com/PenguLoader/PenguLoader
- **LTK patcher**: resmî [ltk-manager](https://github.com/LeagueToolkit/ltk-manager) sürümünden alınır, imzası doğrulanır.
- **Hematite** (Onarım sekmesi): AGPL-3.0, komut satırı kullanımına izin veren istisnayla. https://github.com/RitoShark/Hematite
