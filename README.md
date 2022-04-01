# CeneoScraper

## Struktura opini w serwisie [Ceneo.pl](https://www.ceneo.pl/)

|Składowa opinii|Selektor|Nazwazmiennej|Typ danych|
|---------------|--------|-------------|----------|
|opinia|div.js_product-review|||
|identyfikator opinii|div.js_product-review["data-entry-id"\]|||
|autor opinii|span.user-post__author-name|||
|rekomendacja autora|span.user-post__author-recomendation > em|||
|liczba gwiazdek|span.user-post__score-count|||
|treść opinii|div.user-post__text||class|
|lista zalet|||class|
|lista wad|||class|
|dla ilu osób przydatna|button.vote-yes > span||class|
|dla ilu osób nieprzydatna|button.vote-no > span||class|
|data wystawienia opinii|span.user-post__published > time:nth-child(1)["datetime"\]||class|
|data zakupu produktu|span.user-post__published > time:nth-child(2)["datetime"\]||