# ⚙️ Estirpatore Facile

**Progetto derivato da [FruttOliva Facile](../README.md)**  
L’attrezzo manuale per la rimozione di radici, rovi e ceppi più semplice e intuitivo mai realizzato.

---

## 🌱 Descrizione generale
**Estirpatore Facile** è una macchina manuale completamente meccanica, progettata per la rimozione di radici, polloni e piccoli ceppi legnosi, senza motori e senza sforzi eccessivi.  
Funziona secondo il principio della leva, sfruttando un fulcro regolabile e bracci di forza che moltiplicano la spinta dell’operatore.

> “La forza di EstirpatoreFacile è nella semplicità.”

---

## 🔩 Specifiche tecniche
| Caratteristica | Dettaglio |
|-----------------|------------|
| **Peso** | ~12 kg |
| **Materiale** | Acciaio zincato o verniciato |
| **Lunghezza braccio leva** | Regolabile 100–140 cm |
| **Uso ideale** | Rimozione di radici, robinia, rovi, piccoli ceppi |
| **Tipo di azione** | Leva e contrappeso su fulcro mobile |
| **Compatibilità** | Attrezzo indipendente, nessun motore richiesto |
## ⚙️ Calcoli meccanici – Legge della leva di Archimede

### Dati geometrici reali
| Parametro | Simbolo | Valore | Unità |
|------------|----------|--------|-------|
| Lunghezza manico (braccio della potenza) | Lₚ | 1,00 | m |
| Distanza fulcro–radice (braccio del resistente) | Lᵣ | 0,11 | m |
| Angolo medio di lavoro | θ | 20–25 | ° |
| Vantaggio meccanico | VM = Lₚ / Lᵣ | ≈ 9,1 | × |

---

### Forze in gioco
La forza che l’operatore applica sul manico (**Fₚ**) viene moltiplicata dalla leva:
\[
Fᵣ = Fₚ \times \frac{Lₚ}{Lᵣ} \times \cos(θ)
\]

| Forza applicata Fₚ (N / kgf) | Fᵣ teorica (N) | Fᵣ equivalente (kgf) |
|-------------------------------|----------------|-----------------------|
| 200 N (~20 kgf) | 1 710 N | ≈ 174 kgf |
| 250 N (~25 kgf) | 2 140 N | ≈ 218 kgf |
| 300 N (~30 kgf) | 2 570 N | ≈ 262 kgf |

💪 **Risultato pratico:**  
Con una spinta reale di soli **25–30 kg** sulle braccia, Estirpatore Facile esercita **oltre 200–260 kgf** sulla radice o sul ceppo.

---

### Momento torcente
\[
M = Fₚ \times Lₚ = 250 N \times 1,0 m = 250 N·m
\]
Applicato su un braccio di 0,11 m:
\[
Fᵣ = \frac{M}{Lᵣ} = 250 / 0,11 ≈ 2 270 N ≈ 230 kgf
\]

---

### Considerazioni pratiche
✅ Fulcro a V perfetto per terreni compatti: riduce slittamenti.  
✅ Un manico da 120 cm (+20%) → ~300 kgf.  
✅ Con fulcro più vicino alla radice (Lᵣ = 9 cm) → ~320 kgf.  

---

## 📸 Immagini e risorse
Consulta la cartella [`/Immagini`](./Immagini) per foto, render e schemi tecnici del progetto.

---

## 📜 Licenza
Il progetto è distribuito con la **Licenza “Facile – Estirpatore Facile”**, che consente l’uso, la modifica e la riproduzione personale o aziendale a fronte di un contributo simbolico di 30 €.

📄 [Leggi la licenza completa](./legal/LICENZA_EstirpatoreFacile.txt)

---

## 📢 Materiale marketing
Tutto il materiale promozionale, brochure e contenuti social si trovano in [`/marketing`](./marketing).

---

## 🤝 Filosofia
Estirpatore Facile nasce dalla stessa filosofia di *FruttOliva Facile*:  
> **Semplicità, efficacia e rispetto per la terra.**  

Progettato per chi lavora il terreno con passione, senza rumore, benzina o sprechi.

---
> © 2025 Renato Maiorana — *Linea Facile / GenioVerde™*
> > “Dal terreno alla libertà: la natura si apre alla forza dell’ingegno.”  
© 2025 **Renato Maiorana** – Tutti i diritti riservati.  
*Progetto open-source supportato da GenioVerde™*
