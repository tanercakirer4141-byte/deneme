# Kurulum Rehberi (Basit Anlatım)

Bu rehber, 5 aracın şu anki durumunu ve senin yapman gereken basit adımları anlatır.
Teknik terim yok. Sırayla oku.

> ⚠️ ÖNEMLİ: Şu an bulut üzerinde geçici bir alanda çalışıyoruz. Buraya kurulanlar
> bir süre sonra silinir. Kalıcı olması için bu araçların **kendi bilgisayarına**
> kurulması gerekir. Rehberin en sonundaki "KALICI YAPMAK" bölümüne bak.

---

## 1) Claude Mem — Hafıza (Claude'un seni hatırlaması)

**Ne işe yarar:** Claude her yeni sohbette sıfırdan başlamaz; önceki işlerini hatırlar.

**Durum:** ✅ KURULDU VE ÇALIŞIYOR. Test ettim, hatırlıyor. Ücret yok.

**Sen ne yapacaksın:** Hiçbir şey. Hazır.

---

## 2) Agent Reach — İnternetten / platformlardan okuma

**Ne işe yarar:** YouTube, Reddit, Instagram, X gibi yerlerden içerik/yorum okur
(sadece okur, paylaşım yapmaz).

**Durum:** ✅ Kuruldu ve Claude görüyor. Ama burada internet kısıtlı olduğu için
canlı test edemedim; senin bilgisayarında çalışır.

**Sen ne yapacaksın (kendi bilgisayarında):**
1. Bir kanal eklemek istersen Claude'a şöyle de: "Agent Reach'e Instagram ekle."
2. Instagram, X (Twitter), Facebook gibi yerler **senin giriş yapmanı** ister.
   Bir pencere açılır, sen kendi hesabınla girersin. (Şifreni Claude'a YAZMA.)

---

## 3) Claude Code Setup — Otomasyon önerileri

**Ne işe yarar:** Bir projeni inceleyip "şunları otomatikleştirebilirsin" diye öneri verir.

**Durum:** ✅ Kuruldu ve Claude görüyor. Şu an incelenecek bir projen yok (klasör boş).

**Sen ne yapacaksın:** Uygulama projene başlayınca Claude'a şöyle de:
"Projemi incele ve otomasyon öner." Önerileri çıkarır; hangisini kuracağımıza
BİRLİKTE karar veririz (kendiliğinden hiçbir şey kurulmaz).

---

## 4) Strix — Güvenlik testi

**Ne işe yarar:** Senin kendi siten/uygulaman için güvenlik açığı arar.

**Durum:** ✅ Kuruldu ve Claude görüyor. Hiçbir tarama BAŞLATILMADI.

**Sen ne yapacaksın (tarama yapmak istediğinde):**
1. Ücretsiz bir "LLM API anahtarı" gerekiyor (örneğin ücretsiz OpenRouter anahtarı).
2. Sadece **kendine ait** site/uygulamayı tara. Başkasının sitesini tarama (yasa dışı).
3. "Strix Cloud" denen ücretli sürümü KULLANMADIM, gerekmez.

---

## 5) FreeLLMAPI — Ücretsiz yapay zeka modelleri

**Ne işe yarar:** Birçok firmanın ücretsiz yapay zekasını tek yerden kullanmanı sağlar.

**Durum:** ✅ Kuruldu ve çalışıyor. Senin Claude hesabına DOKUNMADIM (kuralın gereği).

**Sen ne yapacaksın (kendi bilgisayarında):**
1. Panelde bir hesap oluştur (ekranda bir kurulum kodu çıkar, onu girersin).
2. "Keys" (Anahtarlar) sayfasına git.
3. Ücretsiz firmaların anahtarlarını ekle. Her biri ayrı ücretsiz üyelik ister:
   - Google AI Studio, Groq, Cerebras gibi (hepsi ücretsiz başlangıç verir).
4. $19/yıl ücretli sürüm ZORUNLU DEĞİL, almana gerek yok.

---

## KALICI YAPMAK (en önemli adım)

Yukarıdakilerin kaybolmaması için iki yol var. Biri daha kolay:

**Kolay yol — Bilgisayarını bağla:**
1. Bilgisayarına "Claude" masaüstü uygulamasını kur.
2. Ayarlar → Claude Code → Remote Control bölümüne gir.
3. Bir klasörü paylaş.
4. Bana "bilgisayarımı bağladım" de — o zaman kurulumları doğrudan senin
   bilgisayarına kalıcı yaparım.

**Diğer yol:** Claude Code'u doğrudan kendi bilgisayarında çalıştırmak
(biraz daha teknik, birlikte yapabiliriz).

---

## ÖZET

| Araç | Durum | Sen ne yapacaksın |
|------|-------|-------------------|
| 1. Claude Mem | ✅ Çalışıyor | Hiçbir şey |
| 2. Agent Reach | ✅ Kurulu | Kanal eklerken giriş yap |
| 3. Code Setup | ✅ Kurulu | Projen olunca kullan |
| 4. Strix | ✅ Kurulu | Tararken ücretsiz API anahtarı ekle |
| 5. FreeLLMAPI | ✅ Çalışıyor | Hesap aç + ücretsiz anahtarları ekle |

**En kısa yol:** Önce bilgisayarını bağla, sonra ilk olarak Claude Mem + FreeLLMAPI'yi
kalıcı kuralım. Hazır olunca bana "başla" yaz.
