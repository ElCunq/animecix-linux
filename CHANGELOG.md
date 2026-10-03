# Changelog — v1.2.5 → v1.2.6

## Öne çıkanlar

- **Ana sayfa donma düzeltmesi:** kapak JPEG decode + Bilinear scale artık arka-plan
  işçisinde yapılıyor; ana sayfa açılırken UI bloklanmıyor.
- **Ana sayfaya hero eklendi:** iskelet (skeleton) yükleme, bölümü/filmi doğrulanmış
  animeler öneriliyor, tam genişlik + 1280px kapak.
- **Haberler , Yayın Takvimi ve Keşfet sayfası eklendi:** AnimeciX API ile güncel haberleri ve yayın takvimini takip edebilirsiniz. Keşfet ile yeni animeler keşfediğ izleyebilirsiniz.
- **Arayüz ölçeği serbest oldu:** %100–%125 arası serbest değer (eski %150 tavana çekilir).

## Eklenenler
#### En Önemli Değişiklik: 
- Arayüz baştan aşağı Lowell'in katkıları sayesinde değiştirildi. Daha fazla bilgi için reposuna bakabilirsiniz: https://github.com/Lowell137/animecix-linux

- **Yan ray (sidebar) + daraltma:** sayfalar arası tek tıkla geçiş, daraltınca sadece ikonlar kalır.
- **Arama dialogu:** yazarken bekleyip arar, Enter ilk sonuca gider.
- **Headbar hızlı arama hapı:** üst çubuktan direkt arama, yazınca sonuç penceresi açılır.
- **Devam rafı:** kaldığın bölümler ana sayfada, tek tıkla detaya gidersin.
- **Sayfalı raflar:** uzun listeler sayfa sayfa gezilir, sayaç gösterir.
- **Puan hapı:** detayda TMDB puanı rozet olarak görünür.
- **Sezon ve izlendi filtreleri:** sezona ve izleme durumuna göre süzme.
- **Detay sekmeleri:** Bölümler canlı; Ekip / Benzerler / İncelemeler yakında.
- **Yayın Takvimi:** gün gün yeni bölümler.
- **Keşfet:** tür ve sıralama filtreleriyle tarama, büyük kapaklarla.
- **F1 kısayollar penceresi** ve **F11 tam ekran.**
- **Kuantum responsive kartlar:** pencere büyüyünce kartlar da büyür.
- **Poster-lift hover:** üzerine gelince poster hafifçe kalkar.
  
### DİĞER EKLENEN ŞEYLER
  
- Sürüm-notları popup'ı (changelog).
- Gömülü Adwaita ikonları (GitHub master, 59 SVG) + Adwaita tema kilidi
  + `--check-icons` tanı bayrağı.
- Kapak kalite ayarı etkisine zorunlu önbellek-temizleme popup'ı

## Kaldırılanlar

- Evdeki ortadaki hızlı-arama hapı (headbar hapı duruyor).
- Sayfalar menüsü (`tools_menu`) ve hover-play overlay'i.
- Kapak boru hattından zstd sıkıştırması (ham bayt). 
