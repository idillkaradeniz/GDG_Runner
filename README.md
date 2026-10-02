# GDG Runner Düellosu

GDG On Campus Biruni University stand haftası için yazılmış, tarayıcıda çalışan bir sonsuz koşu oyunu. Robot kendiliğinden koşar; oyuncu bug'ların, 404 tabelalarının ve kahve bardaklarının üstünden zıplar. İki kişi bölünmüş ekranda aynı engellere karşı yarışabilir.

## Çalıştırma

`index.html` dosyasına çift tıklayın. Sunucu ve internet bağlantısı gerekmez.

## Modlar

- **Tek kişilik:** Robot çarpana kadar koşar. Skor, kat edilen mesafedir (metre). 1000 metreyi geçen oyuncu sürpriz ödül kazanır.
- **Düello:** Ekran ikiye bölünür ve iki tarafa da aynı engeller, aynı sırayla gelir. İlk çarpan kaybeder.

## Kontroller

| Tuş | İşlev |
|---|---|
| W / Boşluk | Oyuncu 1 zıplar |
| ↑ | Oyuncu 2 zıplar |
| 1 / 2 | Tek kişilik / Düello |
| Enter | Seç / Tekrar oyna |
| Esc | Ana menü |
| F | Tam ekran |
| M | Ses aç/kapat |
| Ctrl + Shift + A | Yönetici paneli |

Tuşu erken bırakırsanız robot daha alçak zıplar. Dokunmatik ekranda ekrana dokunmak zıplatır; düelloda üst yarı Oyuncu 1'i, alt yarı Oyuncu 2'yi zıplatır. Oyun kumandası da desteklenir: 1. kumanda Oyuncu 1'i, 2. kumanda Oyuncu 2'yi yönetir.

## Yönetici paneli

Bu panelden ödül eşiğini, düelloda ödülün nasıl verileceğini, başlangıç hızını ve hız artışını değiştirebilirsiniz. Panelde günlük istatistikler de görünür; bugünün tablosunu ya da tüm verileri buradan sıfırlayabilirsiniz.

Liderlik tablosu ve ayarlar tarayıcının `localStorage` alanında tutulur. Bu veriler o bilgisayara ve o tarayıcıya özeldir.

Varsayılan değerlerin hepsi `index.html` dosyasının başındaki `CONFIG` nesnesindedir.
