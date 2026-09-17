# sendikam-yasal — SİLMEYİN

Bu depo, App Store'da **yayında olan iki uygulamanın** destek ve gizlilik sayfalarını
GitHub Pages üzerinden servis eder. Sayfalar uygulamaların mağaza künyesinde
**zorunlu alan** olarak kayıtlıdır.

| Sayfa | Canlı adres | Nerede kullanılıyor |
|---|---|---|
| `iletisim.html` | https://esatbeyhub.github.io/sendikam-yasal/iletisim.html | Her iki uygulamanın **Support URL**'i |
| `gizlilik.html` | https://esatbeyhub.github.io/sendikam-yasal/gizlilik.html | Her iki uygulamanın **Privacy Policy URL**'i |

Uygulamalar:

- **Sendikam Portal** — Apple ID `6807883652`, `org.sendikam.app`
- **TES-İŞ Isparta** — Apple ID `6807963500`, `org.sendikam.tesisisparta`

## Neden silinmemeli

18 Eylül 2026'da her iki uygulama **Selçuk Çatalkaya**'nın Apple takımına
(Team ID `2QYWQYC5DX`) devredildi, ancak mağaza künyesindeki destek ve gizlilik
adresleri hâlâ bu depoyu gösteriyor. Depo silinir veya GitHub Pages kapatılırsa:

- iki uygulamanın da Support/Privacy linkleri kırılır,
- bu App Review kuralı ihlalidir (Apple uygulamayı mağazadan kaldırabilir),
- KVKK aydınlatma metni erişilemez hale gelir.

## Sayfaları müşterinin kendi alanına taşımak

1. `gizlilik.html` ve `iletisim.html` içeriğini müşterinin sitesine (örn.
   `https://sendikam.org/gizlilik`, `https://sendikam.org/iletisim`) koyun.
2. App Store Connect → ilgili uygulama → **App Information**'da Privacy Policy URL'i,
   sürüm sayfasında **Support URL**'i yeni adreslerle değiştirin.
3. Değişiklik yayına girip doğrulandıktan **sonra** bu depo kapatılabilir.

Taşıma tamamlanana kadar bu depo public ve GitHub Pages açık kalmalıdır.
