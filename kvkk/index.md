---
title: "KVKK Aydınlatma Metni"
lang: tr
source: docs/legal
---

# KVKK Aydınlatma Metni

Son güncelleme: 13.11.2026

Bu metin, 6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) m.10 ve Aydınlatma Yükümlülüğünün Yerine Getirilmesinde Uyulacak Usul ve Esaslar Hakkında Tebliğ uyarınca, Kazan uygulamasını (Uygulama) kullanırken hangi kişisel verilerinin, hangi amaçla ve hangi hukuki sebeple işlendiğini, kimlere aktarıldığını, ne kadar saklandığını ve haklarını nasıl kullanacağını anlatır.

## 1. Veri sorumlusu

- Veri sorumlusu: Cengizhan Köse (gerçek kişi; Uygulamayı geliştiren ve yayımlayan bağımsız geliştirici)
- E-posta: me@cengizhankose.com
- Uygulama içinden: Ayarlar > Gizlilik > Verilerimi sil

## 2. Hangi verileri işliyoruz

- Kurulum kimliği: Uygulama ilk açıldığında cihazında rastgele üretilen bir kimlik (UUID). Adın, e-postan, telefon numaran veya reklam kimliğin (IDFA) bu kimliğe bağlanmaz; yine de kurulumunu ayırt ettiği için kişisel veri olarak işlenir. Ayarlar ekranının altında "Destek kimliği" olarak görünür. Hesap açman gerekmez.
- Plan tercihleri: kaç kişilik yemek yaptığın, hangi akşamlar yemek yapacağın, haftalık bütçen, seçtiğin marketler (zincir, şube, il ve ilçe; varsa şubenin OpenStreetMap kimliği) ve varsa evde olan malzemeler ile semt pazarı tercihin.
- Plan ve liste verileri: planın haftası, seçilen ve değiştirilen yemekler, seçtiğin market, market başına toplam tutarlar, alışveriş listesinde işaretlediğin kalemler, alışveriş kanalı (mağaza, online veya marketlere bölünmüş) ile oluşturma ve güncelleme zamanları.
- Kullanım (analitik) verileri, yalnızca izin verirsen: Uygulama içindeki adımların adları ve özellikleri (örneğin kurulum adımları, kişi sayısı, akşam sayısı, bütçe ve plan toplamı, seçilen market zinciri, market değişikliği, liste açıldı, paylaşıldı, ödeme ekranı ve satın alma adımları), kurulum kimliği, uygulama sürümü, işletim sistemi ve Uygulamayı bir kampanya bağlantısıyla açtıysan ilk kampanya bilgisi (utm_source, utm_medium, utm_campaign, code).
- Abonelik verileri, satın alma yaparsan: kurulum kimliği, Apple işlem kimlikleri ve makbuz bilgisi, ürün, deneme ve abonelik durumu, başlangıç, yenilenme ve bitiş tarihleri, fiyat ve para birimi.
- Bağlantı verisi: Uygulama bir sunucuya bağlandığında IP adresin teknik olarak o sunucuya ulaşır. Biz bunu ayrıca kaydetmeyiz; hizmet sağlayıcıların ayarları 5. bölümde yazıyor.

Uygulama konum izni istemez ve GPS kullanmaz; il, ilçe ve şubeyi sen seçersin. Adını, e-postanı, telefonunu, rehberini veya fotoğraflarını istemeyiz. Sağlık, alerji, din gibi özel nitelikli kişisel veri (KVKK m.6) işlemeyiz.

## 3. Amaçlar ve hukuki sebepler

- Planını oluşturmak, fiyatlandırmak, kaydetmek ve Uygulamayı yeniden kurduğunda geri getirmek (kurulum kimliği, plan tercihleri, plan ve liste verileri): talep ettiğin hizmetin sunulması için sözleşmenin kurulması ve ifasıyla doğrudan ilgili olması (KVKK m.5/2-c).
- Premium aboneliği sağlamak, doğrulamak ve geri yüklemek (kurulum kimliği, abonelik verileri): sözleşmenin ifası (m.5/2-c); abonelikle ilgili bir uyuşmazlıkta hakkın tesisi, kullanılması veya korunması (m.5/2-e).
- Uygulamayı iyileştirmek için kullanım istatistiği üretmek (analitik verileri): açık rızan (m.5/1). İzin vermezsen hiçbir analitik veri toplanmaz ve Uygulamayı aynen kullanırsın.
- Hizmetin güvenli ve kesintisiz çalışması (bağlantı verisi): temel hak ve özgürlüklerine zarar vermemek kaydıyla meşru menfaatimiz (m.5/2-f).

## 4. Toplama yöntemi

Veriler, Uygulamaya girdiğin seçimlerden ve Uygulamanın çalışması sırasında otomatik yollarla, elektronik ortamda toplanır. Abonelik verileri Apple App Store'dan Adapty aracılığıyla gelir.

## 5. Kimlere aktarıyoruz

- Convex, Inc. (ABD şirketi; veritabanı ve sunucu hizmeti): kurulum kimliği, plan tercihleri, plan ve liste verileri. Veriler Convex'in Avrupa Birliği bölgesinde (İrlanda) tutulur.
- PostHog, Inc. (ABD şirketi; ürün analitiği): yalnızca izin verirsen analitik verileri. PostHog'un Avrupa Birliği bulutu (Frankfurt, Almanya) kullanılır. Ham IP adreslerinin olaylarla birlikte saklanmaması ayarı açıktır.
- Adapty Tech Inc. (ABD şirketi; abonelik altyapısı): kurulum kimliği ve abonelik verileri. Adapty'nin sunucuları ABD'dedir. Adapty'de IP adresi ve reklam kimliği (IDFA) toplama kapalıdır; abonelik olaylarının başka analitik hizmetlerine iletilmesi kapalıdır.
- Apple: Ödemeyi Apple alır ve kendi gizlilik politikasına göre işler. Kart bilgilerini hiçbir zaman görmeyiz.
- Yetkili kamu kurum ve kuruluşları: yalnızca kanunen zorunlu olduğunda.

Hizmet sağlayıcılar verileri yalnızca bize hizmet vermek için ve bizim talimatlarımızla işler; bu yükümlülükler onların veri işleme sözleşmelerinde ve kullanım koşullarında yer alır. Verilerini satmayız ve reklam amacıyla kimseyle paylaşmayız.

## 6. Yurt dışına aktarım

Yukarıdaki hizmet sağlayıcılarının sunucuları Türkiye dışındadır: Convex ve PostHog Avrupa Birliği'nde (İrlanda, Almanya), Adapty ABD'dedir. Bu nedenle 5. bölümde sayılan veriler, aynı amaçlarla bu ülkelere aktarılır.

## 7. Ne kadar saklıyoruz

- Cihazındaki veriler (kurulum kimliği, planın, tercihlerin): Uygulamayı silene ya da Verilerimi sil'e basana kadar cihazında kalır.
- Sunucudaki plan, liste ve tercih verileri: son güncellemeden 12 ay sonra otomatik olarak silinir; Verilerimi sil'e bastığında hemen silinir.
- Analitik olayları: PostHog'da 1 yıl saklanır, süre dolunca silinir. Kurulum kimliğine bağlı profil kaydı (uygulama sürümü, ilk kampanya bilgisi) Verilerimi sil'e bastığında olaylarla birlikte silinir. İzni geri çekersen yeni veri gönderilmez ve cihazında bekleyen olaylar silinir.
- Abonelik verileri: aboneliğin sürdüğü ve doğrulanması gerektiği sürece Adapty'de tutulur; Verilerimi sil'e bastığında silinir. Satın almanın kendisi Apple'daki kayıtlarda kalır ve "Satın alımları geri yükle" ile yeniden bağlanabilir.

Süre dolunca veya talebin üzerine veriler silinir, yok edilir ya da anonim hâle getirilir (KVKK m.7).

## 8. Hakların (KVKK m.11)

- Kişisel verinin işlenip işlenmediğini öğrenme,
- İşlenmişse buna ilişkin bilgi talep etme,
- İşlenme amacını ve amacına uygun kullanılıp kullanılmadığını öğrenme,
- Yurt içinde veya yurt dışında aktarıldığı üçüncü kişileri bilme,
- Eksik veya yanlış işlenmişse düzeltilmesini isteme,
- KVKK m.7'deki şartlar çerçevesinde silinmesini veya yok edilmesini isteme,
- Düzeltme, silme ve yok etme işlemlerinin aktarıldığı üçüncü kişilere bildirilmesini isteme,
- Münhasıran otomatik sistemlerle analiz edilmesi sonucunda aleyhine bir sonuç çıkmasına itiraz etme,
- Kanuna aykırı işleme nedeniyle zarara uğrarsan zararın giderilmesini talep etme.

## 9. Nasıl başvurursun

- Silme: Ayarlar > Gizlilik > Verilerimi sil. Bu düğme sunucudaki planlarını, kullanım istatistiklerini ve abonelik kaydını siler, cihazındaki plan ve tercihleri sıfırlar. Talebin bu şekilde Uygulama üzerinden anında yerine getirilir.
- Diğer talepler: me@cengizhankose.com adresine Türkçe yaz. Hesap olmadığı için kaydını yalnızca kurulum kimliğinle bulabiliriz; Ayarlar ekranının altındaki destek kimliğini, adını soyadını ve talebini mesajına ekle. Posta yoluyla başvurmak istersen yazışma adresini bu e-posta adresinden isteyebilirsin.

Başvurunu en geç 30 gün içinde ücretsiz sonuçlandırırız (KVKK m.13). Başvurun reddedilir, cevabımızı yetersiz bulursan veya süresinde cevap vermezsek, cevabı öğrendiğin tarihten itibaren 30 gün ve her hâlde başvuru tarihinden itibaren 60 gün içinde Kişisel Verileri Koruma Kurulu'na şikâyette bulunabilirsin (KVKK m.14).

## 10. Çocuklar

Uygulama yetişkinlerin ev bütçesi için tasarlanmıştır; 13 yaşından küçük çocuklara yönelik değildir ve onlardan bilerek veri toplamayız. 18 yaşından küçüksen analitik izni vermeden ve satın alma yapmadan önce ebeveyninle konuş. Böyle bir verinin bize ulaştığını düşünüyorsan me@cengizhankose.com adresine yaz; sileriz.

## 11. Veri Sorumluları Sicili (VERBİS)

Gerçek kişi veri sorumlusu olarak çalışan sayısı ve yıllık mali bilanço bakımından Kişisel Verileri Koruma Kurulu'nun belirlediği eşiklerin altındayız ve ana faaliyetimiz özel nitelikli kişisel veri işlemek değildir. Bu nedenle Veri Sorumluları Siciline kayıt yükümlülüğünden muafız.

## 12. Değişiklikler

Bu metni değiştirirsek güncel sürümü Uygulamada ve [gizlilik sayfasında](https://cengizhankose.github.io/butcemenu-legal/privacy/), en üstteki tarihi güncelleyerek yayımlarız. Verilerini yeni bir amaçla işleyeceksek bunu işlemeye başlamadan önce sana ayrıca bildiririz.
