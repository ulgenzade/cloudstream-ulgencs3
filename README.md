<div align="center">

# 🇹🇷 UlgenCS3 — Türkçe CloudStream 3, Nuvio & Stremio Deposu

<p align="center">
  <img src="https://img.shields.io/badge/Lisans-GPL--3.0-blue.svg?style=for-the-badge" alt="GPL-3.0">
  <a href="https://cloudstream.cf/"><img src="https://img.shields.io/badge/CloudStream-v3%20%2F%20Pre--Release-8A2BE2?style=for-the-badge&logo=android&logoColor=white" alt="CloudStream"></a>
  <img src="https://img.shields.io/badge/Nuvio-Native%20JS-00C853?style=for-the-badge&logo=javascript" alt="Nuvio">
  <img src="https://img.shields.io/badge/Stremio-Addon%20v3-8A2BE2?style=for-the-badge&logo=stremio" alt="Stremio">
  <a href="https://gitlab.com/ulgenzade/ulgencs3"><img src="https://img.shields.io/badge/Ana%20Sunucu-GitLab-orange?style=for-the-badge&logo=gitlab" alt="GitLab"></a>
  <a href="https://codeberg.org/Ulgenzade/ulgencs3"><img src="https://img.shields.io/badge/Yedek%20Kale-Codeberg-blue?style=for-the-badge&logo=codeberg" alt="Codeberg"></a>
  <img src="https://img.shields.io/badge/Toplam%20Eklenti-33%20Aktif-success?style=for-the-badge" alt="Eklenti Sayısı">
  <img src="https://img.shields.io/badge/Dil-T%C3%BCrk%C3%A7e-red?style=for-the-badge" alt="Türkçe">
</p>

<p align="center">
  <b>Türkçe anime, yerli/yabancı dizi, vizyon filmleri, belgeseller ve canlı spor/TV yayınlarını tek bir dokunuşla CloudStream 3, Nuvio ve Stremio uygulamalarınıza entegre edin.</b>
</p>

</div>

---

> [!IMPORTANT]
> ### 📢 DUYURU VE BİLGİLENDİRME PANOSU
> Bu GitHub deposu **yalnızca bilgilendirme, vitrin, rehber ve duyuru panosudur**.  
> Projemizin ana üretim ve dağıtım sunucusu **[GitLab (ulgenzade/ulgencs3)](https://gitlab.com/ulgenzade/ulgencs3)**, tam senkronize yedek kalesi ise **[Codeberg (Ulgenzade/ulgencs3)](https://codeberg.org/Ulgenzade/ulgencs3)** depolarımız üzerindedir.  
> Güvenlik ve DMCA politikaları gereğince bu GitHub deposunda **hiçbir kaynak kod, kazıyıcı veya derlenmiş eklenti paketi (.cs3) barındırılmamaktadır.**

---

### 🚀 Hızlı Kurulum Bağlantıları

<div align="center">

<a href="https://intradeus.github.io/http-protocol-redirector/?r=cloudstreamrepo://gitlab.com/ulgenzade/ulgencs3/-/raw/builds/repo.json">
  <img src="https://img.shields.io/badge/📲%20CloudStream'e%20Tek%20T%C4%B1kla%20Ekle-Depoyu%20Y%C3%BCkle-blueviolet?style=for-the-badge&logo=googlechrome&logoColor=white" height="42" alt="CloudStream Tek Tıkla Ekle">
</a>
&nbsp;&nbsp;
<a href="https://intradeus.github.io/http-protocol-redirector/?r=stremio://ulgenzade.gitlab.io/ulgencs3/stremio/manifest.json">
  <img src="https://img.shields.io/badge/🟣%20Stremio'ya%20Tek%20T%C4%B1kla%20Kur-Addon'u%20Ba%C4%9Fla-8A2BE2?style=for-the-badge&logo=stremio&logoColor=white" height="42" alt="Stremio Tek Tıkla Ekle">
</a>

<br><br>

<table>
  <tr>
    <td align="center" width="50%">
      <h3>⚡ CloudStream Kısa Kod İle Kurulum</h3>
      <p>CloudStream &rarr; <b>Ayarlar ⚙️ &rarr; Eklentiler &rarr; + Depo Ekle</b> kutusuna:</p>
      <code>!ulgencs3</code>
      <p><small><i>(Beta / Pre-Release sürümleri için)</i></small></p>
    </td>
    <td align="center" width="50%">
      <h3>📱 QR Kod İle Kurulum</h3>
      <p>Telefon veya TV kameranızla taratın:</p>
      <img src="https://api.qrserver.com/v1/create-qr-code/?size=140x140&margin=4&data=https%3A%2F%2Fintradeus.github.io%2Fhttp-protocol-redirector%2F%3Fr%3Dcloudstreamrepo%3A%2F%2Fgitlab.com%2Fulgenzade%2Fulgencs3%2F-%2Fraw%2Fbuilds%2Frepo.json" alt="CloudStream QR Kod" width="130">
    </td>
  </tr>
</table>

</div>

---

## 🌐 Kalıcı Kısa URL ile Kurulum (Tüm Sürümler & Nuvio Ortak)

CloudStream'in standart sürümlerinde veya kısa kodun desteklenmediği ortamlarda tek satırlık kalıcı yönlendiricimizi kullanabilirsiniz:

```text
https://py.md/ulgencs3
```

---

## 📋 Manuel Kurulum Bağlantıları

### 1. CloudStream 3
Depoyu doğrudan CloudStream'deki **Depo Ekle** alanına aşağıdaki bağlantılardan dilediğinizi yapıştırarak kurabilirsiniz:

* **🦊 Ana Sunucu (GitLab CDN):**
  ```text
  https://gitlab.com/ulgenzade/ulgencs3/-/raw/builds/repo.json
  ```
* **🏔️ Yedek Sunucu (Codeberg CDN):**
  ```text
  https://codeberg.org/Ulgenzade/ulgencs3/raw/branch/builds/repo.json
  ```

---

### 2. Nuvio (Doğrudan Yerel JS Kazıyıcıları)
Nuvio uygulamasında **Settings (Ayarlar) → Plugins / Repositories → Add Repository** alanına yapıştırın:

* **🦊 GitLab CDN (Önerilen):**
  ```text
  https://gitlab.com/ulgenzade/ulgencs3/-/raw/master/nuvio.json
  ```
* **🏔️ Codeberg CDN (Alternatif):**
  ```text
  https://codeberg.org/Ulgenzade/ulgencs3/raw/branch/master/nuvio.json
  ```

> [!TIP]
> **Nuvio Arama İpucu:** Nuvio'da film, dizi veya anime aratabilmek için Addons (Eklentiler) kısmında **Cinemeta** (`https://v3-cinemeta.strem.io/manifest.json`) veya **Kitsu Anime** eklentisinin açık olduğundan emin olun.

---

### 3. Stremio (Doğrudan Addon)
Stremio uygulamasında **Addons → Addon URL Yapıştır** kutusuna ekleyin:

* **🦊 GitLab Pages (CORS Destekli & Sunucusuz):**
  ```text
  https://ulgenzade.gitlab.io/ulgencs3/stremio/manifest.json
  ```

---

## 🧩 Eklenti ve Sağlayıcı Listesi (33 Aktif Sağlayıcı)

Aşağıdaki tüm eklentiler depoyu eklediğinizde listelenir ve tek tek kullanılabilir:

### 🎬 Sinema & Yabancı/Yerli Dizi (21 Sağlayıcı)
| Eklenti | Tür | Özellikler | Durum |
| :--- | :--- | :--- | :---: |
| **İnat Box** | Canlı TV / Sinema / Dizi | v16 Native v2, 64-karakter HMAC Temizleme, SelçukSports & RecTV Fallback | ![Aktif](https://img.shields.io/badge/-Aktif%20(v9)-brightgreen?style=flat-square) |
| **Sinewix** | Film & Dizi | 1080p MediaFire & Çoklu Oynatıcı | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **RecTV** | Canlı TV / Sinema / Dizi | v141 İmzalı API, Dinamik Token & 1080p HLS | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DiziPal** | Dizi & Film | HLS / Çoklu Altyazı & Dublaj | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DiziBox** | Yabancı Dizi | Orijinal / Dublaj / 1080p | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DiziMom** | Dizi & Film | Hızlı Akış / Güncel Kaynak | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Dizilla** | Yabancı Dizi | Çoklu Kaynak & Altyazı | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **SezonlukDizi** | Dizi Arşivi | Eksiksiz Sezon & Bölüm Listeleri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **FilmModu** | Film | 1080p / 4K UHD Seçenekleri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **FilmMakinesi** | Film | Geniş Arşiv, Hızlı Oynatıcı | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **HDFilmCehennemi** | Film & Dizi | Dublaj & Altyazı Seçenekleri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **FullHDFilmizlesene**| Film | 1080p Yüksek Kalite | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **SetFilmİzle** | Film & Dizi | Hızlı CDN / FastPlay Alternatifleri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **JetFilmizle** | Film | Seri Oynatıcı & Geniş Kategori | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Webteİzle** | Film & Dizi | Alternatif Kaynaklar / 1080p | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Kült Filmler** | Klasik & Sinema | Özel Küratör Seçkileri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **SinemaCX** | Film & Sinema | 1080p / Zengin İçerik | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **RareFilmm** | Nadir / Festival | Arşiv ve Festival Filmleri | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DDizi** | Yerli Nostalji & Dizi | Türk Dizileri Arşivi | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **SelçukFlix** | Karışık Medya | Film, Dizi ve Özel Yayınlar | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DiziYou** | Asya / Anime / Dizi | 1080p HLS Akışlar | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |

### 🎌 Anime & Asya Dizileri (8 Sağlayıcı)
| Eklenti | Tür | Çözünürlük & Detay | Durum |
| :--- | :--- | :--- | :---: |
| **AniArşiv (Türk Anime)** | Anime Arşivi | 6.000+ Anime, 70.000+ Bölüm, **1080p MP4 CDN** + Çoklu Fansub | ![Aktif](https://img.shields.io/badge/-Aktif%20(v7)-brightgreen?style=flat-square) |
| **AnimeCiX** | Anime | 1080p TauVideo, AnimeWho & Adonis Fansub | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **OpenAnime** | Anime | 4K Ultra HD & 1080p Doğrudan MP4 | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Anizium** | Anime & Asya | 4K UHD / TR Dublaj & Altyazı | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Anizm** | Anime | 1080p / 720p Çoklu Fansub | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **TrAnimeİzle** | Anime | 1080p / 720p | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **Deokwave** | Anime & Donghua | 4K UHD / 1080p | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **DiziKorea** | K-Drama & Asya | 1080p / 720p | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |

### 📺 Çizgi Dizi & Belgesel (2 Sağlayıcı)
| Eklenti | Tür | Açıklama | Durum |
| :--- | :--- | :--- | :---: |
| **ÇizgiMax** | Nostalji & Çizgi Dizi | Eski ve yeni çizgi dizi arşivi | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |
| **BelgeselX** | Türkçe Belgesel | Popüler ve bilimsel belgesel arşivi | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |

### ⚽ Canlı Spor & Canlı TV (2 Sağlayıcı)
| Eklenti | Tür | Kapsam | Durum |
| :--- | :--- | :--- | :---: |
| **Canlı Spor (SelçukSports)** | Canlı Maç & Spor | SelçukSports 35+ Canlı Maç Yayını, beIN Sports 1-5, S Sport 1-2, Exxen Spor 1-4, Tabii Spor 1-6 | ![Aktif](https://img.shields.io/badge/-Aktif%20(v6)-brightgreen?style=flat-square) |
| **CanliTV** | Canlı Yayınlar | TRT 1, ATV, TV8.5 ve 80+ Ulusal Televizyon Kanalı | ![Aktif](https://img.shields.io/badge/-Aktif-brightgreen?style=flat-square) |

---

## 🌐 Dinamik Alan Adı Yönetimi (`domains.json`)

Projedeki tüm sağlayıcılar, kamuya açık sitelerin erişim engelleri veya alan adı değişikliklerinden etkilenmemesi için GitLab ve Codeberg üzerindeki güncel `domains.json` haritasını dinamik olarak okur:
* Kullanıcıların eklentiyi yeniden indirmesine gerek kalmaz; alan adı değiştiği an tüm kullanıcılar yeni alan adı üzerinden kesintisiz izlemeye devam eder.

---

## ⚖️ Yasal Uyarı

Bu GitHub deposunda hiçbir video, ses dosyası, medya akışı veya kazıyıcı kaynak kodu barındırılmamaktadır. Yalnızca açık kaynaklı istemciler için hazırlanmış genel bilgilendirme ve yönlendirme panosudur.
