# Deep Learning – Fashion MNIST Regularisering

Detta projekt undersöker hur olika regulariseringstekniker påverkar en CNN-modells förmåga att generalisera till ny data.

Projektet genomfördes inom kursen Deep Learning och använder datasetet Fashion MNIST från Keras.

---

# Projektets syfte

Målet med projektet var att:
- bygga en baseline-modell
- testa olika regulariseringstekniker
- analysera overfitting och underfitting
- jämföra modellernas resultat

---

# Dataset

Fashion MNIST består av:
- 70 000 svartvita bilder
- 10 olika klasser av kläder och skor
- bildstorlek 28x28 pixlar

Datasetet delades upp i:
- träningsdata
- validation-data
- testdata

---

# Modeller och regularisering

Projektet testade:
- Baseline-modell
- Dropout 0.2
- Dropout 0.5
- Early stopping
- L2-regularisering
- L1 + L2-regularisering

Vi såg att regularisering generellt förbättrade modellernas generalisering och minskade risken för overfitting.

Dropout 0.2 gav bäst resultat i vår körning.

Vi upptäckte även att för stark L1 + L2-regularisering gav tydlig underfitting och mycket låg accuracy. Efter att regulariseringsvärdena sänktes förbättrades resultaten tydligt.

---

# Resultat

Modellerna jämfördes med:
- accuracy
- loss
- confusion matrix
- classification report
- träningskurvor

Confusion matrixen visade att vissa klasser, exempelvis Shirt och T-shirt/top, oftare blandades ihop eftersom de visuellt liknar varandra.

---

# Teknologier och bibliotek

Projektet använder:
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

# Arbetsfördelning

Projektet genomfördes av:
- Henrik Andersson
- Marcus Bäckström
- Carina Karlsson

Allt arbete genomfördes gemensamt under projektets gång.

Henrik delade skärm under arbetets gång och gruppen skrev, testade och analyserade koden tillsammans.

---
