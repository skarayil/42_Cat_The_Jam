# 🌾 Loot&Roots

<div align="center">

![42 School](https://img.shields.io/badge/School-42-black?style=for-the-badge&logo=42)
![Godot](https://img.shields.io/badge/Godot-4.6-478CBF?style=for-the-badge&logo=godotengine&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-000000?style=for-the-badge&logo=godotengine&logoColor=white)
![Game Jam](https://img.shields.io/badge/42_Cat_The_Jam-2026-purple?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<img src="https://media.giphy.com/media/l3vR3y95Zy0Ojdwje/giphy.gif" width="400" alt="Farm Animation"/>

**42 Kocaeli öğrencilerinin gerçek ilerlemesini yansıtan, tarım ve kaynak yönetimi temelli web oyunu.**

*42 Cat The Jam 2026 kapsamında geliştirildi.*

• [Hikaye](#-hikaye) • [Oynanış](#-oynanış) • [Milestone'lar](#-milestoneler) • [Kurulum](#-kurulum)

</div>

---

## 📖 Hikaye

<img align="right" alt="Farm Gif" width="280" src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExcm05aGR3bDY1MHFxMXo5M2RnZ3Y4dXlweW13dzRyMnczYzV1OGNyeSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/h66lm9kjk5wCFU6IVu/giphy.gif">

42 Kocaeli kampüsünün eteklerinde uzanan bu topraklar, öğrencilere aittir.

Her öğrenci, kampüse ilk adımını attığında küçük bir arazi parçasıyla karşılanır. Bu arazi başlangıçta ıssız, ham ve sadece en temel ürünlere ev sahipliği yapabilecek kadar mütevazıdır. Ama buradaki büyüme, gerçektir.

Ekrana her oturuşta, her projede harcanan saatte, her **Evaluation**'da bu topraklar filizlenir. Bilgisayar başında geçirilen **Log Time** toprağa dönüşür, Evaluation puanları tohuma. Kademeli olarak arazi genişler, yeni canlılar belirir, komşularla ticaret başlar.

**Loot&Roots**, 42 Kocaeli'ndeki yolculuğunun yansımasıdır. Ne kadar büyürsen, toprağın da o kadar büyür. 🌱

---

## 🎮 Oynanış

### 🔄 Temel Döngü

<div align="center">
<img src="https://media.giphy.com/media/3o7TKxOhkNQuFoKNIA/giphy.gif" width="350" alt="Growth Animation"/>
</div>

Oyundaki ilerleme tamamen **gerçek 42 aktivitesiyle** beslenir:

| 42 Aktivitesi | Oyun Etkisi |
|---------------|------------|
| ⏱️ **Log Time** | Tarlada bitkilerin büyüme süresi |
| ✅ **Evaluation Puanları** | Yeni tohum kazanımı |
| 🏆 **Milestone Geçişi** | Yeni tohum ve hayvanların kilidi açılır |

```
Evaluation yap → Tohum kazan → Tarlaya ek → Log Time ile büyüt → Hasat et → Ambara biriktir
```

---

### 🌾 Üretim Zinciri

<img align="right" src="https://media.giphy.com/media/l0MYJlyOwdlT0NOXK/giphy.gif" width="250" alt="Harvest"/>

Her kaynak bir öncekine bağlıdır; zinciri takip etmek ilerlemenin anahtarıdır:

| Adım | Kaynak | Nasıl Elde Edilir |
|------|--------|-------------------|
| 1 | 🌾 Buğday | Tarlada yetiştir (Log Time ile büyür) |
| 2 | 🐔 Tavuk | Milestone 1'de açılır |
| 3 | 🌾 → 🍞 Yem | Buğdayı değirmende işle |
| 4 | 🥚 Yumurta | Yemlenen tavuklardan üretilir |
| 5 | 💰 Oyun Parası | Yumurtaları sat |
| 6 | 👛 Wallet Parası | Oyun parasını 42 Wallet'a dönüştür |

> Her milestone'da yeni tohumlar ve hayvanlar eklenerek zincir genişler.

---

### 🌱 Tohum Sistemi

Her **projenin kendine özel bir tohumu** vardır. O projeyi tamamlamayan öğrenci o tohuma sahip olamaz. Bu sayede her öğrencinin bahçesi, onun 42 yolculuğunun benzersiz bir yansımasıdır.

---

### 🏘️ Koalisyon Mahallesi

<img align="right" src="https://media.giphy.com/media/26tPnAAYY9OKSTiRG/giphy.gif" width="220" alt="Trading"/>

İleri seviyelerde her öğrenci kendi **koalisyonunun mahallesine** taşınır. Aynı mahalledeki öğrenciler birbirleriyle **tohum ticareti** yapabilir — birinin sahip olmadığı tohum, komşusundan temin edilebilir.

---

## 🏆 Milestone'lar

<div align="center">
<img src="https://media.giphy.com/media/xT9IgDECMFGDBexpxS/giphy.gif" width="380" alt="Farm Progress"/>
</div>

Her **Milestone**, 42 Kocaeli'nin halka sistemine karşılık gelir. Bir sonraki milestone'a geçmek için o halkaya ait **Evaluation**'ları tamamlaman gerekir. Toplamda **7 milestone** (0'dan 6'ya) bulunur.

---

### 🌱 Milestone 0 — İlk Toprak

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-0-brightgreen?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-1-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-Yok-lightgrey?style=for-the-badge)

</div>

Kampüse ilk adımını attığında seni küçük bir arazi karşılar. Henüz çok az şey yetişebilir bu toprakta — ama her şey bir tohumla başlar.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| Buğday | — |

---

### 🥬 Milestone 1 — Tarlalar Genişliyor

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-1-green?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-2-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-1-orange?style=for-the-badge)

</div>

Arazi büyüdü. Ahırda ilk sesler duyulmaya başladı.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| Lahana | 🐔 Tavuk |

---

### 🥕 Milestone 2 — Ahır Doluyor

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-2-yellowgreen?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-3-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-2-orange?style=for-the-badge)

</div>

Sürü büyüyor. Toprak daha zengin.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| Havuç | 🐄 İnek |

---

### 🌊 Milestone 3 — Dere Kıyısı

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-3-blue?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-3-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-3-orange?style=for-the-badge)

</div>

Arazinin kenarından bir dere akmaya başladı. Yeni otlaklar, yeni misafirler.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| — | 🐑 Koyun, Dere başlangıcı |

---

### 🍯 Milestone 4 — Kovanlar Uçuşuyor

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-4-yellow?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-3-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-4-orange?style=for-the-badge)

</div>

Çiçekler açtı, arılar geldi. Tatlı bir üretim başlıyor.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| — | 🐝 Arı Kovanları |

---

### 🐟 Milestone 5 — Gölet Canlandı

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-5-cyan?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-3-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-5-orange?style=for-the-badge)

</div>

Dere büyüdü, bir gölete dönüştü. Sabahları olta sesleri duyuluyor.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| — | 🐟 Balık Göleti |

---

### 🐴 Milestone 6 — Çiftlik Tamamlandı

<div align="center">

![Milestone](https://img.shields.io/badge/Milestone-6-gold?style=for-the-badge)
![Tohumlar](https://img.shields.io/badge/Tohum-3-yellow?style=for-the-badge)
![Hayvanlar](https://img.shields.io/badge/Hayvan-7-orange?style=for-the-badge)

</div>

Arazi artık gerçek bir çiftlik. Nalların sesi uzaktan duyuluyor, sadık bir dost da yanında.

| 🌾 Tohum | 🐾 Hayvan |
|----------|----------|
| — | 🐴 At, 🐕 Köpek |

---

## ✨ Özellikler

<div align="center">
</div>

- 🔐 **42 OAuth Entegrasyonu** — 42 Intra hesabıyla güvenli giriş
- 📊 **Gerçek Veri Senkronizasyonu** — Log Time ve Evaluation puanları oyunu besler
- 🌾 **Tarım & Kaynak Yönetimi** — Hasat, ambar, değirmen sistemi
- 🐾 **Hayvan Yetiştiriciliği** — Milestone'a göre açılan hayvanlar ve üretim zincirleri
- 🌱 **Proje Tohumu Sistemi** — Her projeye özel tohum, benzersiz bahçeler
- 🏘️ **Koalisyon Mahallesi** — Öğrenciler arası tohum ticareti
- 💰 **Wallet Entegrasyonu** — Oyun içi ekonominin 42 Wallet'a bağlanması
- 🌐 **Web Export** — Tarayıcıdan direkt oyna, kurulum gerekmez

---

## 🚀 Kurulum

### Gereksinimler

- [Godot Engine 4.x](https://godotengine.org/download)
- Bir 42 Intra hesabı
- Web export template (Godot içinden kurulabilir)

### 1. Repoyu Klonla

```bash
git clone https://github.com/ybalkan/loot-and-roots.git
cd loot-and-roots
```

### 2. 42 API Uygulaması Oluştur

1. [https://profile.intra.42.fr/oauth/applications](https://profile.intra.42.fr/oauth/applications) adresine git
2. **New Application** butonuna tıkla
3. Redirect URI olarak şunu gir:
   ```
   http://localhost:8060/tmp_js_export.html
   ```
4. Oluşturulan **UID** ve **SECRET** değerlerini kopyala

### 3. Konfigürasyon Dosyasını Ayarla

```bash
cp "Loots&Roots/secrets.cfg.example" "Loots&Roots/secrets.cfg"
```

Dosyayı aç ve bilgilerini gir:

```ini
[api42]
uid="ALDIĞIN_UID_BURAYA"
secret="ALDIĞIN_SECRET_BURAYA"
redirect_uri="http://localhost:8060/tmp_js_export.html"
```

> ⚠️ `secrets.cfg` dosyası `.gitignore`'a eklenmiştir — repoya gitmez, güvendesin.

### 4. Projeyi Godot'ta Aç ve Çalıştır

1. Godot Engine'i başlat
2. `Loots&Roots/project.godot` dosyasını import et
3. Web export template'i kur:
   `Project → Export → Add → Web → Export Template...`
4. **F5** ile çalıştır veya sağ üst köşeden web'e export et
5. Karşına çıkan **Login** ekranından 42 hesabınla giriş yap

---

## 🗂️ Proje Yapısı

```
Loots&Roots/
├── scripts/
│   ├── login.tscn         # Giriş sahnesi (main scene)
│   ├── oauth42.gd         # 42 OAuth akışı
│   ├── player_data.gd     # Oyuncu verisi (autoload)
│   ├── game_state.gd      # Oyun durumu (autoload)
│   └── inventory.gd       # Envanter yönetimi (autoload)
├── project.godot
├── secrets.cfg.example    # API kimlik bilgileri şablonu
└── export_presets.cfg     # Web export ayarları
```

---

## 🛠️ Teknik Detaylar

| Özellik | Değer |
|---------|-------|
| Engine | Godot 4.6 |
| Renderer | GL Compatibility |
| Hedef Platform | Web (HTML5) |
| Kimlik Doğrulama | OAuth 2.0 — 42 Intra API |
| Physics | Jolt Physics |
| Thread Desteği | Hayır (Web uyumluluğu için) |

---

## 👥 Geliştiriciler

<div align="center">

### 🧑‍🌾 Yusuf BALKAN
[![42 Profile](https://img.shields.io/badge/42%20Profile-ybalkan-black?style=flat-square&logo=42&logoColor=white)](https://profile.intra.42.fr/users/ybalkan)
[![GitHub](https://img.shields.io/badge/GitHub-ybalkan-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ybalkan)

### 👩‍🌾 Sude Naz KARAYILDIRIM
[![42 Profile](https://img.shields.io/badge/42%20Profile-skarayil-black?style=flat-square&logo=42&logoColor=white)](https://profile.intra.42.fr/users/skarayil)
[![GitHub](https://img.shields.io/badge/GitHub-skarayil-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/skarayil)

*42 Cat The Jam 2026 — Game Jam Projesi* 🌱

**⭐ Projeyi beğendiysen star vermeyi unutma!**

</div>

---
