# 💊 Convertitore Vitamina D3

Una webapp moderna e intuitiva per la conversione tra diverse formulazioni di vitamina D3, pensata per medici e professionisti sanitari.

![Versione](https://img.shields.io/badge/versione-1.0-blue)
![Licenza](https://img.shields.io/badge/licenza-MIT-green)

## 📋 Descrizione

Questo strumento consente di convertire facilmente tra:
- Gocce di vitamina D3 (250 UI per goccia)
- Preparazioni fisse (25.000 e 50.000 UI)
- Dosaggi giornalieri, settimanali e mensili

Ideale per calcolare rapidamente le equivalenze tra diverse formulazioni e facilitare la prescrizione e il counseling ai pazienti.

## ✨ Funzionalità

### 🔄 Conversioni disponibili

1. **Da Gocce a Unità Internazionali**
   - Converte il numero di gocce in UI
   - Calcola automaticamente la dose mensile (×30 giorni)
   - Mostra l'equivalenza con le fiale standard

2. **Da Unità Internazionali a Gocce**
   - Converte UI in numero di gocce
   - Gestisce arrotondamenti automatici per valori non esatti

3. **Da Dose Mensile a Gocce Giornaliere**
   - Converte la dose mensile prescritta in gocce giornaliere
   - Mostra anche l'equivalente settimanale
   - Calcola la dose effettiva considerando gli arrotondamenti

4. **Da Gocce Settimanali a Dose Mensile**
   - Converte una posologia settimanale in dose mensile
   - Mostra l'equivalenza giornaliera
   - Utile per schemi posologici settimanali

5. **Conversioni Rapide**
   - Visualizzazione immediata delle equivalenze per fiale standard:
     - 25.000 UI = 100 gocce
     - 50.000 UI = 200 gocce

6. **Guida Dosaggi**
   - Riferimenti rapidi per dosaggi comuni
   - Equivalenze pre-calcolate

## 🚀 Utilizzo

### Apertura diretta
Basta aprire il file `vitamina-d3-converter.html` in qualsiasi browser moderno. Non richiede installazione o connessione internet.

### Hosting locale
```bash
# Con Python 3
python -m http.server 8000

# Con PHP
php -S localhost:8000

# Poi apri http://localhost:8000/vitamina-d3-converter.html
```

### GitHub Pages
1. Fai il fork di questo repository
2. Vai su Settings → Pages
3. Seleziona il branch main come source
4. L'app sarà disponibile su `https://tuousername.github.io/vitamina-d3-converter/`

## 💻 Tecnologie

- **HTML5** - Struttura
- **CSS3** - Stile e animazioni
- **JavaScript Vanilla** - Logica di conversione
- **Design Responsive** - Ottimizzato per desktop, tablet e smartphone

## 📱 Compatibilità

✅ Chrome/Edge (versione 90+)  
✅ Firefox (versione 88+)  
✅ Safari (versione 14+)  
✅ iOS Safari  
✅ Chrome Mobile  

## 🎨 Caratteristiche del Design

- Interface pulita e moderna con gradiente viola
- Animazioni fluide e feedback visivi
- Completamente responsive (mobile-first)
- Box risultati ben evidenziati con colori distinti
- Ottimizzato per macOS e iOS

## 📐 Calcoli e Approssimazioni

- **1 goccia = 250 UI** (valore standard per preparazioni in gocce)
- **Mese = 30 giorni** (per calcoli di dose mensile)
- **Settimana = 7 giorni**
- **Conversione settimanale-mensile**: utilizza il rapporto 30/7 (≈4,3 settimane al mese)

## 🔒 Privacy e Sicurezza

- ✅ Funziona completamente offline
- ✅ Nessun dato viene inviato a server esterni
- ✅ Nessun cookie o tracking
- ✅ Nessuna raccolta di dati personali

## 📝 Note per l'uso clinico

Questo strumento è pensato come supporto al calcolo e alla conversione delle dosi di vitamina D3. Le decisioni cliniche devono sempre basarsi sul giudizio professionale del medico, tenendo conto di:
- Storia clinica del paziente
- Livelli sierici di 25-OH vitamina D
- Fattori di rischio individuali
- Linee guida cliniche aggiornate

## 🤝 Contribuire

I contributi sono benvenuti! Per favore:

1. Fai il fork del progetto
2. Crea un branch per la tua feature (`git checkout -b feature/AmazingFeature`)
3. Committa le modifiche (`git commit -m 'Add some AmazingFeature'`)
4. Pusha il branch (`git push origin feature/AmazingFeature`)
5. Apri una Pull Request

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT. Vedi il file `LICENSE` per maggiori dettagli.

## 👨‍⚕️ Autore

**Dott. Gianmario Corbani**  
Medico di Medicina Generale

## 🐛 Segnalazione Bug

Per segnalare bug o richiedere nuove funzionalità, apri una [Issue](../../issues) su GitHub.

## 📚 Riferimenti

- Preparazioni standard di vitamina D3 in commercio in Italia
- Linee guida AIFA per la supplementazione di vitamina D
- Standard internazionali per le Unità Internazionali (UI)

## 🔄 Changelog

### Versione 1.0 (Novembre 2024)
- ✨ Release iniziale
- ✨ Conversione gocce ↔ UI
- ✨ Conversione dose mensile → gocce giornaliere
- ✨ Conversione gocce settimanali → dose mensile
- ✨ Conversioni rapide per fiale standard
- ✨ Guida dosaggi comuni
- ✨ Design responsive e moderno

---

⭐️ Se trovi utile questo strumento, considera di lasciare una stella su GitHub!
