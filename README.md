# Türkiye İlleri ve İlçeleri JSON / Turkish Cities & Districts JSON

Türkiye’nin illeri ve ilçelerinin **koordinatları** ve **slug’ları** bulunan JSON veri seti.  
Projelerde konum, harita veya API uygulamaları için kullanılabilir.

This is a JSON dataset containing **coordinates** and **slugs** of Turkish cities and districts.  
It can be used in projects, maps, or API applications.

---

## Özellikler / Features
- 81 il ve tüm ilçeleri / 81 provinces and all districts
- Her ilin ve ilçenin koordinat bilgisi (`latitude`, `longitude`) / Coordinates for each city and district
- Slug alanı (URL dostu isimlendirme) / Slug field (URL-friendly names)
- JSON formatında, kullanıma hazır / Ready-to-use in JSON format

---

## Veri Örneği / Data Sample
```json
[
  {
    "id": 1,
    "name": "Adana",
    "latitude": 37.0029,
    "longitude": 35.3194,
    "slug": "adana",
    "towns": [
      {
        "name": "Aladağ",
        "slug": "aladag",
        "latitude": 37.5468,
        "longitude": 35.3951
      },
      {
        "name": "Ceyhan",
        "slug": "ceyhan",
        "latitude": 37.0289,
        "longitude": 35.8178
      }
    ]
  }
]
```
