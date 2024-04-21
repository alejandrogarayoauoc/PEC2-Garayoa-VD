# PEC 2-Visualización de datos
Trabajo realizado por Alejandro Garayoa Casado como parte de la PEC 2 de la asignatura de **visualización de datos** en el máster en Ciencia de Datos por la UOC.

## Estructura del proyecto
Toda la estructura se encuentra en la carpeta ``/src``, conteniendo los notebooks con cada visualización y los datos usados en la carpeta ``/data``, de la siguiente forma:

```
├── src
│   ├── beeswarm.ipynb
│   ├── histograma.ipynb
│   ├── isotype.ipynb
│   ├── isotype.png (imagen producida con isotype.ipynb, guardada ya que github no es capaz de renderizarla)
│   └── datos
│       ├── censo_animales.xlsx
│       ├── sigma_cabs.csv
│       └── student_exam_data.csv
```
## Sobre los datos
Todos los datos utilizados son públicos, y su fuente ha sido referenciada en cada notebook  en el que se usan. Aun así, dejo las referencias aquí:

* [censo_animales.xlsx](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=3e573d68ae8a6410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default), utilizado en ``isotype.ipynb``.
* [sigma_cabs.csv](https://www.kaggle.com/datasets/arashnic/taxi-pricing-with-mobility-analytics), utilizado en ``histograma.ipynb``.
* [student_exam_data.csv](https://www.kaggle.com/datasets/mrsimple07/student-exam-performance-prediction), utilizado en ``beeswarm.ipynb``.

El tratamiento específico seguido se ha explicado en cada notebook.