# Club Inventory / Kulüp Envanteri

[Türkçe](#türkçe) | [English](#english) 

---

## Türkçe

Bu repo, kulübün sahip olduğu ekipmanı, durumlarını ve hâlâ neye ihtiyacımız olduğunu takip eder.
Yılda bir kez tam envanter kontrolü yapmayı hedefliyoruz.

### Bu repo nasıl kullanılır

1. **Önce kuralları oku:** [INVENTORY_RULES.md](INVENTORY_RULES.md)
2. **Kurallara uyarak envanter kontrolünü yap.**
3. **Şablonları kopyala:** [`templates/`](templates/) klasöründen al ve doldur.
4. **Tablolarını [`docs/`](docs/) klasörüne ekle:** `YYYY-inventory.csv` ve `YYYY-shortage-list.csv` adlarıyla (örneğin `2026-inventory.csv`).
5. **Gelecek yıl için notlarını yaz:** kurallar dosyasının sonuna ya da `docs/` içine kısa bir not olarak.

### Şablonlar

| Şablon | Ne için kullanılır |
|--------|--------------------|
| [`templates/inventory-template.csv`](templates/inventory-template.csv) | Her ürünü kaydetmek için (kayıt şablonu) |
| [`templates/shortage-list-template.csv`](templates/shortage-list-template.csv) | Kulübün ihtiyaç duyduğu ama olmayan şeyler (eksik listesi) |

### Tablo sütunları

`item, quantity, condition, location, notes`

Durum şunlardan biri olmalı: `working`, `broken`, `unknown`.

Eksik listesi sütunları: `item, quantity_needed, reason`

---

## English

This repo keeps track of what our club owns, its condition, and what we still need.
We aim to do a full inventory check once a year.

### How to use this repo

1. **Read the rules first:** [INVENTORY_RULES.md](INVENTORY_RULES.md)
2. **Do the inventory check** following the rules.
3. **Copy the templates** from [`templates/`](templates/) and fill them in.
4. **Add your sheets to the [`docs/`](docs/) folder** as `YYYY-inventory.csv` and `YYYY-shortage-list.csv` (for example `2026-inventory.csv`).
5. **Write your notes for next year** at the bottom of the rules file or in a short note in `docs/`.

### Templates

| Template | Use it for |
|----------|------------|
| [`templates/inventory-template.csv`](templates/inventory-template.csv) | Recording every item (the record sheet) |
| [`templates/shortage-list-template.csv`](templates/shortage-list-template.csv) | Listing what the club needs but doesn't have |

### Sheet columns

`item, quantity, condition, location, notes`

Condition is one of: `working`, `broken`, `unknown`.

Shortage list columns: `item, quantity_needed, reason`

