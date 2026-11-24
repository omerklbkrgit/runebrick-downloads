# Runebrick Games — Android Beta Downloads

Official Android closed-beta APK distribution repository for **Runebrick Games** (`runebrick-games`).

> **Note / Not:** This repository hosts release binaries only under [GitHub Releases](https://github.com/omerklbkrgit/runebrick-downloads/releases) and contains no source code. Never commit `.apk`, `.aab`, or signing keys into git history.

## Direct Links / Doğrudan Bağlantılar

- **Beta İndirme Merkezi / Beta Download Center:** https://runebrick-games.omerklbkr.workers.dev/beta/
- **Canlı Sürüm Manifesti / Live Manifest (`releases.json`):** https://runebrick-games.omerklbkr.workers.dev/releases.json
- **GitHub Releases:** https://github.com/omerklbkrgit/runebrick-downloads/releases

## Release Tag & Asset Convention / Sürüm Etiketi ve Dosya Kuralları

Each game uses its own tag prefix so updates to one title never break download links for the other:

| Game | Tag Format | Asset Filename | Current Tag / Asset |
| :--- | :--- | :--- | :--- |
| **Project Legend** (*Kadimlerin Mirası*) | `pl-vX.Y.Z` | `ProjectLegend_vX.Y.Z.apk` | `pl-v0.2.10` / `ProjectLegend_v0.2.10.apk` |
| **Toybox Rumble: Mini Survivor** | `tb-vX.Y.Z` | `ToyboxRumble_vX.Y.Z.apk` | `tb-v1.0.0` / `ToyboxRumble_v1.0.0.apk` |

## Android Install & Update Notes / Android Kurulum ve Güncelleme Notları

- **Türkçe:** İndirdiğiniz `.apk` dosyasını açtığınızda Android *"Bilinmeyen uygulamalara izin ver"* uyarısı çıkarsa tarayıcınız veya dosya yöneticiniz için izin verin. Yeni beta sürümlerini eski sürümü silmeden doğrudan üzerine kurabilirsiniz; aynı imzalama anahtarı (keystore) ile imzalandığı sürece kayıt (save) verileriniz korunur.
- **English:** When opening the downloaded `.apk`, allow *"Install unknown apps"* for your browser or file manager if prompted by Android. Installing a newer beta build over an existing installation preserves your local save data as long as builds are signed with the same keystore.
