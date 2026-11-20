# Trip The Loop — Into The Wild (GitHub Pages Project)

Had l-machrou3 mnaḍḍem f-milaffat mfarqa bach tqdar trfa3o b-sohola 3la **GitHub** o tkhdem b-**GitHub Pages** bla hta mochkil.

## 📂 Binyat l-Machrou3 (Project Structure)

```text
trip-the-loop/
├── index.html          # L-wajiha r-ra2issiya (fiha jami3 l-aqssam: Home, Destinations, About, Trips, Blog, Shop, Contact + Admin Panel)
├── css/
│   └── styles.css      # Jami3 t-tansiqat o l-alwan (Forest Green & Lime)
├── js/
│   ├── data.js         # L-bayanat l-iftiradiya (Rihlat, Wijhat, Maqalat, Matjar, Tarjamat AR/FR/EN)
│   ├── app.js          # T-tanaqqol bin l-aqssam, l-falatra, l-modal, o l-hajz 3abr WhatsApp
│   └── cms.js          # Lawhat t-tahakkom (Admin Panel) + r-rabt m3a Firebase o data/site-data.json
├── data/
│   └── site-data.json  # Milaf JSON l-khariji li katjib mno GitHub Pages l-bayanat l-mohaddatha
└── .nojekyll           # Kaykhalli GitHub Pages y-qra jami3 l-milaffat mobachara bla ta3qidat
```

## 🚀 Kifach trfa3 l-machrou3 l-GitHub:
1. Fakk d-daght 3la milaf `trip-the-loop-github-project.zip`.
2. Dkhol l-Repository dyalk f-**GitHub**, w-rfa3 jami3 had l-milaffat o l-mojalladat (`index.html`, `css/`, `js/`, `data/`, `.nojekyll`) f-nafs t-tartib.
3. Sir l-**Settings -> Pages** f-GitHub, khtar `main` branch o `/(root)` folder, w-dghet **Save**.

## 🔄 Kifach t-haddeth l-mahtawa bla ma t-qiss l-code:
* **Tariqa 1 (T-tahdith l-fawri 3abr Firebase):** Fteh lohat t-tahakkom (fl-asfal dyal l-mawqi3, l-kalma s-sirriya l-iftiradiya: `loop2026`), ddir t-ta3dilat dyalk, w-dghet 3la **ربط ورفع البيانات للسحابة** f-tabwib **الإعدادات والسحابة**.
* **Tariqa 2 (3abr GitHub mobachara):** Ba3d ma t-kammel t-ta3dilat f-lohat t-tahakkom, dghet 3la **⬇ تصدير JSON** bach y-t-hammel milaf `site-data.json`, w-baddel bih l-milaf li dakhil mojallad `data/site-data.json` f-GitHub.
