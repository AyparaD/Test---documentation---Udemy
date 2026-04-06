# Checklist – “Udemy” web və mobil test

## Mobile

### Quraşdırma və launch
- Tətbiq uğurla install olunur (Play market)
- Tətbiq açılır və crash olmur
- Splash screen düzgün göstərilir
- İlk açılışda onboarding düzgün işləyir
- Update zamanı data itmir

### Login / Authorization
- Login düzgün işləyir (valid credentials)
- İnvalid login zamanı düzgün error mesaj göstərilir
- Boş sahələr validasiya olunur
- Session saxlanılır (app bağlanıb açılanda)
- Logout düzgün işləyir

### Navigation
- Bütün ekranlar arasında keçid düzgün işləyir
- Back button düzgün davranır
- Deep link-lər düzgün açılır
- Bottom/Top navigation stabil işləyir

### UI / UX
- UI dizayna uyğun gəlir
- Mətnlər kəsilmir (truncate olmur)
- Düymələr düzgün ölçüdədir və kliklənə bilir
- Scroll düzgün işləyir
- RTL/LTR (məsələn, ərəb dili) düzgün göstərilir

### Input və Validasiya
- Bütün input sahələri düzgün işləyir
- Keyboard düzgün açılır (numeric/text/email)
- Maksimum/minimum uzunluq yoxlanılır
- Xüsusi simvollar düzgün qəbul edilir və ya bloklanır
- Error mesajlar düzgün göstərilir

### Şəbəkə (Network)
- Wi-Fi → Mobile data keçidində problem yoxdur
- Offline rejimdə düzgün mesaj göstərilir
- Zəif internetdə loading göstərilir
- Retry mexanizmi işləyir

### Performans
- Tətbiq tez açılır
- Ekranlar gec yüklənmir
- Scroll zamanı lag yoxdur
- Uzun istifadə zamanı tətbiq donmur

### Background / Foreground
- App background-a keçəndə state saxlamır
- Yenidən açıldıqda məlumat itmir
- Timeout düzgün işləyir
- Push notification gəldikdə app düzgün reaksiya verir

### Device və OS uyğunluq
- Fərqli cihazlarda düzgün işləyir
- Fərqli OS versiyalarında test edilib
- Ekran ölçülərinə uyğun UI
- Orientation (portrait/landscape) düzgün işləyir

### Permissions
- Notification icazəsi düzgün işləyir
- İcazə rədd ediləndə düzgün mesaj göstərilir

### Push Notifications
- Notification gəlir
- Klik edəndə düzgün ekran açılır
- Notification məzmunu düzgündür
- Background-da işləyir

---

## Web

### Browser və launch
- HTTPS sertifikatı aktivdir
- Sayt müxtəlif brauzerlərdə (Google, Edge, Firefox) işləyir
- URL linki düzgün işləyir
- E-maildən göndərilmiş keçid linkləri düzgün yönləndirilir

### Login / Authorization
- Login düzgün işləyir (valid credentials)
- İnvalid login zamanı düzgün error mesaj göstərilir
- Boş sahələr validasiya olunur
- Logout düzgün işləyir

### Navigation
- Header menyusu və digər bütün buttonlar düzgün səhifəyə yönləndirir
- Reload (F5) etdikdə istifadəçi olduğu səhifədə qalır
- Logout etdikdə avtomatik ana səhifə açılır

### UI / UX
- Logo, şəkil və videolar keyfiyyətlidir
- Zoom in/out zamanı səhifə uyğunlaşır
- Responsive dizayn düzgün işləyir
- Kurs kartlarının üzərinə hover zamanı info görünür

### Input və Validasiya
- Bütün input sahələri düzgün işləyir
- Error mesajlar düzgün göstərilir
- Axtarış düzgün nəticə verir

### Təhsil modulu
- Video keçidlərində siyahı avtomatik yenilənir
- Play/pause düzgün işləyir
- Altyazı sinxron işləyir
- Reload edib baxmaq mümkündür

### Ödəniş və səbət
- Ödənişdən sonra kurs siyahıya əlavə olunur
- Discount avtomatik tətbiq edilir

### Performans və təhlükəsizlik
- Eyni hesabla fərqli brauzerlərdə giriş mümkündür
- SQL injection-a qarşı qorunur
- Səhifələr arası keçid 2–3 saniyədir
