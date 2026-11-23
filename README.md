# CLB Proje

Kurumsal, mobil uyumlu, beş dilli (TR/EN/DE/FR/AR) tanıtım sitesi.

## Ana sayfa videosu

Ana sayfa `index.html` içinde çelik konstrüksiyon video arka planı için hazırdır. **Gerçek video dosyası henüz depoda bulunmuyor.** Video görünmesi için lisansı doğrulanmış gerçek şantiye çekimini aşağıdaki dosyalardan en az biri olarak yükleyin:

- `assets/steel-construction.mp4` (H.264, sessiz, web için optimize edilmiş)
- `assets/steel-construction.webm` (isteğe bağlı)

Video otomatik, sessiz, döngüde ve mobilde satır içi oynatılır. Hareket azaltma tercihi olan kullanıcılar için video gizlenir. Dosya yoksa CSS arka plan görseli gösterilir. Mevcut poster uzak görsel kullanır; yayın öncesi firmanın kendi görseliyle değiştirilmesi önerilir.

## Yayın

Statik site olarak GitHub Pages veya başka bir statik sunucuda yayınlanabilir. Özel alan adı için DNS ve barındırma ayarları ayrıca yapılmalıdır. Bu depo güncellemesi otomatik olarak `www.clb.com.tr` alan adına yayın yapmaz.

## Kontrol listesi

- Video dosyasının gerçek, lisanslı şantiye çekimi olduğunu doğrulayın.
- Mobilde otomatik oynatmayı ve yedek görseli test edin.
- Beş dil ve Arapça RTL görünümünü test edin.
- İletişim bilgilerinin müşteri tarafından onaylandığını doğrulayın.
