# UNIEVENTNEW
unireposu

## Week 5 - AI Data Format

AI tarafından üretilecek etkinlik verileri aşağıdaki JSON formatında olmalıdır:

{
  "title": "Etkinlik adı",
  "description": "Etkinlik açıklaması",
  "university": "Üniversite adı",
  "date": "YYYY-MM-DDTHH:MM:SSZ",
  "external_allowed": true
}

Kurallar:

- title → String
- description → String
- university → String
- date → ISO tarih formatı
- external_allowed → Boolean (true veya false)

## Week 6 - Data Cleaning

AI tarafından oluşturulan veriler kontrol edildi.

Kontrol edilen koleksiyonlar:
- users
- universities
- events

Kontrol edilen noktalar:
- Türkçe karakter encoding hataları (Ã¼, ÅŸ, Ã¶ vb.)
- Metin alanlarının doğruluğu

Sonuç:
Herhangi bir bozuk karakter veya encoding hatası bulunmadı. 
Veriler UTF-8 formatında doğru şekilde saklanmaktadır.