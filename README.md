# 🚗 Modellazione 3D di un'Auto in Blender

(Questo progetto è stato realizzato1-per l'esame di computer grafica, 2-per esercitarmi nella modellazione 3D con Blender.) L'obiettivo era creare un modello realistico di un’auto, partendo da zero, utilizzando immagini di riferimento e diversi strumenti e tecniche offerte dal software.


## 🛠️ Fasi del lavoro(Puoi trovare ulteriori dettagli all'interno dei file presenti nel repository).

### 1. **Modellazione base**
- Ho aggiunto un *plane* e fuso i vertici centrali (`M → Merge`).
- Ho estruso (`E`) i punti seguendo la forma dell'auto, creando le prime facce.
- Con `G` ho posizionato manualmente i vertici per formare la carrozzeria.

### 2. **Aggiunta dettagli**
- Ho usato `Ctrl + R` (*Loop Cut*) per inserire tagli e rifinire il modello.
- Ho usato `K` (*Knife Tool*) per dettagli personalizzati.
- Con `Ctrl + B` (*Bevel*) ho aggiunto smussature.
- Ho scalato i vertici su assi specifici (`S Z 0`, `S Y 0`) per allinearli.

### 3. **Aperture e profondità**
- Ho eliminato le facce delle ruote (`X`) e usato `E + S` per dare profondità.
- Per i fari, ho usato `I` (*Inset*) e poi `Ctrl + F → Extrude Faces Along Normals`.

### 4. **Mirror e Solidify**
- Ho applicato un *Mirror Modifier* per ottenere la simmetria.
- Con il *Solidify Modifier* ho dato spessore al modello.

### 5. **Tetto e superfici**
- Ho suddiviso il tetto in sezioni per lavorare meglio.
- Usato `Numpad /` per isolare le parti selezionate.

### 6. Creazione degli specchi 
- Inserito un *plane*, trasformato in una curva con `Shift + Ctrl + B` e *LoopTools*.
- Convertito in mesh, poi usato `Subdivision Surface Modifier` (`Ctrl + 1`).
- Unito oggetti e applicato nuovamente il *Mirror Modifier*.

### 7. **Ruote**
- Aggiunto un cilindro, ruotato e scalato per adattarlo al corpo del veicolo.

### 8. **Texturing**


## 📁 File inclusi
- `.blend` file del progetto
- Immagini del progetto
- Screenshot dei progressi


## 📌 Note
- Tutto il lavoro è stato fatto manualmente, passo dopo passo.
- L’obiettivo principale era apprendere le basi della modellazione 3D in Blender.

## 📷 Anteprima

![6](https://github.com/user-attachments/assets/edab312f-979b-4436-8c8e-17c7637d6bb7)


---

## ✅ Conclusione

Questo progetto mi ha aiutato a migliorare le mie abilità in Blender, dalla modellazione base fino al texturing. 

## 👨‍💻 Autore

Mohammed ASSlaoui

