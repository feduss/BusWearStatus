# BusWearStatus

| Città / City      | Lista Linee / Lines list | Lista Direzioni / Directions list | Lista Fermate / Stops list | Orari programmati / Scheduled times  | Orari in tempo reale / Realtime times  | Feed RSS Avvisi / Feed RSS Alerts              |
|---------------------|----|-----|----|----|----|----|
| Bologna Urbano      | ✅ | ✅ | ✅ | 🟡 |    | 
| Cagliari Urbano     | ✅ | ✅ | ✅ | ✅ | 🚫 | ✅
| Catania Urbano      | ✅ | ✅ | ✅ | 🟡 |    |
| Firenze Urbano      | ✅ | ✅ | ✅ | 🟡 |    |
| Firenze GEST        | ✅ | ✅ | ✅ | 🟡 |    |
| Genova Urbano       | ✅ | ✅ | ✅ | ⚠️ |    |
| Milano Urbano       | ✅ | ✅ | ✅ | 🟡 |    |
| Napoli Urbano       | ✅ | ✅ | ✅ | 🟡 |    |
| Palermo Urbano      | ✅ | ✅ | ✅ | 🟡 |    |
| Roma Urbano         | ✅ | ✅ | ✅ | 🟡 | 🛠️ |
| Slovakia Train Zssk | ✅ | ✅ | ✅ | ✅ | 🚫 | 
| Torino Urbano       | ✅ | ✅ | ✅ | 🟡 |    |
| Trento Urbano       | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫

✅ = OK, testato da utenti reali / OK, tested but real users

🟡 = OK ma richiede più test da utenti reali (alcuni casi non funzionano oppure è corretto che non ci siano dati) / OK but it requires more test by real users (some cases doesn't work or maybe it's correct to not have datas)

⚠️ = Problema con la mia personale interpretazione dei dati o Problema con i dati GTFS della società di trasporti / Issue with my personal interpretation of data or issue with company site

🚫 = Non disponibile nel sito della società di trasporti / Not available on company's site

Note:

- Genova: il file calendar.txt contiene un range temporale errato (gennaio 2024, ma siamo ad ottobre). Questo è un problema per il calcolo della validità degli orari
