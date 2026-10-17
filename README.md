# Türkiye Katmanları
GitHub Pages'e olduğu gibi yükleyin (yerelde açmak için `python3 -m http.server`).
- data/index.json: veri olan iller ve yer sayıları
- data/<plaka>.json: ilin ilçeleri, ilçe harita dizilimi, ilçe başına yer sayısı
- data/<plaka>/<ilçe>.json: ilçenin yerleri (site yalnızca seçilen ilçeyi yükler)
Yeni il eklemek için bu üç dosya türü yeterlidir; kod değişmez.
