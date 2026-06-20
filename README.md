# Gıda Güvenliği Sözlüğü (mini-app)

Ücretsiz, interaktif **gıda güvenliği terim sözlüğü**: ISO 22000, HACCP, CCP, OPRP, PRP, alerjen
ve daha fazlası. Türkçe tanımlar, kaynağa atıflı. Tek dosyalık, kendi kendine yeten `index.html`
(GitHub Pages'e doğrudan konabilir).

**Canlı:** [Gıda Güvenliği Bilgi Tabanı](https://dokumantum.com/kaynaklar/gida-guvenligi-bilgi-tabani)
**Yayıncı:** [Dokumantum — Gıda Güvenliği Yazılımı](https://dokumantum.com/sektorler/gida)
**Lisans:** Veri CC BY 4.0 (atıf: "Dokumantum, dokumantum.com")

## Kullanım
`index.html` dosyasını bir tarayıcıda aç ya da GitHub Pages ile yayınla. Bağımlılık yok.

## Veri
Tanımlar Codex CXC 1-1969, EU 1169/2011 ve ISO 22000:2018'e atıflıdır; standart metni içermez.
Açık veri olarak da yayımlanmıştır:
[Hugging Face](https://huggingface.co/datasets/FoodSecuriry/turkish-food-safety-iso22000-haccp) ·
[Kaggle](https://www.kaggle.com/datasets/morrispoint/gidaguvenligi) ·
[PyPI](https://pypi.org/project/turkish-food-safety-data/) ·
[npm](https://www.npmjs.com/package/turkish-food-safety-data)

## Yeniden üretme
`index.html`, `npm-package/data/` JSON'larından üretilir:
```bash
node build.js
```

> Bilgilendirme amaçlıdır; resmi standardın yerine geçmez.
