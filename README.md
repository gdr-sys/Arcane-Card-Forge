# ⚔️ Arcane Card Forge

<div align="center">

![Arcane Card Forge](https://img.shields.io/badge/D%26D-5e-red?style=for-the-badge&logo=dungeonsanddragons)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Un Card Item Builder avanzato per giochi di ruolo, ottimizzato per D&D 5e**

[🎮 Demo Live](#demo) • [✨ Funzionalità](#-funzionalità) • [🚀 Installazione](#-installazione) • [☕ Supporta il progetto](#-supporta-il-progetto)

<img src="https://raw.githubusercontent.com/noemimarcolini/arcane-card-forge/main/preview.png" alt="Arcane Card Forge Preview" width="800">

</div>

---

## 🎯 Cos'è Arcane Card Forge?

Arcane Card Forge è una **Single Page Application standalone** per creare carte oggetto professionali per D&D 5e e altri GDR. Nessuna installazione richiesta: un singolo file HTML autosufficiente con un'interfaccia **Figma-style** moderna e intuitiva.

### 🎨 Perché è diverso?

- **Zero form noiosi** — Editing visuale diretto sulla carta
- **Interfaccia Split-Screen** — Pannello controlli + Canvas live preview
- **Stampa professionale** — Layout PDF fronte/retro con calibrazione millimetrica
- **100% Offline** — Funziona senza internet dopo il primo caricamento

---

## ✨ Funzionalità

### 🃏 Creazione Carte

| Funzionalità | Descrizione |
|--------------|-------------|
| **Dimensioni Standard** | 2.5 × 3.5 pollici (63.5 × 88.9 mm) - formato TCG |
| **Inline Editing** | Clicca e modifica direttamente sulla carta |
| **Rarità D&D 5e** | Common → Artifact con colori e stili dedicati |
| **Statistiche Dinamiche** | Aggiungi, rimuovi, rinomina qualsiasi campo |
| **Dice Tags** | Scrivi `[2d6+3]` per evidenziare automaticamente |

### 🖼️ Sistema Immagini Avanzato

- **Drag & Drop** per caricare immagini locali
- **URL remoti** per immagini web
- **Galleria preset** con silhouette fantasy
- **Pan & Zoom** — Trascina per spostare, scroll per zoomare (20%-250%)
- **Posizionamento salvato** per ogni carta

### 🎴 Personalizzazione Retro

| Modalità | Descrizione |
|----------|-------------|
| **Lore/Storia** | Testo corsivo stile diario delle avventure |
| **Pattern/Texture** | 9 pattern geometrici (Celtic, Diamond, Runes, Scales...) |
| **Immagine Custom** | La tua immagine con overlay pattern opzionale |

### 🎨 Stili Grafici

- **8 Gradient Preset** — Night Ocean, Ember Glow, Arcane Purple...
- **3 Font Preset** — Classico, Moderno, Gotico
- **Colori personalizzabili** — Testo, sfondo, bordi
- **4 Stili bordo** — Solid, Double, Groove, Ridge
- **16 Emblemi centrali** per il retro

### 📋 Template Rapidi D&D 5e

8 template preimpostati pronti all'uso:
- Pozione di Cura, Spada Lunga +1, Armatura di Mithral
- Anello di Protezione, Bacchetta di Palle di Fuoco
- Mantello dell'Invisibilità, Spada Vorpal, Sfera di Annientamento

### 🖨️ Sistema Stampa Professionale

- **Griglia 3×3** su foglio A4
- **Logica specchio** — I retri si allineano automaticamente ai fronti
- **Calibrazione millimetrica** — Offset X/Y per compensare errori stampante
- **Selezione multipla** — Stampa solo le carte che vuoi

### 🌍 Accessibilità

- **Italiano / English** — Toggle istantaneo
- **Dark / Light Mode** — Tema scuro profondo per sessioni notturne
- **Shortcuts tastiera** — Ctrl+N, Ctrl+S, Ctrl+P

---

## 🚀 Installazione

### Opzione 1: Download diretto
```bash
# Clona il repository
git clone https://github.com/noemimarcolini/arcane-card-forge.git

# Apri index.html nel browser
open index.html
```

### Opzione 2: Usa direttamente
Scarica `index.html` e aprilo con qualsiasi browser moderno. **Fatto!**

### Requisiti
- Browser moderno (Chrome, Firefox, Edge, Safari)
- Nessun server richiesto
- Funziona offline

---

## 📖 Guida Rapida

### Creare una carta

1. **Clicca sul nome** nella carta per modificarlo
2. **Seleziona categoria e rarità** dal pannello Layout
3. **Clicca sull'area immagine** per aggiungere un'immagine
4. **Trascina l'immagine** per posizionarla, **scroll** per zoomare
5. **Modifica le statistiche** cliccando direttamente sui valori
6. **Aggiungi proprietà** dal tab Custom (es: Finesse, Light)

### Personalizzare il retro

1. Vai al tab **Retro**
2. Scegli modalità: **Lore**, **Pattern** o **Immagine**
3. Per Pattern: scegli tipo, colore, opacità, emblema centrale
4. Per Immagine: carica la tua, attiva overlay pattern se vuoi

### Stampare le carte

1. Seleziona le carte con le **checkbox** nel vassoio in basso
2. Vai al tab **Stampa**
3. Imposta **calibrazione** se necessario (offset X/Y in mm)
4. Clicca **Stampa Fronte/Retro**
5. Stampa la prima pagina, gira il foglio, stampa la seconda

### Scorciatoie tastiera

| Shortcut | Azione |
|----------|--------|
| `Ctrl + N` | Nuova carta |
| `Ctrl + S` | Salva |
| `Ctrl + P` | Stampa |

---

## 💾 Salvataggio e Export

- **Auto-save** — Le carte si salvano in localStorage automaticamente
- **Export JSON** — Scarica tutte le carte come file `.json`
- **Import JSON** — Carica carte da file `.json`
- **Condivisione** — Invia il file JSON ai tuoi amici DM!

---

## ☕ Supporta il progetto

Se Arcane Card Forge ti è utile per le tue sessioni di gioco, considera di supportare lo sviluppo!

<a href="https://ko-fi.com/noemimarcolini" target="_blank">
  <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Supporta su Ko-fi">
</a>

---

## 📜 Licenza

Questo progetto è rilasciato sotto licenza **MIT**. Vedi [LICENSE](LICENSE) per i dettagli.

---

<div align="center">

**⚔️ Che le tue carte siano sempre leggendarie! ⚔️**

</div>
