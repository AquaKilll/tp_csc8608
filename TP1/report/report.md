Lien dépot GITHUB : https://github.com/AquaKilll/tp_csc8608

Environnement : Nœud GPU via SLURM

TP1/
├── data/
│   └── images/          # Images sources pour la segmentation
├── outputs/             # Résultats générés (non versionnés)
│   ├── logs/
│   └── overlays/
├── report/              # Documentation du TP
├── src/                 # Code source
│   ├── app.py           # Application principale (Gradio/Streamlit)
│   ├── geom_utils.py    # Calculs métriques (aires, périmètres)
│   ├── sam_utils.py     # Wrapper pour le modèle SAM
│   └── viz_utils.py     # Outils de visualisation
└── requirements.txt

