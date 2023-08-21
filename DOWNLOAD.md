Dataset **Breast Ultrasound Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/7/8/vL/2rAlx8H7HqWZCnYEF9qk1gV7lGMAAOPUak7hVCtqcdEQ0Ro4xiK90W5MLNkHkuDqarLX4Iep4l8PmKxEiFRUMqdAzOBv2emf2Xv4eGgwApczseZ6DCZ2GE0KATGA.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Breast Ultrasound Images', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset/download?datasetVersionNumber=1).