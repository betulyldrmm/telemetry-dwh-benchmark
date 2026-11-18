# telemetry-dwh-benchmark

TÜBİTAK 2209-A Üniversite Öğrencileri Araştırma Projeleri Destekleme Programı kapsamında yürütülen proje.

**Proje:** Askeri Telemetri Verilerinin Analizi İçin Dağıtık Veri Ambarı Mimarisi Geliştirilmesi ve Performansının Değerlendirilmesi

Sentetik İHA/SİHA telemetri verileri üzerinde Apache Spark tabanlı yıldız şemalı veri ambarı ile PostgreSQL'in performans karşılaştırması (1M, 2M, 5M, 10M satır; 10 analitik sorgu; her koşulda 30 tekrar).

## Klasör yapısı

| Klasör | İçerik |
|---|---|
| data_gen/ | Sentetik telemetri veri üretimi |
| schema/ | Yıldız şema (olgu ve boyut tabloları) |
| etl/ | PySpark ETL/ELT hattı |
| queries/ | PostgreSQL ve Spark SQL sorguları |
| benchmark/ | Performans ölçüm scriptleri |
| analysis/ | İstatistiksel analiz ve grafikler |
| infra/ | Docker ile Spark kümesi ve PostgreSQL |
| docs/ | Deney günlüğü ve ortam bilgileri |
| results/ | Ölçüm sonuçları |

## Ekip

- Betül Yıldırım (Proje Yürütücüsü)
- Mukadder Bölükbaşı (Araştırmacı)
- Danışman: Beste Kaysı
