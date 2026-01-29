# API-Test-Automation-Postman
API Test Automation Project (Postman & Newman)
Bu proje, bir backend sisteminin API uç noktalarını (endpoints) test etmek için tasarlanmış profesyonel bir otomasyon paketidir.
🛠 Neler Yapıldı?
Full CRUD Lifecycle: GET, POST, PUT ve DELETE metodları ile uçtan uca veri döngüsü test edildi.
Schema Validation: API yanıtlarının veri tipleri (string, integer vb.) ve kontrat yapısı otomatik olarak doğrulandı.
Environment Management: Dinamik base_url kullanımı ile testler farklı ortamlara (Dev/Prod) hazır hale getirildi.
Performance Testing: Yanıt süreleri için eşik değerler belirlendi (Örn: <300ms).
Negative Testing: Hatalı isteklere karşı API'nin verdiği 404 gibi yanıt kodları doğrulandı.

💻 Nasıl Çalıştırılır?
Bu testleri terminal üzerinden çalıştırmak için aşağıdaki adımları izleyebilirsiniz:
Newman'ı yükleyin: npm install -g newman
Repodaki dosyaları kullanarak şu komutu koşturun:
newman run Portfolio_Collection.json -e My_Environment.json
<img width="1368" height="937" alt="Postman run result" src="https://github.com/user-attachments/assets/5dd1fee6-48c7-4bcc-b3e5-f4edfd173a3c" />
# Advanced API Test Automation Project (Postman & Newman)

Bu proje, bir İş Analisti ve QA Uzmanı bakış açısıyla, backend servislerinin doğruluğunu ve performansını denetlemek amacıyla geliştirilmiş kapsamlı bir test otomasyon paketidir. [cite_start]CV'mde belirttiğim "test süreçlerini optimize etme" [cite: 31, 32] [cite_start]ve "backend servislerini %100 doğrulukla denetleme" [cite: 34] hedeflerimin teknik bir uygulamasıdır.

## 🚀 Proje Kapsamı ve Teknik Özellikler

* **Uçtan Uca CRUD Döngüsü:** POST, GET, PUT ve DELETE operasyonları ile veri akışının kesintisiz olduğu doğrulanmıştır.
* **Variable Chaining (Dinamik Zincirleme):** POST isteği sonucu oluşan `id` değeri otomatik olarak yakalanıp sonraki isteklere (GET/DELETE) dinamik veri olarak aktarılmaktadır.
* [cite_start]**JSON Schema Validation:** API yanıtlarının yapısal doğruluğu, şema doğrulama testleri ile denetlenmektedir. [cite: 53, 60]
* **Dinamik Veri Üretimi:** Pre-request Script'ler kullanılarak her test çalışmasında farklı (random) test verileri üretilmektedir.
* **Performans Denetimi:** Her isteğin yanıt süresi (Response Time) kontrol edilerek belirlenen eşik değerlerin altında kalması test edilmektedir.

## 🛠️ Kullanılan Araçlar & Teknolojiler

* [cite_start]**Postman:** Test senaryolarının geliştirilmesi ve koşturulması. [cite: 14, 57]
* **JavaScript:** Dinamik scriptler ve assertion yazımı için.
* **Newman (CLI):** Testlerin terminal üzerinden çalıştırılması ve CI/CD süreçlerine hazır hale getirilmesi.
* [cite_start]**Jira & Zephyr:** Test case yönetimi ve hata takibi süreçleriyle entegre bakış açısı. [cite: 13, 15, 33, 41]

## 📊 Test Sonuçları
Proje içerisindeki testler, API kontratlarına tam uyum ve veri bütünlüğü odaklıdır. [cite_start]Yapılan testlerle hata tespit süreçleri optimize edilmiş ve sistem güvenilirliğine doğrudan katkı sağlanmıştır. [cite: 32]

---
[cite_start]**İletişim:** [ahmetbaranpolatt@gmail.com](mailto:ahmetbaranpolatt@gmail.com) [cite: 2] | [cite_start][GitHub Profilim](https://github.com/AhmetBaranPolat)
