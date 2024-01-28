# Bilig Crawl👋

Hello! We are excited to announce our newly founded non-profit organization, **Bilig Crawl**, dedicated to the collection of Turkish content. Our mission is to support the academic and business world's need for Turkish data and content.

## Our Mission

In today's world, with the rapid development of Large Language Models (LLM) technology, the collection of Turkish content has become an inevitable necessity. We, at Bilig Crawl, have embarked on this journey to fill this gap.

## Our Activities

- Collecting Turkish content on the web within legal boundaries.
- Storing the collected content on Bilig Crawl servers through our partners.
- Creating a resource for companies and academic circles in need of Turkish data.

## Our Current Focus

- Recruiting team members
- Completing legal structuring
- Developing partnerships
- Project design
- Establishing a data processing pipeline
- Validation, coding, and architectural design

## Our Future Plans

- To address numerous deficiencies with the comprehensive data set we will create over the years.
- To add new team members and partnerships both from Turkey and internationally.

## Join and Contact Us

We invite everyone interested in being a part of this process to join our team. If you are interested, you can reach us through the following links:

- [Discord](https://discord.gg/stMFSKa7)
- [Linkedin](https://www.linkedin.com/company/biligcrawl)

Stay tuned for announcements of our new team members and partnerships!

## Turkish Readme

[Türkce](profile/README_TR.md)

---

Data Format for Every Dataset:

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
