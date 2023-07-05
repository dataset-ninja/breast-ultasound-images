Dataset **Breast Ultrasound Images** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/r/r/YS/Ia4g4Qb9nzKuBlGlCkwlnounKEshGZ6iskT1rLOomTMDDcVoqsKkZXVUFlocIrB88ZJV7UkiJ5ScGXRRj0KGTvTsP8T0WkXA2ka6xXj4J8lX33wQcXv0nWDhZH0W.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Breast Ultrasound Images', dst_path='~/dtools/datasets/Breast Ultrasound Images.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset/download?datasetVersionNumber=1)