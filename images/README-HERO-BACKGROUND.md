# Guida per l'Immagine di Sfondo della Hero Section

## 📐 Specifiche Tecniche Ottimali

### Formato e Dimensioni

**Desktop:**
- **Risoluzione consigliata**: 1920x1080px (16:9) o 1920x800px
- **Formato**: JPG (per foto) o WebP (migliore compressione)
- **Peso file**: < 200KB (ottimizzato)
- **Qualità**: 80-85% per JPG

**Mobile:**
- L'immagine si adatta automaticamente grazie al CSS responsive
- Il CSS usa `background-attachment: scroll` su mobile per prestazioni ottimali
- L'overlay semi-trasparente garantisce leggibilità del testo

### Nome File
Salvare l'immagine come:
```
hero-bg.jpg
```
Oppure:
```
hero-bg.webp
```

### Posizione
Inserire il file nella cartella:
```
C:/progetti/MetodiPro.github.io/images/
```

## 🎨 Suggerimenti per la Scelta dell'Immagine

### Stile Consigliato
- Immagine professionale e moderna
- Evitare troppi dettagli piccoli (potrebbero confondere con il testo)
- Colori che si abbinano al rosso (#dc2626) del brand
- Tonalità neutre o con overlay grigio/bianco

### Contenuto Suggerito
- Ambiente ufficio moderno
- Tecnologia/computer/coding
- Pattern geometrici astratti
- Grafici/dati stilizzati
- Skyline cittadino moderno

### Cosa Evitare
- Immagini troppo luminose (il testo potrebbe non essere leggibile)
- Troppi colori contrastanti
- Immagini con troppi piccoli dettagli
- File troppo pesanti (rallentano il caricamento)

## 🔧 Ottimizzazione dell'Immagine

### Strumenti Online Consigliati
1. **TinyPNG** (tinypng.com) - Compressione JPG/PNG
2. **Squoosh** (squoosh.app) - Conversione WebP
3. **Compressor.io** - Ottimizzazione multi-formato

### Processo di Ottimizzazione
1. Ridimensiona a 1920px di larghezza
2. Comprimi con qualità 80-85%
3. Converti in WebP (opzionale, migliore compressione)
4. Verifica che il peso sia < 200KB

## 📝 Modifica CSS (se necessario)

Se vuoi modificare l'opacità dell'overlay, modifica nel file `css/style.css`:

```css
.hero::before {
    background: rgba(229, 231, 235, 0.85); /* Cambia 0.85 per più/meno opacità */
}
```

- **0.90** = Overlay più opaco (testo più leggibile, immagine meno visibile)
- **0.80** = Overlay più trasparente (immagine più visibile)

## ✅ Checklist Finale

- [ ] Immagine dimensionata a 1920x1080px o 1920x800px
- [ ] Formato JPG o WebP
- [ ] Peso file < 200KB
- [ ] Nome file: `hero-bg.jpg` o `hero-bg.webp`
- [ ] File salvato in `/images/`
- [ ] Testato su desktop e mobile
- [ ] Testo della hero ben leggibile

## 🎯 Risultato Atteso

Con l'immagine correttamente posizionata, la hero section avrà:
- Sfondo visivo professionale e coinvolgente
- Testo perfettamente leggibile grazie all'overlay
- Caricamento veloce
- Ottima visualizzazione su tutti i dispositivi
