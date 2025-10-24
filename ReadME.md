# Amplificator Audio Multietaj – Proiect CAD

Acest proiect reprezintă proiectul CAD realizat de **Mihuț Darius Daniel** în cadrul **Universității Tehnice din Cluj-Napoca**, Facultatea de Electronică, Telecomunicații și Tehnologia Informației.

## 📘 Descriere generală
Scopul proiectului este realizarea unui **amplificator audio multietaj**, capabil să amplifice un semnal de intrare de 900 μV până la o tensiune de ieșire reglabilă între **±3 V și ±13 V**, pentru o **sarcină de 9 Ω** și o **bandă de frecvență de 210–9000 Hz**.

## ⚙️ Structura circuitului
Circuitul este alcătuit din următoarele etaje funcționale:
1. **Filtru trece-bandă activ** – selectează frecvențele între 210 Hz și 9000 Hz.  
2. **Două etaje de amplificare fixe** – amplifică semnalul filtrat în mod controlat.  
3. **Etaj cu amplificare reglabilă (SET)** – permite ajustarea tensiunii de ieșire între ±3 V și ±13 V.  
4. **Etaj tampon (buffer)** – izolează etajele și asigură adaptare de impedanță.  
5. **Etaj de putere** – livrează semnalul către sarcina de 9 Ω, utilizând o configurație push-pull cu tranzistoare TIP41C/TIP42C.

## 🔬 Simulări efectuate
Proiectul include analize și simulări realizate în software CAD:
- **AC Sweep** – răspunsul în frecvență al circuitului;
- **Time Domain** – forma de undă a semnalului în timp;
- **Monte Carlo** – verificarea toleranțelor componentelor;
- **FFT** – analiza spectrală a semnalului;
- **Parametric Sweep** – variația în funcție de rezistența de reglaj;
- **Temperature Sweep** – stabilitatea termică a circuitului.

## 📈 Rezultate
- Banda de trecere: 210 Hz – 9000 Hz  
- Amplificare reglabilă: ±3 V – ±13 V  
- Fără distorsiuni vizibile în domeniul de funcționare  
- Comportament stabil la variații de temperatură

## 🧰 Componente utilizate
- Amplificatoare operaționale: **TL072**, **AD822**  
- Tranzistoare de putere: **TIP41C**, **TIP42C**  
- Diode de polarizare: **1N4148**  
- Sursă de alimentare: **±15 V**

## 📂 Fișiere disponibile
- `CAD-MIHUT-DARIUS-DANIEL.docx` – documentul complet al proiectului  
 
 
 

## 🧑‍🎓 Autor
**Mihuț Darius Daniel**  
Grupa 2126 – Universitatea Tehnică din Cluj-Napoca  
Coordonator: *asist. drd. ing. Elena Ștețco*
