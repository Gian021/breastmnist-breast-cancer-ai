# 🔬 BreastMNIST AI Classifier

Un modello di Deep Learning in **PyTorch** per la classificazione automatizzata di lesioni mammarie (benigne vs. maligne) utilizzando il dataset benchmark **BreastMNIST (MedMNIST)**.

---

## 📌 Contenuto della Repository

- `breastmnist_classification.ipynb`: Notebook Jupyter con la pipeline completa (Data Loading, Preprocessing, Architettura CNN, Training Loop e Valutazione delle metriche diagnostiche).
- `README.md`: Documentazione tecnica e clinica del progetto.

---

## 🎯 Obiettivi Clinici & Ingegneristici

- **Dataset:** BreastMNIST ($28 \times 28$ pixel, ecografie/mammografie).
- **Architettura:** Rete Neurale Convoluzionale (CNN) con strati di Batch Normalization e Dropout per prevenire l'overfitting.
- **Focus diagnostico:** Massimizzazione del punteggio **ROC-AUC** e della sensitività (Recall) per ridurre al minimo i falsi negativi, parametro critico nello screening oncologico del tumore al seno.

---

## 📊 Risultati Ottenuti

- **Accuracy su Test Set:** ~83-85%
- **ROC-AUC Score:** ~0.88+

---

🛠️ **Tech Stack:** Python, PyTorch, MedMNIST, Scikit-Learn, Matplotlib, NumPy.
