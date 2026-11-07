BÜDCƏ VƏ XƏRC İZLƏYİCİSİ - müstəqil tətbiq (Claude lazım deyil)

Fayllar: index.html, manifest.webmanifest, sw.js, icon-*.png

1) Pulsuz yerləşdirin (https lazımdır, yoxsa quraşdırma düyməsi çıxmır):
   - Netlify Drop: https://app.netlify.com/drop  -> bu qovluğu sürüşdürüb buraxın
   - və ya GitHub Pages / Cloudflare Pages
2) Alınan linki telefonda açın:
   - Android Chrome: menyu -> "Tətbiqi quraşdır"
   - iPhone Safari: Paylaş -> "Ana ekrana əlavə et"
   - Kompüter (Chrome/Edge): ünvan sətrindəki quraşdırma ikonu
3) APK / Play Store üçün: https://www.pwabuilder.com saytına linki yazın.

Qeydlər:
- Məlumat hər cihazın öz brauzerində saxlanır. Köçürmək üçün Ayarlar -> İxrac (JSON) edib digər cihazda İdxal edin.
- Çatbot burada yerli köməkçidir (xərc, qalıq, hədəf, qənaət məsləhəti). Həqiqi AI üçün öz serverinizi window.cbAsk funksiyasına qoşun. API açarını heç vaxt səhifə koduna yazmayın.
- Yeniləmə: faylı dəyişəndən sonra sw.js içində V dəyərini artırın.
