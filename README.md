# DermaScan

Aplikasi Streamlit untuk klasifikasi lesi kulit dari foto (7 kelas HAM10000: akiec, bcc, bkl, df, mel, nv, vasc). Model: Keras, input 224×224.

> ⚠️ Hanya untuk keperluan belajar. Bukan alat diagnosis medis.

## Struktur

```
deploy/
├── app.py                  # aplikasi Streamlit
├── images/                 # gambar contoh per kelas
├── .streamlit/config.toml
└── model_deploy/
    ├── model.keras
    ├── labels.json
    └── requirements.txt
Tugas_BingungLek.ipynb      # notebook training
```

## Cara menjalankan

```bash
cd deploy
pip install -r model_deploy/requirements.txt
streamlit run app.py
```

Buka http://localhost:8501.
