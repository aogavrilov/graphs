### Задача: 
Потренируйтесь использовать правила и парсер RML, чтобы преобразовать в RDF несколько датасетов с Kaggle:

Netflix Shows (исходный формат CSV) - как базовую онтологию используйте schema.org, а для генерации URI колонку show_id. \
Для маппинга TV Shows используйте schema:TVSeries и релевантные предикаты, для Movie - schema:Movie.\
Amazon Music Reviews (исходный формат JSON) - используйте schema:Review как основной класс и используйте релевантные для него предикаты. \
Для генерации URI используйте конкатенацию reviewerID и asin, например http://example.com/{reviewerID}/{asin}. \
Для создания URIs, которых нет в schema.org, используйте префикс http://example.com/ 

Курс: **[KG Course](https://migalkin.github.io/kgcourse2021/)**
