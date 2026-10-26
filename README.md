# KYK Yemek Rehberi (Ekim 2026) - GSB Manisa

Bu proje, KYK Yurdunda kalan öğrenciler için geliştirilmiş modern, mobil uyumlu ve PWA destekli yemek menüsü rehberidir.

## 🚀 Öne Çıkan Özellikler

1. **"Bugünün Menüsü" Hero Kartı:**
   - Sayfa açıldığı anda kullanıcının karşısına en üstte bugünün yemeği, çorbası, alternatifleri ve kalorisi doğrudan çıkar.
   - Kartın üzerine tıklandığında doğrudan günün detay penceresi açılır.

2. **Akıllı Saat Geçiş Sistemi:**
   - **Kahvaltı Saati:** 06:00 ile 12:30 arası doğrudan Kahvaltı menüsü aktif gelir.
   - **Akşam Yemeği Saati:** 12:30 ile 23:59 arası Akşam Yemeği menüsü aktif gelir.
   - **Gece / Ertesi Gün Geçişi:** 23:59'dan sonra (00:00 - 12:30 arası) otomatik olarak yeni günün Kahvaltı menüsüne geçer.

3. **Varsayılan Beyaz Tema & Koyu Tema:**
   - Siteye her girildiğinde tertemiz **Aydınlık (Beyaz) Tema** ile başlar.
   - İstenildiğinde sağ üstteki 🌙/☀️ butonu ile oturum süresince gözü yormayan modern karanlık moda geçilebilir.

4. **📱 Web Bildirimleri & PWA (Telefona İndirme):**
   - `manifest.json` ve `sw.js` (Service Worker) ile çevrimdışı çalışma desteği.
   - Android ve iOS'ta "Uygulamayı Yükle" desteği.
   - Web Notification API ile günlük menü hatırlatma bildirimi.

---

## 🌐 Vercel'e Nasıl Yayınlanır?

Bu proje %100 saf HTML, CSS ve JavaScript kullanılarak hazırlanmıştır. Hiçbir harici derleyici veya Node.js bağımlılığı gerektirmez, Vercel'de **0 hata** ile çalışır.

### Yöntem 1: GitHub & Vercel Dashboard (Önerilen)
1. Bu klasörü (`C:\Users\ardau_o60fdxn\Documents\Siteler\kykyemek`) yeni bir GitHub reposuna yükleyin (veya mevcut deponuza commit atın).
2. [vercel.com](https://vercel.com) adresine girin, projenizi seçin.
3. Otomatik olarak saniyeler içinde yayına girecektir.

### Yöntem 2: Vercel CLI İle
Terminalden bu klasöre gelip:
```bash
vercel --prod
```
komutunu çalıştırmanız yeterlidir.
