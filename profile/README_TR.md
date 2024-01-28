# Bilig Crawl

Merhaba! Yeni kurduğumuz kar amacı gütmeyen organizasyonumuz, **Bilig Crawl**, Türkçe içeriklerin toplanmasına adanmıştır. Misyonumuz, akademik ve iş dünyasının Türkçe veri ve içerik eksikliğine destek olmaktır.

## Misyonumuz

Günümüz dünyasında, Büyük Dil Modelleri (LLM) teknolojisinin hızla gelişimi ile Türkçe içeriklerin toplanması büyük bir ihtiyaç haline gelmiştir. Biz, Bilig Crawl olarak, bu eksikliği gidermek için yola çıktık.

## Faaliyetlerimiz

- Yasal sınırlar içerisinde web üzerindeki Türkçe içerikleri toplamak.
- Ortaklarımız aracılığıyla toplanan içerikleri Bilig Crawl sunucularında saklamak.
- Türkçe veriye ihtiyaç duyan şirketler ve akademik çevreler için bir kaynak oluşturmak.

## Şu Anki Durumumuz

- Ekip arkadaşları bulma
- Hukuki yapılanmayı tamamlama
- Ortaklıklar geliştirme
- Proje tasarımı
- Veri işleme hattı (pipeline) oluşturma
- Doğrulama, kodlama ve mimari tasarım

## Gelecek Planlarımız

- Yıllar içinde oluşturacağımız kapsamlı veri seti ile birçok eksikliği gidermek.
- Hem Türk hem de uluslararası alanda yeni ekip arkadaşları ve ortaklıklar eklemek.

## Katılım ve İletişim

Bu sürecin bir parçası olmak isteyen herkesi ekibimize katılmaya davet ediyoruz. İlgileniyorsanız, aşağıdaki bağlantılardan bize ulaşabilirsiniz:

- [Discord](https://discord.gg/stMFSKa7)
- [Linkedin](https://www.linkedin.com/company/biligcrawl)


Yakında yeni ekip arkadaşlarımızı ve ortaklıklarımızı duyuracağız. Takipte kalın!

--- 

Data Format:

| content                | url                      | dtype  | type | length | timestamp    |
|------------------------|--------------------------|--------|------|--------|--------------|
| İstikbal göklerdedir   | http://example.com/page1 | string | book | 4      | 1617187200   |
| İstikbal göklerdedir   | http://example.com/page2 | string | book | 3      | 1617187260   |
| İstikbal göklerdedir   | http://example.com/page3 | string | book | 2      | 1617187320   |

### Table Format

- `content`: Türkçe metin
- `url`: Sayfanın URL'si
- `dtype`: Veri türü, default=string
- `type`: İçerik türü, (book, article vb.)
- `length`: `content`'in kelime sayisi.
- `timestamp`: Scrabing Unix epoch zamanı
