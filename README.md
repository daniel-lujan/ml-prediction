# Proyecto I.A.

[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/) [![Kaggle](https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white)](https://www.kaggle.com/competitions/home-credit-default-risk)

> [!IMPORTANT]
> Esto es un repositorio con fines académicos

Miembros del equipo:

- **Daniel Lujan Agudelo** (C.C. 1035970328): Ingeniería de Sistemas Presencial
- **Santiago Rivera Montoya** (C.C. 1000654685): Ingeniería de Sistemas Presencial
- **Emanuel López Higuita** (C.C. 1000662113): Ingeniería de Sistemas Presencial

# Datos

Los datos provienen de la competencia de Kaggle [Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk).

Puede montar el dataset a cualquier Notebook de Colab de la siguiente manera:

Primero debes subir tu clave `kaggle.json`.

> [!NOTE]
> Si no tienes uno, revisa la sección **Authorization** en [Kaggle Public API](https://www.kaggle.com/docs/api).

```python
from google.colab import files
files.upload()
```

Para descargar el dataset:

```bash
!mkdir ~/.kaggle
!mv ./kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
!kaggle competitions download -c home-credit-default-risk
```

# Videos

- [Video segunda entrega](https://youtu.be/LL3NO8VgRFs)
- [Video entrega final](https://www.youtube.com/watch?v=QxVvctfkMxY)
