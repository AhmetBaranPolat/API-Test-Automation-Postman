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
