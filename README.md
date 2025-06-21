# 🎹 Vintage VU-Meter & Mixer

Un'elegante applicazione desktop per Windows che porta il fascino dell'audio analogico sul tuo PC. Questo progetto combina un'interfaccia grafica ricca e reattiva con la cattura audio a basso livello per creare un'esperienza visiva e funzionale unica.


!(https://imgur.com/a/1C164Wh)
---

## ✨ Caratteristiche Principali

Questo non è solo un visualizzatore, ma una suite completa di strumenti audio dal design retrò:

- **Doppio VU Meter Analogico:** Due VU meter splendidamente renderizzati, con un look ambrato e retroilluminato.
- **Fisica della Lancetta Realistica:** Le lancette implementano un sistema di *ballistics* con smorzamento ed elasticità, replicando il movimento fluido e l'inerzia degli strumenti analogici reali.
- **Mixer di Volume Integrato:** Controlla il volume master del tuo sistema Windows direttamente dall'applicazione tramite un fader professionale.
- **Peak Meter a LED Verticale:** Una barra di LED a gradiente (verde-giallo-rosso) mostra i picchi di volume in tempo reale, con un LED di picco che rimane acceso per avvisare del clipping.
- **Controllo Multi-Input:** Modifica il volume con precisione trascinando il cursore con il mouse o usando la rotellina per regolazioni rapide.
- **Cattura Audio WASAPI:** Utilizza l'API moderna **WASAPI (Windows Audio Session API)** in modalità loopback per catturare l'audio del sistema in modo pulito e ad alta fedeltà.
- **Interfaccia Scalabile:** L'interfaccia è completamente ridimensionabile e mantiene le proporzioni corrette grazie a un layout dinamico.

---

## 🛠️ Stack Tecnologico

Questo progetto è stato costruito interamente in **Python**, sfruttando la potenza di diverse librerie chiave:

- **GUI:** **Tkinter** per la creazione della finestra e del canvas di disegno.
- **Audio Loopback:** **pycaw** per interfacciarsi con l'API audio a basso livello di Windows (WASAPI).
- **Calcolo Numerico:** **NumPy** per un'efficiente elaborazione del segnale audio.
- **Threading & Struttura:** L'applicazione è multithread per garantire che la cattura audio non blocchi mai la fluidità dell'interfaccia grafica.

---

## 🚀 Come Eseguire

### Eseguibile `.exe`
La via più semplice è scaricare l'ultimo eseguibile dalla sezione **[Releases]** di questo repository. Non richiede alcuna installazione. Basta un doppio clic!
