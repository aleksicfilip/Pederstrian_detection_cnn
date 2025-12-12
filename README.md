# Pedestrian Detection CNN

Ovaj projekt se bavi detekcijom pješaka koristeći konvolucijske neuronske mreže (CNN).

## Struktura Projekta

```text
pedestrian-detection-cnn/
├── data/               <-- Podaci (ignorirani u gitu)
│   ├── raw/            <-- Originalni skinuti podaci
│   └── processed/      <-- Obrađeni podaci
├── notebooks/          <-- Jupyter bilježnice
├── src/                <-- Izvorni kod
├── requirements.txt    <-- Popis biblioteka
└── README.md           <-- Ovaj dokument
```

## Postavljanje Okoline (Setup)

1.  **Kreiraj virtualno okruženje:**
    ```powershell
    python -m venv venv
    .\venv\Scripts\Activate.ps1
    ```

2.  **Instaliraj biblioteke:**
    ```powershell
    pip install -r requirements.txt
    ```

## Podaci (Data)

### Kako skinuti podatke:

### Datasetovi:
*   **Penn-Fudan Database:** Mali dataset za testiranje pipelinea.
*   **INRIA Person Dataset:** Veći dataset za treniranje.
*   **Caltech Pedestrian:** (Opcionalno) Za ovaj dataset preporučujemo ručno skidanje konvertirane verzije s Kaggle-a i raspakiravanje u `data/raw/Caltech`.