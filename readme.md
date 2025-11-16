Proje Klasör Yapısı
root/
├─ index.html           # Ana HTML dosyası
├─ index.css            # Genel stil dosyası
├─ Image/
│  ├─ Index.png
├─ components/
│  ├─ card/
│  │  ├─ card.js
│  │  └─ card.css
│  ├─ iconButton/
│  │  ├─ iconButton.js
│  │  └─ iconButton.css
│  ├─ menu/
│  │  ├─ menu.js
│  │  └─ menu.css
│  └─ haber/
│     ├─ haberler.js
│     └─ haberler.css
└─ package.json
📝 Açıklama
Projedeki tüm bileşenler JavaScript (vanilla JS) ile yazılmıştır. Bileşenler document.createElement, appendChild, classList.add, setAttribute gibi temel DOM yöntemleri kullanılarak oluşturulmuştur.

Bu ödevde amaç;

HTML etiketlerini JavaScript ile dinamik üretmek,
Parametreli fonksiyonlarla yeniden kullanılabilir bileşenler yapmak,
CSS ile her bileşeni bağımsız bir şekilde stillendirmek,
DOM API’sini kullanarak veri tabanlı içerikler oluşturmayı öğrenmektir.

