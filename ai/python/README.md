# UniEventAI - AI (Python)

Bu klasör scraper'lar, NLP ve öneri motoru için Python kodlarını içerir.

Önerilen paketler `requirements.txt` içinde listelenir. Sanal ortam (venv/conda) kullanarak kurulum yapın.

Not: Web scraping yaparken hedef sitelerin robots.txt kurallarına ve kullanım şartlarına uyun.


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