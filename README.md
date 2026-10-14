# Couleurs_TIM

Projet autour du traitement et de l’analyse des couleurs (TIM). Ce projet s'intéresse à la segmentation d'images couleur par l'algorithme SLIC.

---

## Installation / Environnement Python

Le fichier `Pipfile` suivant est **suffisant pour exécuter les notebooks** du projet:

### Pipfile

```toml
[[source]]
url = "https://pypi.org/simple"
verify_ssl = true
name = "pypi"

[packages]
numpy = "*"
opencv-python = "*"
notebook = "*"
pandas = "*"
matplotlib = "*"
scipy = "*"
scikit-learn = "*"
ipykernel = "*"
scikit-image = "*"

[dev-packages]

[requires]
python_version = "3.12"
