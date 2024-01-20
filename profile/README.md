## Bilig Crawl👋

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
- `timestamp`: Unix epoch zamanı